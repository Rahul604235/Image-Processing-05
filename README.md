# Image-Processing-05

# Shape from focus

The amount of blur due to optical defocussing depends on the distance between camera and
scene. Hence it is possible to use blur as a cue to determine the depth of a particular point in the
scene.
In this experiment, you are given a set of images which are captured using different camera lens
settings, thus resulting in different degrees of optical blur. Use these images to determine the depth
of each pixel in the image using the shape from focus (SFF) algorithm discussed in class. Display
the 3D structure of the scene using the calculated depth values.
Use sum-modified Laplacian (SML) operator as focus measure and Δd = 50:50. Observe the
output 3D structure for q = 0; 1 and 2, where q is the size of the neighbourhood for the SML
window as defined in class.
