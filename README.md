# cpnt260-a2

1. cpnt260
2. Team Card Assignment
   Author name; Kevin Taguchi
3. Attributions;
- CSS-trick
- MDN Web Docs
- W3school
4. Problem and possible solutions / Not from my own code.

 I had hard time to put profile picture above background image and give white border line around the image.
 
 ### Solution: 
 Select profile image give position relative and use margin to place image to right spot.

 e.g.
  + position: relative;
  + margin-top: 5rem;
  + margin-left: auto;
  + margin-right: auto;
  
  Border properties made image circle and gave white border line.
 e.g.
  - border-radius: 100px;
  - border: 8px solid #f3f4f4;
 
  Positioning background images(banner image) in card container.
  First, add position relative in class container.
  Next, position absolute, height, width in class banner-image; Where you selected the background-image class.
  
  <!-- These code is not my own -->
 e.g.
 - container {
   position: relative;
}
 
- .banner-image {
   position: absolute;
   height: 9.5rem;
   width: 100%;
}

