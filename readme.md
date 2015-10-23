##Multi-channel support vector regression (SVR)
Channel data is combined with an aggregated kernel, computed as:<br><br>
*K(x<sub>i</sub>, x<sub>j</sub>) = Sum<sub>c</sub> [ k<sup>c</sup>(x<sub>i</sub><sup>c</sup>, x<sub>j</sub><sup>c</sup>) / A<sup>c</sup> ]* <br><br>
where *k<sup>c</sup>(x<sub>i</sub><sup>c</sup>, x<sub>j</sub><sup>c</sup>)* is the kernel similarity between observation
*x<sub>i</sub>* and *x<sub>i</sub>* with respect to the *c*-th channel using kernel function *k<sup>c</sup>*, and
*A<sup>c</sup>* is the mean value of similarities for the *c*-th channel.<br><br>
Requires:<br>
numpy<br>
scikit-learn (for the underlying SVR model)<br>

						