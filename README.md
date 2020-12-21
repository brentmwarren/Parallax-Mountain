# Parallax Mountain

Parallax Mountain is an experiment using 7 different layers to exagerate the parallax effect.

## Usage

All that's needed is to pull down the project and open it via local host in the browser.
Scroll up and down the page to see the effect produced

## Crediting and Sources

This project was inspired by a Codepen [Firewatch Parallax CSS](https://codepen.io/samdbeckham/pen/OPXPNp) The
[Original Photo](https://www.pexels.com/photo/silhouette-of-mountains-1323550/) was take by Simon Matzinger from Pexels

## Development

After reviewing the original code from the codepen, I was unable to mimic the functionality.
This was due to the codepen using SASS by importing "compass/css3". The library seems to have a few issues so I chose to translate the SASS into vanilla CSS

Afterwards, I decided to use a different image - [Layered Mountain Photo](https://www.pexels.com/photo/silhouette-of-mountains-1323550/) In order to have the different images, I used photoshop's quick selection tool to automatically grab specific edges of a layer, delete the rest of the image, and turn the blank space into a vector. I repeated this process on each layer.

After adding the images to my project I realized I had two issues from the original code. 1) something was blocking the image responsiveness with different window sizes 2) The quick selection tool produced a "halo" on the edges of my layers.

I was able to change some of the .parallax css properties to fix the scaling issues and as a temporary workaround I slight moved all layers "up" a few pixels to partially cover the halo.

## Contributing

Any and all feedback is welcome as I would love to solve the halo issue and come up with a solution for a cleaning scroll
