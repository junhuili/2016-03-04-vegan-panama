## Introduction to community data analysis using the vegan package in R    

Welcome to the GitHub repository for workshop on community ecology analyses using the `vegan` package at ESA 2015.

**Location and time:**    
Saturday, August 8, 2015    
12:00 PM - 5:00 PM     
Location: Room **306**, Baltimore Convention Center     

## Organizers
[Naupaka Zimmerman](http://naupaka.net) and [Gavin Simpson](http://www.fromthebottomoftheheap.net/).

---

## Pre workshop instructions

### Installing R  
If you don't already have R set up with a suitable code editor, we recommend downloading and installing [R](http://cran.cnr.berkeley.edu) and [RStudio Desktop](http://www.rstudio.com/ide/download/) for your platform. Once installed, open RStudio and install the following packages. Simply paste these commands into your prompt. 

### Installing packages

```r
install.packages("vegan", dependencies = TRUE)
install.packages("plyr")
install.packages("reshape2")
```

### Extra check for MacOS X users
In order to use the `orditkplot()` function you need a working Tcl/Tk installation. This may not be installed on Macs; to check run the following code

```r
library("vegan")
data(varespec)
orditkplot(rda(varespec))
```

If you get errors and not a new window in which you can edit the biplot, then you probably don't have the correct setup on your system to use Tcl/Tk. Refer to the [Tcl/Tk Issues section](http://cran.r-project.org/bin/macosx/RMacOSX-FAQ.html#Tcl_002fTk-issues) of the R Mac OS X FAQ.

### Downloading code/data from this repository  
If you're already familiar with `Git`, then simply clone this repo. If you're not familiar with Git, simply hit the **Download ZIP** button on the right side of this page. If you're not sure where to save it, just download and unzip to your Desktop.

If you're having any trouble with these steps please drop us an [email](mailto:naupaka@gmail.com). We'll also strive to have local copies if you forget to install any of these tools.

---

# License  
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/deed.en_US">Creative Commons Attribution 4.0 International License</a>.
