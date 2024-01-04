# Panorama Application  
  
This is a project that can create panoramic pictures! I made this using 
information from my CS 639: Intro to Computer Vision class's lectures.  

Here's an ![example image](<img url>) where the program
was run on 3 images of a winter lake in Northern Minnesota!  
  
And here's ![another example image](<img url>), run on 3 images of
a mountain scene!  
  
And here's ![another example image](<img url>), run on 3 images of
a parking garage!  

  
Here's how it works:
- I take 3 pictures that I want to stitch together.
- Run the program using those image filenames.
- The images need to be combined correctly, so keypoints are found using the 
[SIFT Keypoints Algorithm](https://en.wikipedia.org/wiki/Scale-invariant_feature_transform).
- Then, the images are lined up according to the keypoints.
- The left and right images undergo a linear transformation to make the outer 
edge wider, and the inside edge narrower to give an illusion of a curved sides. 
- And *ouila,* it's a panorama!  

Link to [presentation site](https://christophergottwaldt.notion.site/Panorama-Application-316065b6e8054c1b943775d67d3b8298).





A panorama application that can stitch 3 or more images together into a combined panorama image.

Find out more on this presentation page!
https://christophergottwaldt.notion.site/Panorama-Application-316065b6e8054c1b943775d67d3b8298
