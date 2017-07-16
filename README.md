Quick Start Guide
============

EDITING PROJECTS
============

To edit exisiting projects go to the "_projects" folder and find and select the project you wish to edit (Projects are named 01.markdown, 02.markdown, etc.). Projects are sorted according to their name. 01.markdown will display first in the project queue with 02.markdown coming next. You can find a project's file name by looking at the end of the path for the associated project page's url.

![Screenshot](https://blazingpencils.github.io/assets/img/URL-1.png)

After selecting a project file, choose the edit button to begin making your changes.

![Screenshot](https://blazingpencils.github.io/assets/img/ProjectEdit-1.png)

From here you can change common project details such as dates, author, and client (I will cover changing, adding, and removing images in the "ADDING PROJECTS" section). You can also change the project description by editing the final blocks of text (under the "---", starting at line 18 in the below preview) on this page.

![Screenshot](https://blazingpencils.github.io/assets/img/EditPage-1.png)

To save your changes, scroll down and hit the green "Commit changes" button at the bottom of this page.

![Screenshot](https://blazingpencils.github.io/assets/img/Commit-1.png)

Your website will be updated with your project changes! The site may take a few minutes to update to reflect the changes you made.



ADDING PROJECTS
============

If you know how to edit exisiting projects, adding additional projects should be no big deal.

First you'll want to upload the images you'll need for your new project. 

The images for projects are located under "/assets/image/projects" and "/assets/image/projects/carousel". Images in the /assets/image/projects folder are what display on the project grid (on the homepage and on the projects page), while images in the /assets/image/projects/carousel are what display on the specific project's page.

First we'll upload the image you want to appear on the project grid. I edited these images to use a size of 2000x1545px (in some cases adding an extra white background layer), or in case they were originally smaller, a size that kept that same ratio.

Navigate to /assets/image/projects and drag the image you want to use onto the screen, then click the commit button.

Next we'll upload the image(s) you want to appear on the project page in the same way.

Navigate to /assets/image/projects/carousel and drag the image(s) you want to use onto the screen, then click the commit button.

The images you'll be using should be uploaded.

In the "_projects" folder select one of the existing project files (it doesn't matter which), choose the edit button, and then copy that file's contents (Select All > Right Click > Copy).

Next, return to the "_projects" folder and choose the "Create new file" button.

![Screenshot](https://blazingpencils.github.io/assets/img/Create-1.png)

Name the new file in the format 01.markdown, with 01 being whatever comes next in the sequence (if you have 10 projects already, name the new project 11.markdown).

Paste the contents you copied earlier into the new project file, and change the "img:" option to whatever you named your image that you'd like to appear on the homepage grid (the first one you uploaded above to the /projects folder). Change options under "carousel:" to the images you'd like to appear on the project page (the one(s) you uploaded to the "/carousel" folder).

![Screenshot](https://blazingpencils.github.io/assets/img/EditPage-2.png)

Then click the "Commit changes" button at the bottom of the page to save your changes for your new project. The site may take a few minutes to update.








##License
This theme is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
