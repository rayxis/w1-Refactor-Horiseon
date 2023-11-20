# Code Refactor Starter Code for Horiseon

## Description
The code for the Horiseon marketing agency's website has been refactored to provide not only a clean, easy-to-follow HTML structure, but also an organized CSS file to make any additional changes to the layout of the website as easy to navigate and edit as possible.

The most notable changes were:
* Converting `div` tags to `header`, `main`, `section`, `article`, `aside`, and `footer`.
* Consolidating the tags that were similar, organizing the tags by grouping, and spacing the parameters in an easy to read format.
* Additional commenting was added to both for the purposes of separation, but most things in there are self-explanatory.
* Fixed a couple of errors in the HTML code that were broken.

Original code for the website (preoptimization) can be found here: https://github.com/coding-boot-camp/urban-octo-telegram.

## Installation
You can extract the files in web site's root directory (for example, /var/www/html).

Note: Unless both your web host and user have a fast enough connection, they may notice a performance issue with the size of the images being served. If you notice this is the case, you can reduce the quality of the images to reduce the amount if time that it takes to load. As of right now it's ~50MB. This shouldn't be an issue on faster machines.

## Usage

I have included two different versions, one is a consolidated version of the original code. The second version is a (mostly) BEM-style version, which appears to be a little easier to follow; this is the way that I would have done it if this was my website. The reason I prefer it is because it creates more useable code that is easy to work with if you want to move your blocks around and reorganize, but not break the site.

A live version of the finished site can be found here: https://rayxis.github.io/w1-Refactor-Horiseon/index.html.


A second version in a mostly BEM-style: https://rayxis.github.io/w1-Refactor-Horiseon/index2.html.

Both pages display as follows:

![Screenshot of completed website](./assets/images/screenshot.png)

## User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria
GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and 
positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
