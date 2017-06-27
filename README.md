Quick Start Guide
============

##EDITING PROJECTS##

To edit exisiting projects go to the "_projects" folder and find the select the project you wish to edit (Projects are named 01.markdown, 02.markdown, etc.). Projects are sorted according to their name. 01.markdown will display first in the projct queue with 02.markdown coming next. You can find a project's file name by looking at the end of the path for the associated project page's url.

![Screenshot](https://blazingpencils.github.io/assets/img/URL-1.png)

After selecting a project file, choose the edit button to begin making your changes.

![Screenshot](https://blazingpencils.github.io/assets/img/ProjectEdit-1.png)

From here you can change common project details such as dates, author, and client (I will cover changing, adding, and removing images in the "ADDING PROJECTS" section). You can also change the project description by editing the final blocks of text (under the "---", starting at line 18 in the below preview) on this page.

![Screenshot](https://blazingpencils.github.io/assets/img/EditPage-1.png)

To save your changes, scroll down and hit the green "Commit changes" button at the bottom of this page.

![Screenshot](https://blazingpencils.github.io/assets/img/Commit-1.png)

Your website will be updated with your project changes! The site may take a few minutes to update to reflect the changes you made.



##ADDING PROJECTS##

If you know how to edit exisiting projects, adding additional projects should be no big deal.

First you'll want to upload the images you'll need for your new project. 

The images for projects are located under "/assets/image/projects" and "/assets/image/projects/carousel". Images in the /assets/image/projects folder are what display on the homepage grid, while images in the /assets/image/projects/carousel are what display on the project's page.

First we'll upload the image you want to appear on the homepage grid. I edited these images to use a size of 2000x1545px (in some cases adding an extra white background layer), or in case they were originally smaller, a size that kept that same ratio.

Navigate to /assets/image/projects and drag the image you want to use onto the screen, then click the commit button.

Next we'll upload the image(s) you want to appear on the project page in the same way.

Navigate to /assets/image/projects/carousel and drag the image(s) you want to use onto the screen, then click the commit button.

The images you'll be using should be uploaded.

In the "_projects" folder select one of the existing project files (it doesn't matter which), choose the edit button, and then copy that file's contents (Select All > Right Click > Copy).

Next, return to the "_projects" folder and choose the "Create new file" button.

![Screenshot](https://blazingpencils.github.io/assets/img/Create-1.png)

Name the new file in the format 01.markdown, with 01 being whatever comes next in the sequence (if you have 10 projects already, name the new project 11.markdown).

Paste the contents you copied earlier into the new project file, and change the "img:" option to whatever you named your image that you'd like to appear on the homepage grid (the first one you uploaded above). Change options under "carousel:" to the images you'd like to appear on the project page (the one(s) you uploaded to the "/carousel" folder.

![Screenshot](https://blazingpencils.github.io/assets/img/EditPage-2.png)

Then click the "Commit changes" button at the bottom of the page to save your changes for your new project. The site may take a few minutes to update.









Solid. A Bootstrap theme for Jekyll.
============
![Screenshot](https://st4ple.github.io/solid-jekyll/assets/img/browser.png)

This is a [Jekyll](https://jekyllrb.com/) port of the [Solid theme](https://www.blacktie.co/2014/05/solid-multipurpose-theme/) by [blacktie.co](https://www.blacktie.co/). Visit the [live demo](https://st4ple.github.io/solid-jekyll/) for a preview. 

##Usage
This theme can be customized, built and published straight from GitHub, thanks to [GitHub Pages](https://pages.github.com/). A local installation of Jekyll isn't even necessary!

[Fork this repository](https://github.com/st4ple/solid-jekyll/fork) to get started. 
####Customize  
Most general settings and data like site name, colors, address, etc. can be configured and changed right in the main config file: `/_config.yml`
The content of the Home page can be changed here: `/home.html`
The content of the About page can be changed here: `/about.html`
The content of the Portfolio page can be changed here:`/portfolio.html`
The content of the Contact page can be changed here:`/contact.html`
####Add content  
Delete the demo content and publish your own content.
#####Blog post
Create a Blog post by creating a file called `yyyy-mm-dd-name-of-post-like-this.markdown` in the `/_posts/blog/` directory with the following template:
```markdown
---
layout: post          #important: don't change this
title: "Name of post like this"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- blog                #important: leave this here
- category1
- category2
- ...
img: post01.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: thumb01.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---
This text will appear in the excerpt "post preview" on the Blog page that lists all the posts.
<!--more-->
This text will not be shown in the excerpt because it is after the excerpt separator.
```
#####Project post
Create a Project post to go in your Portfolio by creating a file called `yyyy-mm-dd-name-of-the-project.markdown` in the `/_posts/project/` directory with the following template:
```markdown
---
layout: project       #important: don't change this
title:  "Name of the project"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- project             #important: leave this here
img: portfolio_10.jpg #place image (600x450) with this name in /assets/img/project/
thumb: thumb02.jpg
carousel:
- single01.jpg        #place image (1280x600) with this name in /assets/img/project/carousel/
- single02.jpg  
- ...
client: Company XY
website: https://www.internet.com
---
####This is a heading
This is a regular paragraph. Write as much as you like.
```
#####Question entry
Create a Question entry (that is listed in the Frequently Asked section on the Home page) in this directory by creating a file called `yyyy-mm-dd-do-i-have-a-question.markdown` in the `/_posts/project/` directory with the following template:
```markdown
---
layout: question
title:  "Do I have a question?"
date: yyyy-mm-dd hh:mm:ss
author: First Last
categories:
- question            #important: leave this here
---
####Can I use this theme for my website?
Of course you can!
```
####Publish
To publish with [GitHub Pages](https://pages.github.com/), simply create a branch called `gh-pages`in your repository. GitHub will build your site automatically and publish it at `https://yourusername.github.io/repositoryname/`.  
If there are problems with loading assets like CSS files and images, make sure that the `baseurl` in the `_config.yml`is set correctly (it should say `/repositoryname`).

If you want to host your website somewhere else than GitHub (or just would like to customize and build your site locally), please check out the [Jekyll documentation](https://jekyllrb.com/). 

##License
This theme is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
