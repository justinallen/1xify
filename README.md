1xify
=====

####Utility for Producing Retina-Ready Graphics

**1xify** helps you produce retina-ready graphics. I wrote this script while producing a bunch of assets for a retina-ready project and needed to eliminate repetitive work.

**1xify** assumes you are designing at 2x: i.e. a logo which will end up displayed at 220 pixels will be designed at 440 pixels, then downscaled into a 1x version. Run `1xify` and it will append @2x to the filenames, put them in a folder, and save versions downscaled by 50% in the root of the directory. 

This is the workflow suggested by Apple in their design guidelines for accomodating retina screens which employ pixel-doubling, as well as tools like Retina.js for making retina-ready websites that spare your non-retina users from an extra-large download.  

**Support:** jpg, jpeg, gif, png

**Dependencies:** ImageMagick needs to be installed on your system as 1xify depends on the `convert` command


