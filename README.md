# Quaternions
This is a note for what quaternions represent. 

Get the rotation in axis-angle representation: 
Rotate $\theta$ with respect to $x\hat{i}+y\hat{j}+z\hat{k}$ vector. 
Simple quaternion conversion for that rotation would be :

Take the unit vector of this axis: 
$M = \sqrt{(x^2+y^2+z^2)}$ - is the magnitude of this vector. 

Quaternion would be:
$w_q = \cos(\frac{\theta}{2})$
$x_q = \frac{x\sin(\frac{\theta}{2})}{M}$
$y_q = \frac{x\sin(\frac{\theta}{2})}{M}$
$z_q = \frac{x\sin(\frac{\theta}{2})}{M}$


