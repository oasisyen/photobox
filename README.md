photobox
========

A lightweight CSS3 image gallery that is pretty to look and and easy to use.

## BETA 1.5
Please switch to branch "1.5" and try out the new beta. I've re-wrote a LOT of the code, fixing bugs and adding support for autoplay.

## Basic use-case example:
    <div id='gallery'>
        <a href="http://www.somedomain.com/images/image1_large.jpg">
    		<img src="http://www.somedomain.com/images/image1_small.jpg" alt="photo1 title">
    	</a>
    	<a href="http://www.somedomain.com/images/image2_large.jpg">
    		<img src="http://www.somedomain.com/images/image2_small.jpg" alt="photo2 title">
    	</a>
    	<a href="http://www.somedomain.com/images/image3_large.jpg">
    		<img src="http://www.somedomain.com/images/image3_small.jpg" alt="photo3 title">
    	</a>
    	<a href="http://www.somedomain.com/images/image4_large.jpg">
    		<img src="http://www.somedomain.com/images/image4_small.jpg" alt="photo4 title">
    	</a>
    </div>
    ...
    ...
    ...
    <script>
    	$('#gallery').photobox('a',{ time:0 });
    </script>

## settings
**time** (default: 3000) minimum 1000ms allowed

    The time in miliseconds when autoplaying a gallery. Set to '0' to hide the autoplay button

**autoplay** (default: false)

    should the gallery autoplay on start or not.

**loop** (Default: 'true')

    Loop back to last image before the first one and to the first image after last one.
    
**thumbs** (Default: 'true') 

    Show thumbs of all the images in the gallery at the bottom.
   
**counter** (Default: 'true')

    Show the current image index position relative to the whole. Example (3,11). 
   
**hideFlash** (Default: 'true')

    Hide flash instances when viewing an image in the gallery.

**keys.close** (Default: "27, 88, 67")

    Key codes which close the gallery.

**keys.prev** (Default: "37, 80")

    Key codes which change to the previous image.

**keys.next** (Default: "39, 78")

    Key codes which change to the next image.
