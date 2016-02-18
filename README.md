# Homework 0

You are currently in the "GitHub repository (repo)" for HW-0. For this to work, you must have installed git and completed all the [SetUp](https://github.com/Middlebury-Data-Science/SetUp), in particular the [RStudio and GitHub](https://github.com/Middlebury-Data-Science/SetUp#rstudio-and-github) step.



## Your Homework

1. Open RStudio and starting in the menu bar, go to File -> New File -> R Markdown...
1. Give it an arbitrary title and select the HTML (not PDF) output format.
1. A document `Untitled1` should pop-up. In that panel, click on the arrow next to the Knit PDF button and select Knit HTML.
1. Give the file a name and save.
1. Click Publish on the top right of the resulting page and say yes to any prompts to install packages.
2. Create an account on [Rpubs.com](http://rpubs.com/)
3. Give your document a Title and a desired Slug (i.e. webpage URL)
4. Note the URL for the page.



## HW Submission Exercise

This exercise will guide you through the HW submission process for the semester. 

1. **Fork (make a copy) of the repo**:
    1. In the top right corner of this page, click on *Fork* and select your GitHub account. This forks a copy of this original repo to your GitHub account.
    1. In the top left of the page, you should see "YOUR_GITHUB_ID/HW-0 forked from Middlebury-Data-Science/HW-0" in blue. This is your fork (copy) of the repo which you will be editing.
    1. Copy the contents of the HTTPS field to your clipboard
1. **Create an *RStudio Project* based on this repo**: From RStudio go to *File* -> *New Project...* -> *Version Control* -> *Git* and 
    1. Paste the clipboard contents into Repository URL
    2. Type `HW-0` as the project directory name.
    3. Select the project subdirectory you want this to be saved in.
1. **Do your homework**: Open and edit `HW-0.Rmd` in RStudio. 
1. **Push (sync) your changes to GitHub**:
    + Select the *Git* panel. You will see a list the files that were modified.
    + Click the checkbox next to `HW-0.Rmd` to select it for syncing with GitHub and click *Commit*. This stages the files to commit, i.e. to check if GitHub can accept these changes.
    + Add a brief commit message describing your changes and click *Commit*.
    + Push (upload) your changes to GitHub:
        + DO THIS ONLY THE FIRST TIME: Go to *Tools* -> *Shell...* -> type `git push` -> type your GitHub login and password -> Close the shell pop-up.  You only need to do this once.
        + ALL FUTURE TIMES: Click *Push*.
1. **Submit your homework**:
    + Go to your fork on GitHub and ensure that the files have updated.
    + Click *New pull request*. This is a request that I pull in your changes so I can view them.
    + Click *Create pull request*
    + In the title field type your name and leave a comment, then click *Create pull request*. I will get an email notification.



## Things to Keep in Mind

1. Once you've forked a copy of HW-X, you should only be looking at the GitHub page of
    * your fork marked *"YOUR_GITHUB_ID/HW-X forked from Middlebury-Data-Science/HW-X"* in blue on the top right
    * and not the original repo marked *"Middlebury-Data-Science/HW-X"*.
1. You can access all your forked repos on GitHub by clicking on your picture icon on the top right of any GitHub page -> *Your Profile* -> selecting the *Repositories* tab
1. RStudio projects are self-contained meaning you can only push file changes to GitHub if you are currently working in that project. If you want to switch between projects, in the top right of RStudio you can toggle between projects by clicking on the arrow. 


## Help! This Isn't Working!

I anticipate this not working for many of you the first time, hence this is just a practice HW-0. If you encounter issues, don't panic and come see me during office hours.
