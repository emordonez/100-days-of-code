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

**Links to work:** [Repository for Markdown-generated resumes](https://github.com/emordonez/resumes),
