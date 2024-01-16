# Panorama Application  
  
This is a project that can create panoramic pictures! I made this using 
information from my CS 639: Intro to Computer Vision class's lectures.  

Here's a wintry lake panorama where the program was run on 3 images of a winter lake in Northern Minnesota! ![winter lake](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/wintrylake.png) 
 
  
And here's a mountain scene panorama, run on 3 images of a mountain scene! ![mountain](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/mountain_panorama.png)

Here's a picture of my roommates: ![roommates](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/roommates.png)
  
And here's a parking garage panorama, run on 3 images of a parking garage! ![parking garage panorama](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/garagepano.png)

A Minneapolis panorama: ![Minneapolis panorama](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/mpls_pano.jpg)  

And a railroad bridge! ![Rail bridge panorma](https://github.com/ChristopherGottwaldt/Panorama_Application/blob/main/wintrybridgepano.png)

  
## Here's how it works:
- I take 3 pictures that I want to stitch together.
- Run the program using those image filenames.
- The images need to be combined correctly, so keypoints are found using the 
[SIFT Keypoints Algorithm](https://en.wikipedia.org/wiki/Scale-invariant_feature_transform).
- Then, the images are lined up according to the keypoints.
- The left and right images undergo a linear transformation to make the outer 
edge wider, and the inside edge narrower to give an illusion of a curved sides. 
- And *ouila,* it's a panorama!  

## Future Improvements:
 I would like to make the panoramas work for portrait (vertical) pictures, because if you don't take horizontal photos the resulting panorama just doesn't come out right.  
 Currently if one of the sides deviates more from the center than the other, then that side will be made larger.  
 You can see this happening on the above images, usually to the right side of them.
