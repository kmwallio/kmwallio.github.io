---
layout: default
title: Video Transformer - Miles Wallio
---

## [Video Transformer](http://github.com/kmwallio/VideoTransformer)

This is an example projective mapping program written in Perl. It was produced for CSE 4280: Graphics Algorithms. Projective mapping is the process of taking one image and placing it on another. The program takes in two videos, extracts all of the frames, gets mouse input for the corners of where the source video will be projected onto the destination video, and creates the video. For more on projective mapping, feel free to read Paul Hckbert's thesis on [Fundamentals of Texture Mapping and Image Warping](http://www.cs.cmu.edu/~ph/texfund/texfund.pdf). The code is available for viewing and for download on [GitHub](http://github.com/kmwallio/VideoTransformer).

<div class="centered"><img src="/images/vid_shot.jpg" class="yui3-img-bordered"  alt="screenshot"></div>

## About the Program

The program takes in two videos, extracts all of the frames, gets mouse input for the corners of where the source video will be projected onto the destination video, and creates the video.

Currently, the program outputs a video of 15 frames per second 1500k bit rate as an mpeg4. No audio is kept. Later on I hope to make it read the frame rates of the provided videos and output a better quality (if you look at the ./temp/output directory, the frames are much higher quality than the video produced).

### Uses

* mplayer
* ffmpeg
* Perl
	* Gtk2-Perl
	* ImageMagick
	* PDL