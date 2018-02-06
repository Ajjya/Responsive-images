# Responsive-images
> Js library for responsive images

## Getting started

### Quick start
* [Download the latest release](https://github.com/Ajjya/Responsive-images/archive/master.zip)
* Clone the repository: git clone [Clone](https://github.com/Ajjya/Responsive-images.git)
* Install: bower install Responsive-images

### Installation
Include files:
	Before your closing <body> tag add:
	```html
	<script type="text/javascript" src="path-to-library/responsiveImages.js"></script>
	```
### Usage
Add attribute data-img-sizes to every image or tag with background image which needs to be responsive (Change size according to window width). The biggest image have to be without size, all others paths have sizes (image width).
Sizes are separated with comma, image path and size are separated with space
	```html
	<div class="main_pic bg" data-img-sizes="biggest-image.png, big-image.png 1300, small-image.png 1000, smallest-image 768" ></div>
	```
