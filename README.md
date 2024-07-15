# Cambridge-SHeM-Pinhole-Plate-Design-and-Analysis

A Python analysis script that parameterizes the pinhole plate geometry and analyses the performance of any new design.

Created by **Ke Wang**, **Sam Lambrick**.

This is a figure demonstrating the parameterization of the pinhole plate geometry.

![Pinhole_Scheme](https://github.com/user-attachments/assets/abcc9f5e-898d-49f5-aa07-7d5b6fdba1e3)

where $a$ is the full length of the axis of the detector aperture, $b$ is the separation between the center of the pinhole aperture and the detector aperture, $Z$ is the perpendicular distance between the sample and the pinhole aperture, $H_p$ is the height of the pinhole aperture above the plate, $H_d$ is the height of the detector aperture above the plate, $\alpha$ is the incidence angle of the helium beam, $\beta$ is the tilt angle of the detector aperture, $\theta$ is the detection angle of the detector aperture when the sample is located at a certain $Z$ position, and $\phi$ is the in-plane angular acceptance of the detector aperture w.r.t the sample at a certain $Z$ position.

$a,b,H_p,H_d,\alpha,\beta$ will be fixed for any pinhole plate design in Cambridge currently. After setting these parameters following the example in the Jupyter notebook, one has basically create a new pinhole plate design. The next step is inputting a range of $Z$, and the code will produce the in-plane angular acceptance, out-plane angular acceptance, and solid angle of the detector aperture against $Z$, $\theta$, and $\Delta K$, which are also demonstrated using the current A-SHeM and B-SHeM pinhole plate as examples in the notebook.
