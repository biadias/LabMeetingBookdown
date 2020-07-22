--- 
title: "Lab Meeting Bookdown Example"
author: "Bia Dias"
date: "2020-07-22"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: biadias/LabMeetingBookdown
description: "Example of how to build a bookdown."
---

# Index



Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX):
<https://yihui.name/tinytex/>.

 


## Housekeeping

(@) Clone the repository MBayOtolith/Thursdata
(@) Create a branch
(@) DO NOT edit the .yml files as they are the main component of the bookdown. 
(@) .travis.yml is the continuous integration file. However, Travis has no access to our organization repos.
(@) On your branch (not the master) the work flow will be: Pull->Make changes->save->stage->commit(add notes)->push
(@) Then the master (Bia) will take your branch and merge->render->publish to have your changes show up on the book


Use the `bookdown::render_book("index.Rmd")` to render the .Rmd files into a bookdown format, all packages must be installed and up to date in order to do so. 


## Good resources

* Using git and github: <https://happygitwithr.com/>
* Rmarkdown Tutorials and Sheet Cheats
  + <https://bookdown.org/yihui/rmarkdown/>
  + <https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf>
  + <https://rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf>
  + <https://rmarkdown.rstudio.com/lesson-15.html>


 


## Notes

_italic_
**Bold**
math equation $a^2 + b^2 = c^2$.


```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```



