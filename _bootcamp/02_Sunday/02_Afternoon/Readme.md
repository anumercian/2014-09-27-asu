### Using and Rmd file, create a short analysis report using R of the gapminder dataset.

1. Move into your working directory (the one you have been working with for git and github)
2. Take a look at the file ([you can re-download it here](http://npk.io/BGRY+)), and pick three countries you are interested in.
3. Write an Rmd script to load the data file, select all the data for that country (hint, use the `subset()` function), and make a three scatter plots (one for each country) that has year on the x-axis and GDP on the y axis. Describe any trends you see for each country using markdown text.
4. Commit your changes using git.  You can do this from the command line or in RStudio if you like.
5. Calculate the mean, min, and max life expectancies for each continent (hint: you use `aggregate()` if you like). Describe what you see in the results using a markdown text.
6. Commit your changes using `git` and push them to github.
7. Make 2 histograms of global life expectancy.  One with the default bin widths and one with narrower bin widths (you can check in help files for the syntax you might need to do this). Explain the differences and any interesting trends in markdown text.
8. Commit your changes and push them to github.
9. Compile the final Rmd file to html, make sure it looks ok, and then commit this html file as well (should be in your working directory) and push everything to github.

