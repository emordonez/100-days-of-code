# 100 Days Of Code &ndash; Log

## Week 0

### Day 0: April 12, 2021

**Today's progress:** Altered my website's Vue icon component to import SVGs automatically.

**Thoughts:** I need a regex refresher.
I can make sense of `require.context()` now, but managing image loaders with webpack still confuses me.

**Link to work:** [Website commit](https://github.com/emordonez/website/commit/85ec813df7c5d9add4113869ab75347f746f79e7)

### Day 1: April 13, 2021

**Today's progress:** Implemented a website Vue component to load images in Markdown content, fine-tuned it to handle GIFs.

**Thoughts:** The simplest solution usually is to see if there's already a [module that does what I need](https://image.nuxtjs.org/) then modify it if needed  ¯\\\_(ツ)_/¯

**Links to work:** [Website commit 1](https://github.com/emordonez/website/commit/66949f27d1c9c5d05113674b464193a329e8ddbd), [2](https://github.com/emordonez/website/commit/33ee93f4e51b2aed95e70e5399bdfda523202c48)

### Day 2: April 14, 2021

**Today's progress:** Mostly organizational and cleanup work.
Structured my Transfermarkt webscraper into a proper Python project, which can now be imported as a module or run as a script.

**Thoughts:** I learned a lot about how Python modules and packages are structured.
Although writing up full documentation and setup for something simple or "self-explanatory" initially seemed excessive, I see the benefit in how readily extendable the webscraper is now.

**Link to work:** [New project repository for Transfermarkt transfers](https://github.com/emordonez/transfermarkt-transfers)

### Day 3: April 15, 2021

**Today's progress:** Added transfer windows and a default cleaning option to the Transfermarkt web scraper.
Fixed an error caused when no league data is available.

**Thoughts:** I feel more confident after running the full script and fixing what runtime errors occurred.
However, I still need to inspect the scraped/cleaned data to make sure everything looks sensible.
Next up is a simple testing suite.

**Links to work:** [Project commit 1](https://github.com/emordonez/transfermarkt-transfers/commit/2f6dbd794de84680d524be0b2a9d820748a420ba), [2](https://github.com/emordonez/transfermarkt-transfers/commit/114dec6c9b6e61b21fbbf76e31dc809b4dca75c2), [3](https://github.com/emordonez/transfermarkt-transfers/commit/314413ea12c90aadfe5e09af1854fa009c11c7a5)

### Day 4: April 16, 2021

**Today's progress:** Assessed the Transfermarkt data by determining null counts.

**Thoughts:** This was a good refresher on dictionary comprehensions and methods.

**Link to work:** [Data dump](https://github.com/emordonez/transfermarkt-transfers/commit/4d6c33da9c9df710a981caa41b987973a9353284), will find a way in the future to post the Jupyter notebook

### Day 5: April 20, 2021

**Today's progress:** Started a Vue side project that emulates the connecting wall from Only Connect.
Implemented a basic grid that randomly shuffles a static source of connected clues.

**Thoughts:** I unintentionally took three days off due to a family visit and a vaccination.
Although this broke a streak of consecutive days coding, I wasn't upset by it because I've put in multiple hours per day in the days prior.
But I did notice I was more sluggish in getting started, so lost momentum is tangible and should not be underestimated.

**Link to work:** [New project repository for Only Connect connectin wall](https://github.com/emordonez/connecting-wall)

### Day 6: April 21, 2021

**Today's progress:** Completed all basic functionality for the connecting wall: Selecting clues, checking clues, rearranging correctly identified clues, and conditional color styling.

**Thoughts:** I am very satisfied with the look, feel, and flow of the walls' basic functionality.
What I thought were naive implementations turned out to be very effective and as close to canonical for Vue as I can find, but the code can probably be cleaned further.

**Link to work:** [Project commit](https://github.com/emordonez/connecting-wall/commit/eb07e17d2257c7068dcf626924d84599c66ef751)

## Week 1

### Day 7: April 22, 2021

**Today's progress:** Implemented automatic scaling font size, fixed a PurgeCSS issue, and animated transitions in the connecting wall.
Deployed a test wall on Netlify.

**Thoughts:** The size of the project seems daunting now that I see how many features I want to implement and how bare the minimal working example is compared to that, but it didn't feel overwhelming when I focused only on small bits of functionality at a time.
It feels easier to take on the rest of the project this way.

**Links to work:** [Test deploy for the connecting wall](https://connecting-wall.netlify.app/), [project commits 1](https://github.com/emordonez/connecting-wall/commit/d02e24d4516c7ea7adf4ff0e7c67c0f756c37f3e), [2](https://github.com/emordonez/connecting-wall/commit/3661c9a6032d0ee04bb18e57a4fd711e3c6cce78), [3](https://github.com/emordonez/connecting-wall/commit/48dd63b96daa25f268b8ff96413537fe028fe7ca)

### Day 8: April 23, 2021

**Today's progress:** Finished a CSS stylesheet for Markdown-generated resumes and cover letters.
Made a Makefile to streamline the process.

**Thoughts:** I wrote the stylesheet from scratch with vanilla CSS declarations, and the success of the end result makes me feel like I do have a good understanding of CSS fundamentals, rather than a fluid familiarity with frameworks and shortcuts.
Even though it's a small and simple example, I can readily see how I can expand upon it.

**Link to work:** [Repository for Markdown-generated resumes](https://github.com/emordonez/resumes)

### Day 9: April 24, 2021

**Today's progress:** Tweaked a JS util to compute image source URLs in the site's static directory.
Made minor adjustments to site styling and began working on an author bio component.

**Thoughts:** The image URL workaround is temporary until I learn more about image providers and my CDN options.
Eventually, I want no static assets to be hosted in the site repo.

### Day 10: April 25, 2021

**Today's progress:** Completed the author bio component and restuctured the homepage layout.

**Thoughts:** I think my site is looking pretty good now!

**Links to work:** [Commit 1](https://github.com/emordonez/website/commit/c2b11e87e0b675d6696b7700dee6d4feeb4f4b65), [2](https://github.com/emordonez/website/commit/48e060c55b39e86fb1cb9e103b68a595d5e1cc2b)

### Day 11: April 26, 2021

**Today's progress:** Added a card list for works in progress on my website.

### Day 12: April 28, 2021

**Today's progress:** Tweaked the grid layout and flow for the "latest posts" cards on my website.
Began revisiting an old set of R visualizations using the soccer transfers data set.

### Day 13: April 29, 2021

**Today's progress:** Updated the R visualizations with the new data.
Changed the plot styles for the club transfer profits (bar), league spending comparison (area), and most expensive transfers (lollipop).
Found a hacky workaround online to pipe the data from the treemap into a ggplot, recreating the treemap but with consistent theming.

**Thoughts:** I'm also late logging the past three days, one of which I did not code for an hour.
I haven't pushed or even committed any of the website tweaks or R visualizations, so I'm relying upon my memory to note when I worked on something and to what extent.
Honestly, the hours blend together, and it's difficult to remember when my various "a-ha!" moments were, which, in previous logs, were the moments at which I'd commit and note the progress.
Consider this a small bump that shows the importance of small contributions and consistent logging for the long term.

## Week 2

### Day 14: April 30, 2021

**Today's progress:** Explored options on how to scale ggplot figures, particularly ragg.
Settled on using ggsave to output an SVG then exporting a manually resized PNG with Inkscape.

**Thoughts:** It's a little offputting that something as trivial as scaling figures is nontrivial with R and ggplot, but ggplot's ease and aesthetics still win out for me.
I could probably simplify the Inkscape process with a Python script.

**Link to work:** [Gist of the R script](https://gist.github.com/emordonez/5fe7d760ceba4aa0c930ca6496ba1b42)

### Day 15: May 1, 2021

**Today's progress:** Looked into remark and rehype plugins to wrap Markdown content.
Attempted to make the table of contents more dynamic by observing sections instead of headers, but to no avail.

**Thoughts:** Although the remark/rehype plugins I've tried are not working as intended, I stumbled upon several other plugins that I want to try.
Take note of them for future Nuxt projects.

### Day 16: May 2, 2021

**Today's progress:** Decided against wrapping headers and content.
Implemented smooth scrolling to hash links with the appropriate offset to keep the header in view.

**Thoughts:** Observing sections still seems the most straightforward way to get the TOC behavior I want with Intersection Observer, but neither of the remark/rehype plugins I tried work nicely with Nuxt.
I may need to tweak how the currently active entry is recorded and styled.

**Link to work:** [Website commit](https://github.com/emordonez/website/commit/e38ba329b1b03a27a9a02b42b224afcf34462ce7)
