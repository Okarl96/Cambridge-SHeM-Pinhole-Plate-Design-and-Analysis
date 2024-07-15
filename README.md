# Cambridge-SHeM-Pinhole-Plate-Design-and-Analysis

A Python analysis script that parameterizes the pinhole plate geometry and analyses the performance of any new design.

Created by **Ke Wang**, **Sam Lambrick**.

This is a figure demonstrating the parameterization of the pinhole plate geometry.

![Pinhole_Scheme](https://github.com/user-attachments/assets/abcc9f5e-898d-49f5-aa07-7d5b6fdba1e3)

where $a$ is the full length of the axis of the detector aperture, $b$ is the separation between the center of the pinhole aperture and the detector aperture, $Z$ is the perpendicular distance between the sample and the pinhole aperture, $H_p$ is the height of the pinhole aperture above the plate, $H_d$ is the height of the detector aperture above the plate, $\alpha$ is the incidence angle of the helium beam, $\beta$ is the tilt angle of the detector aperture, $\theta$ is the detection angle of the detector aperture when the sample is located at a certain $Z$ position, and $\phi$ is the in-plane angular acceptance of the detector aperture w.r.t the sample at a certain $Z$ position.

$a,b,H_p,H_d,\alpha,\beta$ will be fixed for any pinhole plate design in Cambridge currently. After setting these parameters following the example in the Jupyter Notebook, one has basically created a new pinhole plate design. 

![Pinhole Plate Designs Examples](https://github.com/user-attachments/assets/fe3645fc-271d-4156-8f15-775072622648)

The next step is inputting a range of $Z$, and the code will produce the in-plane angular acceptance, out-plane angular acceptance, and solid angle of the detector aperture against $Z$, $\theta$, and $\Delta K$, which are also demonstrated using the current A-SHeM and B-SHeM pinhole plate as examples in the Notebook.

![in-plane example](https://github.com/user-attachments/assets/9e5bfd27-82d0-4198-ac71-d2075ae8ec55)
![out-plane example](https://github.com/user-attachments/assets/93cd95c4-fbaa-4b39-b21f-99bb5e3a57cd)
![solid angle example](https://github.com/user-attachments/assets/b675001f-9f67-46e2-89ba-77febef5e6e5)

There is an add-on feature in the Notebook that adds diffraction conditions to the plot.

![Diffraction Conditions example](https://github.com/user-attachments/assets/3c72619c-a196-4d5c-b403-e5348d3d6c2b)

The width of each diffraction channel is determined by the in-plane angular acceptance at its location.

![Diffraction Conditions Ashem example](https://github.com/user-attachments/assets/e21a546c-c3c8-4fbe-afb8-60497b4694a8)

For a more detailed analysis and simulation of the diffraction measurement, please go https://github.com/Okarl96/Scanning-Helium-Microscope-Diffraction-Measuement-Simulation

(●'◡'●)
