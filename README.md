# Classical-Panoramic-Image-Stitching-using-Homography
This notebook demonstrates how to stitch two or more images to create a panorama from multiple images of the same scene with different angles or shifts.

First we see how 2D transforms can be applied to an image to stretch/squeeze the image.
Then we extend the idea to 3D to see how an image can be warped in all three directions.

And, finally we use this information to find where an image lies in 3D space with respect to another image.
This technique is called Homography, a fast and classical method to stitch images using keypoint detection and 3D geometry.
