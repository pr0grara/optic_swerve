# OpticSwerve
OpticSwerve is a web application that allows you to upload an image and turn it into "music"!

## Background and Overview

The inspiration for optic swerve came partly from QR codes and partly from a pure curiosity to see what one sense swapped for another would look/sound like. Optic Swerve
allows a user to upload an image, convert the image's pixel data into tones of differing frequencies and then play those tones as a jingle unique to every picture.

## Technology

 ### Javascript
  -Optic Swerve is written entirely in Javascript using the HTML canvas, FileReader, and Tone.js library. Core canvas methods used include drawImage and getImageData. Converting the data gathered into tones is done through my own math algorith and using the Tone.js library. 
  
  -Because a 500px X 500px image contains 250,000 pixels, if OpticSwerve were to convert pixels to tones at a 1:1 ratio, listening to an entire image with 1/16 sec notes would take roughly 4.5 hours and would probably serve as a good interogation technique.
  As a result each tone represents the average data from 5000 pixels, this way we end up with 50 notes to play--a much more reasonable number.
  
## Future Implementation
  -Reverse function where a user uploads audio and has it converted into something drawn on the canvas. Doing this in real-time and with a user adjustable algorithm opens up the use case of OpticSwerve to live performers.

## Walkthrough
![Image of Site](https://github.com/pr0grara/optic_swerve/blob/master/images/optic_swerve.png)
 1. User uploads an image through File Reader.
 2. User clicks "play image".
 
 ## Live Link
 Hosted on GitHub
 http://pr0grara.github.io



