# Responsive Web Typography Variable Font Workshop (short)
Working files for the full-day version of my workshop on using variable fonts and modern CSS techniques.

## Initial setup
To make use of the `gulp` process, you need to have `npm` and `gulp` installed.

Once both are installed, follow these steps:
Open a terminal window and navigate to the project root
Execute the command `npm install`

## Running the `gulp` process
If the initial setup has been completed, executing the command `gulp` from the root of the project will start the 'watch' task and the local server with BrowserSync.

## Simple Setup (Plain CSS approach)
If you want to skip all the 'build tools' you can just edit the files in the `css` directory instead. Just remember that if you do that and then try the build process later, you will lose any changes you make to `rwt_vf_styles.css` so be sure to make a copy to bring those changes back into the source Sass file (located in `scss/rwt_vf_styles.scss`).

## What you'll find here
This repository contains all the sample pages from my workshop, along with some useful tools and supporting files.

### Supporting Directories:
- CSS - all the compiled CSS for the project. You can edit these directly but you will lose the changes if you then try out the `build` process
- Fonts - some early versions of variable fonts and Plex, and open-source font from IBM
- Images - images used in the project (all taken/created by me)
- Ish - a really useful tool from Brad Frost for previewing any page in a responsive 'viewer' to help test the responsiveness of your work
- JS - just a few script files to help enhance font loading and typography
- SCSS - the source Sass files for the project

### Pages
- index.html - This is an example of a 'finished' page that incorporates all the things covered in the course
- part-04
  - vf-samples.html - a page that has examples of individual axes of variation, triggered on hover
- part-05
  - index-plex.html - a page that uses Plex, and brings in font loading management that you can tailor to improve the loading experience with Plex
- part-06
  - index.html - a copy of a page I wrote and designed about variable fonts, set using FF Meta from Monotype (originally published on CodePen here: https://codepen.io/jpamental/pen/MGEPEL/)
  - index-plex-rwt.html - the next evolution of the page from part-05, adding in responsive web typography features like a modular scale that reacts to viewport width and adds fallback font styles
  - index-vf.html - the page now using variable fonts and the new custom properties/calculation based typographic system
- part-07
  - index-01.html
  - index-02.html
  - index-vf.html
- part-08
  - index-meta.html - the same essay from part-06, but here complete with the CSS
  - example-magazine.html - a fictitious outdoor magazine site page, showcasing variable fonts, fluid typography, and a bit of CSS grid
  
  