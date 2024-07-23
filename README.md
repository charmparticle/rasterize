#Rasterize

*What is this?*

This is a script designed to act as a RIP - a Raster Image Processor - to convert vector PDF files to raster images, so that they will print correctly.

*What does it do?*

This script takes a PDF as input, and prints it to your default printer. In full, it:
 * optimizes the PDF
 * splits the optmized PDF into individual pages
 * rasterizes each individual page
 * prints the rasterized pages

*Why would I want to use this?*

Sometimes some printers struggle to print vector files correctly. If your PDF is missing text or illustrations, and you use a Linux distro or MacOS, this script is for you.

*How do I use this?*

like so: ./rasterize something.pdf
