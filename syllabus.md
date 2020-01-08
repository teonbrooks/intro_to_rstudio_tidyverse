Overview
--------

This course will give you a feel for the complete data analysis process
in R - from importing and manipulating data through visualization.
You'll see how using code to capture the analysis pipeline leads to
deliverables that are documented, easily reproduced and easily
automated.

We'll focus on tools in the [`tidyverse`](https://www.tidyverse.org/) a
core set of R packages that are designed to be easy to learn, easy to
use, and solve the most frequent data analysis problems.

During the course, we'll alternate between me introducing a new concept
with some examples, and you applying that concept on your own. You
should expect to spend at least 50% of your time writing code in RStudio
on your own laptop.

The first half day is specifically for those who are new to R. Take a
look at the [prerequisites](#prerequisites) to see if you might be able
to skip it.

Schedule
--------

<table>
<colgroup>
<col width="22%" />
<col width="30%" />
<col width="47%" />
</colgroup>
<thead>
<tr class="header">
<th>Session</th>
<th>Date/Time</th>
<th>Topic</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Day 1: afternoon</td>
<td>Thu Dec 12th 12pm-5pm</td>
<td>Getting Started with R and RStudio, and Data Visualization 2 with <code>ggplot2</code></td>
</tr>
<tr class="even">
<td>Day 2: afternoon</td>
<td>Tue Dec 17th 2pm-4pm</td>
<td>Data Manipulation with <code>dplyr</code>, and Data Visualization 2 with <code>ggplot2</code></td>
</tr>
<tr class="odd">
<td>Day 3: afternoon</td>
<td>tba</td>
<td>Modelling, RMarkdown, and Application of Our Learnings</td>
</tr>
</tbody>
</table>

### Day 1 - Getting Started with R and RStudio

On your first afternoon you'll focus on getting comfortable writing code
and executing it in RStudio. We'll take things slow as you learn to
navigate RStudio, learn some syntax rules, and how to get help when you
get stuck. Along the way you'll meet R's most ubiquitous objects for
holding data and learn to import data whether it is a CSV, SPSS or Excel
data file.

By the end of the day you will be able to:

-   Open a notebook in RStudio and execute the code chunks in it
-   Install and load an R package
-   Open the help page for a function or built-in dataset
-   Identify the components of an R function: the function name and
    arguments
-   Assign the results of a function to a new variable
-   Get an overview of a dataset that is in a data frame or tibble
-   Import CSV, SPSS and SAS data files

We will end the day with an introduction to data visualization using
the package `ggplot2`. You'll see how `ggplot2` provides a framework
for thinking about plots, which means you only need to learn
one template to make almost any plot you can imagine.

### Day 2 - Visualization and Manipulation of Data

In the afternoon we'll focus of the most common types of data
manipulation: extracting subsets from data, adding new variables and
creating grouped summaries. You'll find that doing this is quite
intuitive using the `dplyr` package which boils down manipulation into a
set of verbs like: `filter()`, `mutate()` and `summarise()`.

We'll finish the day with second half of the data visualization section
with further exploration of the package `ggplot2`.
To practice, you'll make some of the most common kinds of data
visualizations: histograms, scatterplots and time series plots.

By the end of the day you will be able to:

-   Create plots in `ggplot2` to explore data
-   Select variables and filter observations to subset data
-   Add new variables, and transform variables
-   Create grouped summaries of data

### Day 3 - Modelling, RMarkdown, and Application of Our Learnings

We will introduce some of the most common modelling techniques that are
used in R, primarily `lm()`. We will also be using the package `broom`
to present the results of our modeling into nice and presentable tables.

We will then proceed to learn more about RMarkdown, the document type
used throughout these modules, and how we can customize its outputs
and harness the full rendering power of the document.

We will end our workshop with a hands-on practicuum that ties together
all the key concepts from our journey into R. We will explore some
survey data from one of our studies at Mozilla and work on a report
to communicate the results.

Prerequisites
-------------

The first half-day is specifically for people that are new to R. You can
safely join us starting on day 2 if you already:

-   know how to define variables in R
-   have called a few basic functions (e.g. `mean()`), and
-   know how to open .R script files, and run code in the console

Although I'll assume on the first half-day you haven't used R, you might
like to get a little experience before we meet. Some options are:

-   Work through the non-interactive [Chapter 1 of Hands on Programming
    with
    R](https://www.safaribooksonline.com/library/view/hands-on-programming-with/9781449359089/ch01.html),
    which introduces RStudio as well as basic R syntax.
-   Work through the interactive chapters at [Try
    R](http://tryr.codeschool.com/)
-   Try the free ["Introduction to R" course at
    DataCamp](https://www.datacamp.com/courses/free-introduction-to-r)

Software Requirements
---------------------

You'll need to bring a laptop with R and RStudio installed. In addition,
you'll want to install the following packages:

    install.packages(c("tidyverse", "rmarkdown", "gapminder", "usethis"))

If you've installed the tidyverse before, re-installing it may not
update all the component packages, in which case run,

    tidyverse::tidyverse_update()

to identify any out-of-date packages, and follow the instructions to
update them.

Don't forget to bring your power cable!

I'll also be providing some additional materials (slides, code and data)
prior to our meeting, keep your eyes out for an email about soon.

Getting the materials
---------------------

To download the materials, download the zip bundle [here](https://github.com/teonbrooks/intro_to_rstudio_tidyverse/archive/mozilla_ur_workshop.zip).

1.  Navigate to where the folder was downloaded (this should be a folder
    called `r_intro_bc_stats-master` on your **Desktop**)
2.  Double-click the file `r_intro_bc_stats.Rproj` to open up RStudio


Instructor Info
---------------

Teon Brooks
-   <teon.brooks@gmail.com>
-   [teonian.com](https://teonian.com)
-   @[teonbrooks](http://www.twitter.com/teonbrooks)
