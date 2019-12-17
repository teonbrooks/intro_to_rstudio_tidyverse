
<!-- README.md is generated from README.Rmd. Please edit that file -->

This is the repo for an introduction to R using the `tidyverse`
developed for an internal workshop at Mozilla. It is hybridized version
based off of @cwickham [BC
Stats](https://www2.gov.bc.ca/gov/content/data/about-data-management/bc-stats)
and the [RStudio Atlanta
workshop](https://github.com/cdhowe/atl-welcome-tidyverse).

The repo currently reflects a 2.5 day version to be delivered Dec 2019.
If you are looking for an older version, try:

  - [Oct 2019: A 1 day
    version](https://github.com/cdhowe/atl-welcome-tidyverse/tree/bb834598453accfd956d1f40bfe3b0d6f5830743)
  - [Jul 2018: A 1.5 day
    version](https://github.com/cwickham/r_intro_bc_stats/tree/v2.0)
  - [Dec 2017: A 2.5 day
    version](https://github.com/cwickham/r_intro_bc_stats/tree/v1.0)

**Solutions** to “Your Turns” available at
[r\_intro\_bc\_stats\_solutions](https://github.com/cwickham/r_intro_bc_stats_solutions).

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" data-property="dct:title">Introduction
to data science with the tidyverse</span> by
<a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/cwickham/r_intro_bc_stats" property="cc:attributionName" rel="cc:attributionURL">Charlotte
Wickham</a> is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative
Commons Attribution 4.0 International License</a>. Based on a work at
<a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/rstudio/master-the-tidyverse" rel="dct:source">https://github.com/rstudio/master-the-tidyverse</a>.

<!--html_preserve-->

<h2>

Overview

</h2>

<p>

This course will give you a feel for the complete data analysis process
in R - from importing and manipulating data through visualization.
You'll see how using code to capture the analysis pipeline leads to
deliverables that are documented, easily reproduced and easily
automated.

</p>

<p>

We'll focus on tools in the
<a href="https://www.tidyverse.org/"><code>tidyverse</code></a> a core
set of R packages that are designed to be easy to learn, easy to use,
and solve the most frequent data analysis problems.

</p>

<p>

During the course, we'll alternate between me introducing a new concept
with some examples, and you applying that concept on your own. You
should expect to spend at least 50% of your time writing code in RStudio
on your own laptop.

</p>

<p>

The first half day is specifically for those who are new to R. Take a
look at the <a href="#prerequisites">prerequisites</a> to see if you
might be able to skip it.

</p>

<h2>

Schedule

</h2>

<table>

<colgroup>

<col width="22%" />

<col width="30%" />

<col width="47%" />

</colgroup>

<thead>

<tr class="header">

<th>

Session

</th>

<th>

Date/Time

</th>

<th>

Topic

</th>

</tr>

</thead>

<tbody>

<tr class="odd">

<td>

Day 1: afternoon

</td>

<td>

Thu Dec 12th 12pm-5pm

</td>

<td>

Getting Started with R and RStudio

</td>

</tr>

<tr class="even">

<td>

Day 2: afternoon

</td>

<td>

Tue Dec 17th 2pm-4pm

</td>

<td>

Data Manipulation with <code>dplyr</code> and Data Visualization 2 with
<code>ggplot2</code>

</td>

</tr>

<tr class="odd">

<td>

Day 3: afternoon

</td>

<td>

tba

</td>

<td>

Modelling, RMarkdown, and Application of Our Learnings

</td>

</tr>

</tbody>

</table>

<h3>

Day 1 - Getting Started with R and RStudio

</h3>

<p>

On your first afternoon you'll focus on getting comfortable writing code
and executing it in RStudio. We'll take things slow as you learn to
navigate RStudio, learn some syntax rules, and how to get help when you
get stuck. Along the way you'll meet R's most ubiquitous objects for
holding data and learn to import data whether it is a CSV, SPSS or Excel
data file.

</p>

<p>

By the end of the day you will be able to:

</p>

<ul>

<li>

Open a notebook in RStudio and execute the code chunks in it

</li>

<li>

Install and load an R package

</li>

<li>

Open the help page for a function or built-in dataset

</li>

<li>

Identify the components of an R function: the function name and
arguments

</li>

<li>

Assign the results of a function to a new variable

</li>

<li>

Get an overview of a dataset that is in a data frame or tibble

</li>

<li>

Import CSV, SPSS and SAS data files

</li>

</ul>

<p>

We will end the day with an introduction to data visualization using the
package <code>ggplot2</code>. You'll see how <code>ggplot2</code>
provides a framework for thinking about plots, which means you only need
to learn one template to make almost any plot you can imagine.

</p>

<h3>

Day 2 - Visualization and Manipulation of Data

</h3>

<p>

In the afternoon we'll focus of the most common types of data
manipulation: extracting subsets from data, adding new variables and
creating grouped summaries. You'll find that doing this is quite
intuitive using the <code>dplyr</code> package which boils down
manipulation into a set of verbs like: <code>filter()</code>,
<code>mutate()</code> and <code>summarise()</code>.

</p>

<p>

We'll finish the day with second half of the data visualization section
with further exploration of the package <code>ggplot2</code>. To
practice, you'll make some of the most common kinds of data
visualizations: histograms, scatterplots and time series plots.

</p>

<p>

By the end of the day you will be able to:

</p>

<ul>

<li>

Create plots in <code>ggplot2</code> to explore data

</li>

<li>

Select variables and filter observations to subset data

</li>

<li>

Add new variables, and transform variables

</li>

<li>

Create grouped summaries of data

</li>

</ul>

<h3>

Day 3 - Modelling, RMarkdown, and Application of Our Learnings

</h3>

<p>

We will introduce some of the most common modelling techniques that are
used in R, primarily <code>lm()</code>. We will also be using the
package <code>broom</code> to present the results of our modeling into
nice and presentable tables.

</p>

<p>

We will then proceed to learn more about RMarkdown, the document type
used throughout these modules, and how we can customize its outputs and
harness the full rendering power of the document.

</p>

<p>

We will end our workshop with a hands-on practicuum that ties together
all the key concepts from our journey into R. We will explore some
survey data from one of our studies at Mozilla and work on a report to
communicate the results.

</p>

<h2>

Prerequisites

</h2>

<p>

The first half-day is specifically for people that are new to R. You can
safely join us starting on day 2 if you already:

</p>

<ul>

<li>

know how to define variables in R

</li>

<li>

have called a few basic functions (e.g. <code>mean()</code>), and

</li>

<li>

know how to open .R script files, and run code in the console

</li>

</ul>

<p>

Although I'll assume on the first half-day you haven't used R, you might
like to get a little experience before we meet. Some options are:

</p>

<ul>

<li>

Work through the non-interactive
<a href="https://www.safaribooksonline.com/library/view/hands-on-programming-with/9781449359089/ch01.html">Chapter
1 of Hands on Programming with R</a>, which introduces RStudio as well
as basic R syntax.

</li>

<li>

Work through the interactive chapters at
<a href="http://tryr.codeschool.com/">Try R</a>

</li>

<li>

Try the free
<a href="https://www.datacamp.com/courses/free-introduction-to-r">“Introduction
to R” course at DataCamp</a>

</li>

</ul>

<h2>

Software Requirements

</h2>

<p>

You'll need to bring a laptop with R and RStudio installed. In addition,
you'll want to install the following
packages:

</p>

<pre><code>install.packages(c(&quot;tidyverse&quot;, &quot;rmarkdown&quot;, &quot;gapminder&quot;, &quot;usethis&quot;))
</code></pre>

<p>

If you've installed the tidyverse before, re-installing it may not
update all the component packages, in which case run,

</p>

<pre><code>tidyverse::tidyverse_update()
</code></pre>

<p>

to identify any out-of-date packages, and follow the instructions to
update them.

</p>

<p>

Don't forget to bring your power cable\!

</p>

<p>

I'll also be providing some additional materials (slides, code and data)
prior to our meeting, keep your eyes out for an email about soon.

</p>

<h2>

Getting the materials

</h2>

<p>

To download the materials, download the zip bundle
<a href="https://github.com/teonbrooks/intro_to_rstudio_tidyverse/archive/mozilla_ur_workshop.zip">here</a>.

</p>

<ol>

<li>

Navigate to where the folder was downloaded (this should be a folder
called <code>r\_intro\_bc\_stats-master</code> on your
<strong>Desktop</strong>)

</li>

<li>

Double-click the file <code>r\_intro\_bc\_stats.Rproj</code> to open up
RStudio

</li>

</ol>

<h2>

Instructor Info

</h2>

<p>

Teon Brooks

</p>

<ul>

<li>

<a href="mailto:teon.brooks@gmail.com">teon.brooks@gmail.com</a>

</li>

<li>

<a href="https://teonian.com">teonian.com</a>

</li>

<li>

@<a href="http://www.twitter.com/teonbrooks">teonbrooks</a>

</li>

</ul>

<!--/html_preserve-->
