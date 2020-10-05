# cpnt260-a2

1. ##cpnt260
2. ##Team Card Assignment
3. ##Attributions;
-css-trick
-MDN Web Docs
 
4.## problem and possible solutions
I had hard time to put profile picture above background image and give white border line around the image.
 solutuion: Select profile image give position relative and use margin to place image to right spot.
 e.g.
  -position: relative;
  -margin-top: 5rem;
  -margin-left: auto;
  -margin-right: auto;
  
  Border properties made image circle and gave white border line.
 e.g.
  - border-radius: 100px;
  - border: 8px solid #f3f4f4;
 
  Positioning background images(banner image) in card container.
  First, add position relative in class container.
  Next, position absolute, height, width in class banner-image; Where you selected the background-image class.
 e.g.
 container {
   position: relative;
 }
 
  .banner-img {
    position: absolute;
    height: 9.5rem;
    width: 100%;
 }
