# mkdocs site set-up

First, We need pip install

Install Python by downloading an installer appropriate for your system from python.org and run it

pip should come installed with Python
If you need to upgrade pip
type "pip install --upgrade pip"

Step 1. pip install mkdocs
this will give you the mkdocs command installed on your system

Step 2: run "mkdocs --version" to check everything worked ok

mkdocs, version 1.1.2 from c:\users\jsanc\anaconda3\lib\site-packages\mkdocs (Python 3.7)

Getting Started 
1. type command mkdocs new [dir-name]
2. type cd [dir-name]

Creates a single configuration file "mkdocs.yml"
and a folder named docs that will contain your documentation source files. It has index.md.

To preview docummentation. Make sure you are in the same directory as the mkdocs.yml configuration file and then start the server by running the [mkdocs serve] command

Open up http://127.0.0.1:8000/ in your browser
(You are able to look at your updates for the site on the previous link in real-time)

mkdocs uses _Markdown Formatting Language_

In the docs folder, contains the index.md file which is the homepage for your site. If you want to add additional pages you may create additional files with .md extension in the same /docs folder.

I am able to create an .md file using notepad app on Windows clicking "Save As" an adding the extension .md to the file name. Sublime Text Editor is also another good text editor I use.

## Embed a video
For this example, I am embedding a video from youtube. Pick a video from youtube you would like to embed. Youtube enables you to embed videos. 

Click on the share button 
![](https://i.imgur.com/pqgu1fg.png)
click the embed button on its site
![](https://i.imgur.com/nZyNR0y.png)
and you can copy the code it gives you(the embed code should start with <iframe.....)
![](https://i.imgur.com/syEi4hi.png)

Make sure the embed code is _not indented_ or doesn't have spaces before the start of the code because otherwise the video does not show up.
![](https://i.imgur.com/17lHyQH.png)

And Ta Da! You have a video embedded

![](https://i.imgur.com/oXg5PKV.png)


## Render mkdocs site

To host my newly made site, I used readthedocs.org. 
readthedocs (or RTD) is nice because they will host your documentation for free and great for open source projects as well as building multiple versions of your website.

To do this, you will need a GitHub account that houses all of your documentation you used to create the mkdocs site.

Once you create an account on readthedocs you want to go to the drop-down menu next to your username and click on "My Projects"

readthedocs gives you the option to Import a Project from GitHub

readthedocs also gives you the option to import manually as well.


## To import a project from Github

To import a project from github, you click on the Import a project from the My Projects Page.

On the following page, fill in the Name, repository url related to the project you want to host on read the docs.

Click Build Version. 

And Voila you have a website.