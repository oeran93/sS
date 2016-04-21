# slideShow

JQuery plugin to build slideShows.

###Description
This simple plugin allows to easily set up a div with sliding background images.
***
###Example
####File.js
```
$('#slideShow').sS(
					{
						path: './images/',
						images: [
							'1.jpg',
							'2.jpg',
							'3.jpg',
							'4.jpg'
						]
					}
);
```
####File.html
```
<div id='slideShow'></div>
```
***
###Parameters
All the parameters that can be passed in to the sS function:
* path: the path to the images folder. Must include the last slash (e.g ./images wrong ./images/ right).
* images: an array of all the images part of the slideshow.
* showTime: amount of time to show each slide for.
* bgRepeat: sets background-repeat property of the div
 * no-repeat
 * repeat-y
 * repeat-x



