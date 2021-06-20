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

**Links to work:** [Website commit 1](https://github.com/emordonez/website/commit/c2b11e87e0b675d6696b7700dee6d4feeb4f4b65), [2](https://github.com/emordonez/website/commit/48e060c55b39e86fb1cb9e103b68a595d5e1cc2b)

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

### Day 17: May 3, 2021

**Today's progress:** TOC highlighting now detects when an entry is being scrolled into from below.
Fixed a prior issue with this implementation, where the Intersection Observer logic selected the second-to-last TOC entry when initialized.

**Thoughts:** I liked the elegance of the original TOC, but I believe users will intuitively expect a TOC to indicate they've scrolled up into a previous section since that's they see.
It took me a nontrivial amount of time to learn how to implement something so small, but I think it was worth it. (I now know a _lot_ about Intersection Observers!)

**Link to work:** [Website commit](https://github.com/emordonez/website/commit/91213c6626345fac13ee2d2d98f515c1639ea5a1)

### Day 18: May 4, 2021

**Today's progress:** Added basic page transitions to the website.
Downloaded a CSV of World Bank data for ASEAN countries and began reshaping and cleaning it with Pandas.

**Thoughts:** At first I was manually rehsaping the CSV from a wide to long format, but I decided to do it all in Python as a refresher on Pandas syntax and methods.
It's a simple exercise, but I think it showcases essential skills for the jobs I'm looking for.

**Link to work:** [Website commit](https://github.com/emordonez/website/commit/b7cda8b572a072fd9136ed2ae79a161c53c2d89d)

### Day 19: May 5, 2021

**Today's progress:** Completed cleaning ASEAN macro data.
Finished one plot with the data and read up on other new plot styles to try.
Began cleaning PSA data on Philippine regional GDP and population.

**Thoughts:** I'm now using Reticulate to use Python and R together.
I find data cleaning and computation easier with Python, but manipulation and visualization easier with R.

### Day 20: May 6, 2021

**Today's progress:** Finished three R plots of the ASEAN macro data, for four in total.

**Thoughts:** I'm becoming more confident in my visual design choices and in how to use ggplot2.
I think I'm getting faster at the whole process of finding, cleaning, and depicting data.

**Link to work:** [Gist](https://gist.github.com/emordonez/78658ad9507efa2a6f586a9d24d23ea3)

## Week 3

### Day 21: May 7, 2021

**Today's progress:** Finished cleaning the Philippines PSA data and completed one plot for ranking regions by GDP per capita.

**Thoughts:** I'm getting a better understanding of how data frames and series are piped into ggplot.
I might be able to revisit some earlier plots and tidy up my now-naive approach to certain things.

### Day 22: May 9, 2021

**Today's progress:** Looked into how to read geoJSON and shapefiles in R.
Created a geospatial plot using a humdata shapefile set.

**Thoughts:** I couldn't resolve neither geojsonio's nor rgdal's dependencies, so I opted for sf.
Geospatial plotting is straightforward with ggplot, and I like the workflow enough to want to try more geospatial visualizations.
The drawback with this one is the size of the shapefile (~200MB), which slowed the rendering too much for my liking.

### Day 23: May 10, 2021

**Today's progress:** Finished the final plot for Philippine regional GDP.

**Thoughts:** I think this visualization affirmed my understanding of ggplot with how I manipulated breaks, labels, and limits.
I would feel very confident explaining to a recruiter or employer that I can use ggplot for nearly anything entry-level that they need.

**Link to work:** [Gist](https://gist.github.com/emordonez/de0a8019c830285f327bbd39a152cfa7)

### Day 24: May 12, 2021

**Today's progress:** Changed content directory structure to organize website posts by date.
Made minor adjustments to previous code layout in an effort to achieve a more consistent code style.

**Thoughts:** It was very frustrating trying to get recursive fetching and routing to work since yesterday.
Note that the Nuxt Content docs do not address this or dynamic routing very well.

**Links to work:** [Commits 1](/), [2](/), [3](/)

### Day 25: May 13, 2021

**Today's progress:** Wrote a Python script to create new blog posts by emulating Hugo archetypes.
Added the Vue Router to the Connecting Wall app.

**Thoughts:** Python really is like duct tape, and I should consider writing more utility scripts considering how easy it is to install and run them.

**Link to work:** [Gist](https://gist.github.com/emordonez/ecb5d88c0be3eeeec48380c36739dba3)

### Day 26: May 14, 2021

**Today's progress:** Opened a pull request to switch out Nuxt Image components for the native HTML img tag.

**Thoughts:** I'm going to start testing new features/implementations on new branches so that I can both preview the deploy on Netlify and also learn the workflow of opening and merging pull requests.

**Link to work:** [Pull request commit](https://github.com/emordonez/website/pull/1/commits/76449733f1c0562cb8078a3b211da3f5e70c6859)

### Day 27: May 15, 2021

**Today's progress:** Created a Cloudinary account.
Tried Nuxt Image again but specified Cloudinary as the provider, to no avail.

**Thoughts:** I'm unsatisfied with Netlify LMS and am unsure if Git LFS is the way to go (I don't want image assets bloating the repository, but even local pointers seem like clutter to me).
Cloudinary seems to be the most common solution for easy image delivery.

## Week 4

### Day 28: May 16, 2021

**Today's progress:** Dropped in Nuxt Cloudinary components to deliver my Cloudinary-hosted images.

**Thoughts:** This was the easiest and what probably should have been the first approach to remote hosting images.
Cloudinary offers tons of free features that I can't see myself using at the moment, so it may be overkill for my simple use cases.
But it's fast and free!

### Day 29: May 17, 2021

**Today's progress:** Migrated from Tailwind to Windi.
Added a simple hero pattern background to the website.

**Thoughts:** I'm getting the hang of managing git branches and heads.

**Links to work:** [Pull requests 1](https://github.com/emordonez/website/pull/1), [2](https://github.com/emordonez/website/pull/2)

### Day 30: May 19, 2021

**Today's progress:** Integrated the Vue Router into the Connecting Wall.
Walls are now stored as local JSON and then dynamically routed.
Added a simple Timer component that visually counts down but doesn't affect game logic yet.

**Thoughts:** I am very satisfied with how this project is shaping into a polished product!
I can clearly see how far I've come since the first attempts to get the Bricks and Wall grid to even function.

**Link to work:** [Pull request](https://github.com/emordonez/connecting-wall/pull/1)

### Day 31: May 20, 2021

**Today's progress:** Restructured the Connecting Wall for game logic to be run through one component.
Created a Modal component with background blur.
Tweaked the Timer to end the game if not solved within the time limit.

**Thoughts:** Got a lot done!
I'm now consciously trying to commit more frequently, every time I succeed in a smaller tweak toward a more significant change (like committing the Modal once it was functional and then again once I got the blur to work, rather than trying to complete everything in one big commit).

**Link to work:** [Pull request](https://github.com/emordonez/connecting-wall/pull/2)

### Day 32: May 21, 2021

**Today's progress:** Connecting Wall now automatically resolves if time runs out.

**Thoughts:** I took advantage of existing functions to make implementing this feature simple.
Apart from one missing break statement that caused a hiccup, everything worked seamlessly!

**Link to work:** [Pull request](https://github.com/emordonez/connecting-wall/pull/3)

### Day 33: May 22, 2021

**Today's progress:** Implemented a three strike system after two groups have been found.
Wall now freezes after striking out, then automatically resolves.
Merged pull request, so game now has working time and strike limits.

**Thoughts:** The existing logic worked with these new features relatively easily, only requiring minor tweaks in props and emits.
I considered restructuring the entire thing to have an "ideal" flow for all the new and existing attributes together, but I think it's more realistic to determine how to incorporate new features on top of existing ones.
In any case, the project functions exactly as I wanted it to.
I should document all the obstacles and design decisions so that I can compare my determinations to what an "ideal" flow might be.

**Link to work:** [Pull request](https://github.com/emordonez/connecting-wall/pull/3)

### Day 34: May 24, 2021

**Today's progress:** Added sound effects from _Only Connect_ to the connecting wall.
Made a template grid with two-way data binding for the wall editor.

**Thoughts:** I initially was going to add a third-party package to handle sound, but I figured the use case wasn't complex enough to justify it.
I think it paid off more as a learning experience to implement audio using vanilla JS.

**Link to work:** [Pull request 1](https://github.com/emordonez/connecting-wall/pull/4), [2](https://github.com/emordonez/connecting-wall/pull/5)

## Week 5

### Day 35: May 25, 2021

**Today's progress:** Finished the wall editor with data encoding and decoding, form validation, and dynamic routing.
User-created walls can now be shared and played.

**Thoughts:** I am extremely satisfied with the end result that I will call the first iteration of this project!
It's in a working and polished state that I can comfortably show off to others.
I already have the next round of major features in mind.

**Link to work:** [Pull request](https://github.com/emordonez/connecting-wall/pull/5)

### Day 36: June 9, 2021

**Today's progress:** Started a new data analysis project with the Transfermarkt data, beginning with a data setup script.

**Thoughts:** It's been about two weeks since my last active day of coding, unfortunately.
I found it very difficult to keep the flow going once my daily schedule was disrupted, with guests coming to stay here.
I can see from this how much more helpful it would have been to block off a specific time every day for coding.
Instead, I've become too used to all my time being free time and thus feeling like I can code anytime.
Getting started after a long, physical day or at the very end of the night is a challenge!

### Day 37: June 10, 2021

**Today's progress:** Played around with simple and multiple regressions in R.

**Thoughts:** I needed a refresher on linear regressions after having not used or studied them in a couple years now.
Specifically, I had to remind myself what assumptions must be satisfied before considering a regression to be valid.

### Day 38: June 13, 2021

**Today's progress:** Calculated Gini coefficients for total transfer spending between and within leagues.
Used best fit lines to determine whether trends over time are significant.

**Thoughts:** I'm satisfied with this trend analysis, regardless of how simple it is on its face.
I think a valuable lesson from this coding challenge, abstracted to something like this, is to recognize that achieving something small but significant is still good.
Although this result doesn't reveal anything novel or profound, it still provides a solid foundation should I ever want to return to it after learning more advanced techniques.

### Day 39: June 14, 2021

**Today's progress:** Read up on tests for normality and on nonparametric tests.
Played around with Shapiro&ndash;Wilk and Mann&ndash;Whitney _U_ tests before and after log and root transformations of the data.
Settled on using _U_ tests for comparing defender vs. attacker values.

**Thoughts:** Although the data are right-skewed, they look normal but with significant left skew after a log transformation, hence not normal.
This does not concern me as much as it did before, because based on my understanding the _U_ test should suffice for my non-normal data.
Reading up on all these new tests and assumptions is showing me just how little I know despite my strong grasp of what I did in undergrad.
But that excites me for everything there is to learn and do in grad school!

### Day 40: June 15, 2021

**Today's progress:** Ran two regressions: One to estimate the premium paid for English players in the Premium League, and one to estimate the "treatment" effect that the Homegrown Player Rule had on this premium.

**Thoughts:** I imitated the steps of my regression analysis from an econ research paper, and it translated well here.
I'm very happy with the results and what their significance could suggest, but I still have to figure out which of the two regressions to use and if they can both be used and reported.

### Day 41: June 16, 2021

**Today's progress:** Spread Gini coefficient data in wide formats for table layout.
Results are now output to TeX with xtable.

**Thoughts:** I've finished the first third of the data analysis and can begin the writeup of that part of the discussion and results.

## Week 6

### Day 42: June 17,  2021

**Today's progress:** With a log transformation for defenders' and attackers' fees, ran Shapiro--Wilk tests for normality and Kolmogorov--Smirnov tests to determine if the distributions differ.
Formatted test results into LaTeX tables.

**Thoughts:** I'm not sure if reporting the test statistics is necessary, but I'll keep them in the report for the sake of being thorough.

**Links to work:** [Project repository](https://github.com/emordonez/football-transfer-analysis), [commits 1](https://github.com/emordonez/football-transfer-analysis/commit/f7ad4acc8ecb6c1df908f1f48d9fe021c6b62c58), [2](https://github.com/emordonez/football-transfer-analysis/commit/2770a92bc6d081e8c0e63d4a40bc99feba41af96)

### Day 43: June 18, 2021

**Today's progress:** Restructured setup and first analysis code and wrote additional comments.
Added the Mann--Whitney _U_ test for comparing mean ranks and began implementing a permutation test for comparing medians.

**Thoughts:** I did not get as much done today as I wanted to (ideally, I should've finished the permutation test and trend fit).

### Day 44: June 19, 2021

**Today's progress:** Finished the permutation test and trend fitting for median differences.

**Thoughts:** No looming thoughts, I just need motor through the rest of this analysis!
