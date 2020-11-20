# UCO swirl R
Swirl course to learn R for the students of the University of Cordoba (Spain)

By [Manuel J. Marin-Jimenez ](https://github.com/mjmarin)

# Quick start
Download file '.swc' in your computer.

First of all, make sure you have installed 'swirl' library in your R system. Otherwise, type
```R
   install.packages("swirl")
```

Then, in the R console, type 
```R
    library(swirl)
    install_course()
```
You will be asked to select the '.swc' you downloaded previously. 
If everything went well, you will receive a message like _'Course installed successfully!'_

Once installed, type 
```R
    swirl()
```

You are ready to select this new course and start learning!

Usefule notes:
* If you want to use this course on a multi-user system (e.g. the computers of your university), you might need to set the following variables, right after loading the swirl library:
```R
   swirl_options(swirl_data_dir="~/swirl_data")
   swirl_options(swirl_courses_dir="~/swirl_courses")
```
This example assumes that you have previously created both folders `swirl_data` and `swirl_courses` in your home directory.
