This script takes an IMOD model file, and creates an EM mask (values between 0 and 1) as an MRC file. The model points are input as spheres with a user selectable size, and into a box defined by the user.

Typical usage would be:  

make_mask_from_model.py my_dot_model.mod  128  8

where 128 is the number of pixels along the box edge, and 8 is the radius of the sphere being added at the position of the model points. THe spheres are gaussian blurred.
