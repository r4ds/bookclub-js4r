# R4DS JavaScript for R Book Club

Welcome to the R4DS JavaScript for R Book Club!

We are working together to read [_JavaScript for R_](https://book.javascript-for-r.com/) by John Coene (Chapman & Hall/CRC, copyright July 16, 2021, [9780367680633](https://www.routledge.com/Javascript-for-R/Coene/p/book/9780367680633)).
Join the #book_club-js4r channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/js4r).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: Tuesdays, 11:00am CST/CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- 2022-05-24: Chapter 1 (Overview) - Russ Hyde
- 2022-05-31: Chapter 2 (Prerequisites) - Presenter TBD
- 2022-06-07: Chapter 3 (Introduction to Widgets) - Presenter TBD
- 2022-06-14: Chapter 4 (Basics of Building Widgets) - Presenter TBD
- 2022-06-21: Chapter 5 (Your First Widget) - Presenter TBD
- 2022-06-28: Chapter 6 (A Realistic Widget) - Presenter TBD
- 2022-07-05: Chapter 7 (The Full Monty) - Presenter TBD
- 2022-07-12: Chapter 8 (Advanced Topics) - Presenter TBD
- 2022-07-19: Chapter 9 (Linking Widgets) - Presenter TBD
- 2022-07-26: Chapter 10 (Final Revisions) - Presenter TBD
- 2022-08-02: Chapter 11 (Bidirectional Communication) - Presenter TBD
- 2022-08-09: Chapter 12 (A Complete Integration) - Presenter TBD
- 2022-08-16: Chapter 13 (Tips & Tricks) - Presenter TBD
- 2022-08-23: Chapter 14 (Custom Outputs ) - Presenter TBD
- 2022-08-30: Chapter 15 (Custom Inputs) - Presenter TBD
- 2022-09-06: Chapter 16 (Cookies) - Presenter TBD
- 2022-09-13: Chapter 17 (Widgets with Shiny) - Presenter TBD
- 2022-09-20: Chapter 18 (The V8 Engine) - Presenter TBD
- 2022-09-27: Chapter 19 (Machine Learning) - Presenter TBD
- 2022-10-04: Chapter 20 (Managing JavaScript) - Presenter TBD
- 2022-10-11: Chapter 21 (Discover Webpack and NPM) - Presenter TBD
- 2022-10-18: Chapter 22 (Webpack with R) - Presenter TBD
- 2022-10-25: Chapter 23 (Webpack Advanced) - Presenter TBD
- 2022-11-01: Chapter 24 (Conclusion) - Presenter TBD

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_HappyHappy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-js4r")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/js4r).
