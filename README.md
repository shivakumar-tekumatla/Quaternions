# Quaternions
This is a note for what quaternions represent. 

Get the rotation in axis-angle representation: 
Rotate $\theta$ with respect to $x\hat{i}+y\hat{j}+z\hat{k}$ vector. 
Simple quaternion conversion for that rotation would be :

$w_q = \cos\alpha$,
$x_q = \frac{x\sin\alpha}{M}$,
$y_q = \frac{y\sin\alpha}{M}$,
$z_q = \frac{z\sin\alpha}{M}$

where $M = \sqrt{(x^2+y^2+z^2)}$ - is the magnitude of the vector , and $\alpha = \frac{\theta}{2}$. 



