

This code is for preprocessing images for removing letter artifacts (background noises) from the images.

We applied a contour based preprocessing where, at first we find all regions in an image and then only keep

the largest region (as we assumed that breast region is the largest region). Finally, we check the direction
of the image and if find the image is L2R direction then we flip to R2L direction as most images R2L directed. 
