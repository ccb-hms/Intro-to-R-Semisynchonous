# Introduction to R - Part II

## I. Please **study the contents** and **work through all the code** within the following lessons:

   2.1 [Data Wrangling: Subsetting Vectors and Factors](../lessons/05_introR-data-wrangling.md)
      <details>
          <br>Manipulating, filtering, and selecting data are some of the core steps in any analysis.<br><br> This lesson will cover:<br>
            - Subsetting vectors and factors<br>
            - Using logical operators<br>
            - Manipulating factors<br>
        </details>

   2.2 [Packages and libraries](../lessons/04_introR_packages.md)
       <details>
           <br>Base R is incredibly powerful, but it cannot do everything. R has been built to encourage community involvement in expanding functionality. Thousands of supplemental add-ons, also called "packages" have been contributed by the community. Each package comprises of several functions that enable users to perform their desired analysis. <br><br>This lesson will cover:<br>
             - Descriptions of package repositories<br>
             - Installing a package<br>
             - Loading a package<br>
             - Accessing the documention for your installed packages and getting help<br><br>
         </details>
         
   2.3 [Data wrangling: data frames, matrices and lists](../lessons/07_introR-data-wrangling2.md)
       <details>
           <br>In class we covered data wrangling (extracting/subsetting) information from single-dimensional objects (vectors, factors). The next step is to learn how to wrangle data in two-dimensional objects.<br><br>This lesson will cover:<br>
             - Examining and extracting values from two-dimensional data structures using indices, row names, or column names<br>
             - Retreiving information from lists<br><br>
         </details>

   2.4 [The %in% operator](../lessons/08_identifying-matching-elements.md)
       <details>
         <summary><i>Click here for a preview of this lesson</i></summary>
           <br>Very often you will have to compare two vectors to figure out if, and which, values are common between them. The <code>%in%</code> operator can be used for this purpose.<br><br>This lesson will cover:<br>
             - Implementing the <code>%in%</code> operator to evaluate two vectors<br>
             - Distinguishing <code>%in%</code> from <code>==</code> and other logical operators<br>
             - Using <code>any()</code> and <code>all()</code> functions<br><br>
         </details>

   2.5 [Reordering and matching](../lessons/09_reordering-to-match-datasets.md)
       <details>
         <summary><i>Click here for a preview of this lesson</i></summary>
           <br>Sometimes you will want to rearrange values within a vector (row names or column names). The <code>match()</code> function can be very powerful for this task.<br><br>This lesson will cover:<br>
             - Maunually rearranging values within a vector<br>
             - Implementing the <code>match()</code> function to automatically rearrange the values within a vector<br><br>
         </details>

   2.6 [Setting up a data frame to plot (+ the `map()` function)](../lessons/10_setting_up_to_plot.md)
       <details>
           <br>We will be starting with visualization in the next class. To set up for this, you need to create a new metadata data frame with information from the counts data frame. You will need to use a function over every column within the counts data frame iteratively. You could do that manually, but it is error-prone; the <code>map()</code> family of functions makes this more efficient.<br><br>This lesson will cover:<br>
             - Utilizing <code>map_dbl()</code> to take the average of every column in a data frame<br>
             - Briefly discuss other functions within the <code>map()</code> family of functions<br>
             - Create a new data frame for plotting<br><br>
        </details>
     
[Solution to exercises in above lessons](../homework/day2_hw_answer-key.R)

## II. **Complete the exercises**:
   * Note that some exercises assume you have variables in your environment from the lessons. 
   * [Practice exercises II](../activities/Day3_activities.md)
   * **Copy over** your code from the exercises into a text file. 
   * **Upload the saved text file** to [Dropbox](https://www.dropbox.com/request/oys0ebmAT4xJ0GeecNL1).
   
### Questions?
* ***If you get stuck due to an error*** while running code or have a conceptual question, post a question on [Slack](https://ccb-intro-to-r.slack.com) or [email us](mailto:christopher_magnano@hms.harvard.edu).
              
***

## Cheatsheets
* [base R cheatsheet](../cheatsheets/base-r.pdf)
* [RStudio cheatsheet](../cheatsheets/rstudio-ide.pdf)
* [ggplot2 cheatsheet](../cheatsheets/data-visualization-2.1.pdf)

****

*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*
