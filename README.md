
<p align="left">
<a href="#logo" name="logo"><img src="https://raw.githubusercontent.com/bionanoimaging/UC2-GIT/master/IMAGES/UC2_logo_text.png" width="400"></a>
</p>


# openUC2 Workshop
---

*Last updated: 2022-05-05 (BD)*

This repository will give you an extended tour through the UC2 ecosystem. We will start with its core concept why it is awesome to think in cubes.

# Outline

* **GENERAL** Introduction into UC2 (30 min, [==> UC2 General Repo](https://github.com/openUC2/UC2-GIT))
* **RESOURCES**: Repos and Structure (10 min, [==> UC2 Cheatsheet](./UC2_01_GENERAL.md))
* Hands on experience:
  * Set up an Inline Holographic (i.e. lensless) Microscope
* CAD design for creating an insert using Thingiverse/Autodesk Inventor (60 min)
* **SOFTWARE**: Introduction into ImSwitch
* Reconstruct holograms with ImSwitch in realtime using the Holo Plugin (30-45 Minutes)
  * Install the software/start the SOFTWARE
  * get familiar with ImSwitch
  * *HINT:* Find a sparse samples e.g. plankton on coverslip would be best, or just dust/sand/cheeck cells
* **ELECTRONICS**: Introduction into UC2-REST  
  * Introduction into the ESP32 and Arduino IDE
  * Flash the code and test the LED array + motor
* **OPTICS**:
  * Build the “incubator microscope”/finite corrected microscope by adding the Z-stage
  * Swap the camera by a second mirror + eyepiece and use the cellphone as the camera



(30 Minutes, People in Woods hall, get to know cubes; Things to do in advance: Add LEDs to the insert /w sticky tape; add aluminium foil, find samples on glass coveslip)


, need to install the ImSwitch, Drivers Pacakge, all here https://www.dropbox.com/sh/pea63wifrq3edsl/AAChzXEGA55uUt2Kjxxfk_Dka?dl=0 on students/Woodshall laptops, 30-45 minutes)
Intro into UC2 electronics and ESP32 microcontrollers, LED array and Stepper-related stuff (Bene, 30-45minutes)

Connecting LED array to ImSwitch and make it work (Woodshall People, connect LED Array 3 wires to ESP32, we should have some on site and some will come over too); we should have 5 setups that will be working (ESP32 wemos d1 + cnc shield - pretty much plug and play 1x Ps4 controller; worst case: We flash everything from one computer


  (not yet assembled, but I will add pictures Z-stage https://github.com/openUC2/UC2-Zstage#hardware---motor-driven-z-stage-diy-captive-nema11) and the LED array



  I think this is the end and if people want to do more, they can swap the Thorlabs camera with the Eyepiece + Cellphone bit.
  What do you think? I can definitely write a more precise protocol to have it better documented - perhaps even record the steps in advance..
  The tricky bits right now are:
  Assembly of Z-stage
  Wiring (LED Matrix)
  Installation of Software on machines in Woodshall.


### DAY 1

[Experiment 0 - Get Familiar](./Experiment_0.md)

[Experiment 1 - Telescope](./Experiment_1.md)

[Experiment 2 - Fourier-Filtering](./Experiment_2.md)

[Experiment 3 - Incubator Microscope](./Experiment_3.md)


### DAY 2

[Experiment 4 - Light Sheet](./Experiment_4.md)

[Experiment 5 - Examine the Time-Lapse Series](./Experiment_5.md)

[Experiment 6 - Intro to Image Processing with ImJoy](./Experiment_6.md)

[Experiment 7 - Smartphone Microscopy](./Experiment_7.md)



## Get Involved

This project is open so that anyone can get involved. You don't even have to learn CAD designing or programming. Find ways you can contribute in  [CONTRIBUTING](https://github.com/openUC2/UC2-GIT/blob/master/CONTRIBUTING.md)


## License and Collaboration

This project is open-source and is released under the CERN open hardware license. Our aim is to make the kits commercially available.
We encourage everyone who is using our Toolbox to share their results and ideas, so that the Toolbox keeps improving. It should serve as a easy-to-use and easy-to-access general purpose building block solution for the area of STEAM education. All the design files are generally for free, but we would like to hear from you how is it going.

You're free to fork the project and enhance it. If you have any suggestions to improve it or add any additional functions make a pull-request or file an issue.

Please find the type of licenses [here](https://github.com/openUC2/UC2-GIT/blob/master/License.md)

REMARK: All files have been designed using Autodesk Inventor 2019 (EDUCATION)


## Collaborating
If you find this project useful, please like this repository, follow us on Twitter and cite the webpage! :-)
