Introduction to transport data science
================
Robin Lovelace
University of Leeds
<br/><img class="img-footer" alt="" src="https://comms.leeds.ac.uk/wp-content/themes/toolkit-wordpress-theme/img/logo.png">

Note: before you run this tutorial, ensure that you have recently
updated R and RStudio on your computer. Furthermore, you will need to
have installed a number of packages, as described here:
<https://docs.ropensci.org/stats19/articles/stats19-training-setup.html>

There is one additional package that you will need that is not available
on CRAN which can be installed as follows (see [Chapter 2 of
Geocomputation With
R](https://geocompr.robinlovelace.net/spatial-class.html) for details,
this requires the package remotes):

``` r
# install.packages("remotes")
remotes::install_github("Nowosad/spDataLarge")
```

## Agenda

1.  Thinking about transport data science (20 min)
2.  Questions about the homework (10 min)
3.  Practical 2 (2.5 hrs)

# 1 Thinking about (transport) data science

-   Based on the contents of the lecture, come up with *your own*
    definition of data science
-   How do you see yourself using data science over the next 1 year, 5
    years, 20 years
-   What do you hope to get out of it personally?
-   Bonus: think of a question about a transport system you know well
    and how data science could help answer it, perhaps with reference to
    a sketch like that below

#### How much potential is there for cycling across the transport network?

![](https://user-images.githubusercontent.com/1825120/127524923-7d9f5511-84a6-430b-8de9-a603a5524f39.png)

# 2 Questions about homework

1.  Reproduce this script:
    <https://github.com/ITSLeeds/pct/blob/master/inst/test-setup.R>
2.  Work through the transport chapter of Geocomputation with R:
    <https://geocompr.robinlovelace.net/transport.html>

# 3 Practical 2

See
<https://github.com/ITSLeeds/TDS/blob/master/practicals/2-software.md>

<!-- - In terms of future work in an evolving job market? -->
<!-- - In terms of the kinds of problems you want to solve? -->
<!-- ## Sketching research methods (in groups of 2-4, 30 minutes) -->
<!-- Starting with the 1000 'desire lines' dataset of Leeds, sketch-out some research ideas that cover -->
<!-- 1) Hypotheses: generate two hypotheses that are falsifiable and 2 hypotheses that are not falsifiable -->
<!-- 2) Input data: draw schematic representations of additional datasets that you could use alongside the desire lines dataset, with at least one at each of these levels: -->
<!-- - Zones -->
<!-- - Points -->
<!-- - Routes -->
<!-- - Route networks -->
<!-- - Individual -->
<!-- What temporal and spatial resolution could each one have? -->
<!-- 3) Methods: using a flow diagram (e.g. as shown below) -->
<!-- ## Practical, group computer task (30 minutes) -->
<!-- Create a github account (all). See: https://github.com -->
<!-- Building on the follow code chunk (but with no copy-and-pasting), create a data frame that contains the names, coffee habits and like/dislike of bus travel for everyone in your group (just 1 computer per group): -->
<!-- ```{r} -->
<!-- person_name = c( -->
<!--   "robin", -->
<!--   "malcolm", -->
<!--   "richard" -->
<!-- ) -->
<!-- n_coffee = c( -->
<!--   5, -->
<!--   1, -->
<!--   0 -->
<!-- ) -->
<!-- like_bus_travel = c( -->
<!--   TRUE, -->
<!--   FALSE, -->
<!--   TRUE -->
<!-- ) -->
<!-- personal_data = data.frame(person_name, n_coffee, like_bus_travel) -->
<!-- personal_data -->
<!-- ``` -->
<!-- When you are complete, add your code to https://github.com/ITSLeeds/TDS/blob/master/code-r/01-person-data.R -->
<!-- ## Learning outcomes -->
<!-- - Articulate the relevance and limitations of data-centric analysis applied to transport problems, compared with other methods -->
