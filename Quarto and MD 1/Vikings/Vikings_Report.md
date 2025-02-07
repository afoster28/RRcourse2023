---
title: "Vikings Report"
author: "Adam Foster"
date: "4/13/2023"
format:
  html:
    toc: true
    toc-depth: 2
    toc-expand: 1
    toc-title: Contents
    toc-location: body
    smooth-scroll: true
    theme: 
      light: flatly
      dark: darkly
  pdf:
    lof: true
    lot: true
  revealjs: 
    output-file: document-revealjs.html
keep-md: true
number-sections: true
number-depth: 2
title-block-banner: true
code-fold: true
code-summary: Show code
latex-tinytex: false
execute:
  echo: fenced
  warning: false
  freeze: true
---



------------------------------------------------------------------------

# ASSIGNMENT

Pick a TV show that had its premieres on TV and thus has some viewership numbers reported on Wikipedia. E.g. [Suits](https://en.wikipedia.org/wiki/List_of_Suits_episodes) (see table just above the References)

Then create a short report (you can copy the content from Wikipedia or other pages for this task) that contains, for example:

(do a commit after each step!)

1.  A brief description of the show (use *italics* for names).
2.  A photo with the logo or a shot from the show itself.
3.  A summary of some basic statistics (e.g. on viewership or ratings).
4.  A graph of the viewership over time.
5.  A graph of the episode-to-episode (or season-to-season) changes in viewership.
6.  A short description of the observed changes that includes inline references to numbers (e.g. the viewership decreased by `insert_calculated_number` between seasons 3 and 5).
7.  Make sure your report looks nice -\> this time we're mostly interested in the output and not necessarily the codes used to achieve it.
8.  `render` your report and save it in the relevant folder of your repo.
9.  Commit the changes and push them to Github.

------------------------------------------------------------------------

*Vikings* is a historical drama television series created and written by *Michael Hirst*. *Vikings* is inspired by the sagas of *Ragnar Lodbrok*, a Viking who is one of the best-known legendary Norse heroes and notorious as the scourge of *Anglo-Saxon England* and *West Francia*. The show portrays *Ragnar* as a farmer from the *Kattegat* who rises to fame by raiding England and eventually becomes a Scandinavian king, with the support of his family and fellow warriors. In the later seasons, the series follows the fortunes of his sons and their adventures in *England, Scandinavia, Kievan Rus', the Mediterranean and North America*.


![Vikings Logo](Vikings_Title.png)

------------------------------------------------------------------------

# Rating Statistics

The show has an 8.5/10 rating on IMDB.

Rotten Tomatoes assign it 93% with the following breakdown.

| Season    | Score |
|:----------|:-----:|
| 1         | 82%   |
| 2         | 93%   |
| 3         | 100%  |
| 4         | 92%   |
| 5         | 92%   |
| 6         | 100%  |

## Ratings over Time

Viewership numbers are not easily accessible - one estimate places the total view count up to 4.36m.

Vikings ratings have decreased with every season, but remained strong, averaging above 7.5.

![Vikings Ratings over Time](Vikings_Rating_Time.png)

Average ratings decreased from 8.3m to 7.7m.
Rating dispersion increased over time as interest in the show varied.
Overall, ratings remained strong well into the maturity of the show, unlike many others.

------------------------------------------------------------------------

