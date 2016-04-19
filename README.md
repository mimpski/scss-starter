## SCSS Starter

This is a starting point for projects using SASS and Susy. It's made up of an assets folder containing the work-in-progress SASS folder (containing all .scss files) and the CSS folder where the compiled and compressed CSS will be output.   

SCSS Starter can be placed into any type of project for a quick set up of files and folders.

SCSS Starter requires SASS to be installed but also makes use of COMPASS and Susy. To make the most of these features you will need to install them, if you don't want to use them just comment out or remove the Susy require in the config.rb file and the COMPASS and Susy include in the top level styles.scss file.

## Compiling

Once installed you can run **compass compile** in your Terminal window. This will process the .scss files and output a compiled and compressed styles.css in the assets/css folder.

You can also run **compass watch** for the compiler to watch for any changes that you make and compile as you go.

## Motivation

This project exists to save time when beginning a new project. Creating folders and files each time for a project is inefficient and can lead to inconsistencies between projects making them tricky to maintain. 

Inspiration was taken from https://sass-guidelin.es/ where Hugo Giraudel talks about the 7-1 architecture pattern, this is not an exact copy but a modified version to suit how I write CSS for sites larger than single page.

http://cssguidelin.es/ has also been a great resource while learning to write scalable and maintainable CSS.

## Installation

Clone or download this project and throw the assets folder and config.rb into your project folder.

Run **compass compile** in your Terminal and add the following into your HTML header:

<link rel="stylesheet" href="assets/css/styles.css">

Check the file is being loaded correctly into your project and you're all set.
