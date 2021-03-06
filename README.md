# grubClub
Please cite the information in this repository using the following DOI:  
[![DOI](https://zenodo.org/badge/422724743.svg)](https://zenodo.org/badge/latestdoi/422724743)

I would like to present grubClub (“grub” for larva, and “club” for… well, you will see). I built off of the ethoscope (https://github.com/gilestrolab/ethoscope) by https://github.com/qgeissmann to enable automated long-term optogenetic stimulation of Drosophila larvae. Here is my Halloween-style release: https://twitter.com/NeuroLuebbert/status/1454220954666631170?s=20

GrubClub consists of a printed circuit board (PCB) and an accompanying arena. Both fit into the ethoscope published here: https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2003026.

The PCB holds 4 transistors, each connecting to 2 LEDs. Each row of LEDs can be controlled independently through Raspberry Pi GPIOs. In the picture below, each LED has a 270 ohm resistor. The power of the LEDs can be increased (or decreased) by modifying this resistance (within the circuit limits). 

The grubClub arena slides into the ethoscope and holds larvae in small round wells that can be filled with sugar-containing agar (or any larva medium). Each square fits a standard 22x22 mm coverslip as a lid. I 3D-printed my arena using translucent PLA to increase light intensity.

Since I am currently not recording larval behavior, I did not include an IR backlight for camera recordings. However, the PCB is designed such that an IR light strip can easily fit between the LED rows, enabling optogenetic stimulation and behavior recording at the same time. Finally, while red LEDs (~630 nm) might prevent a startle response, for my experimental design, I decided to stimulate at the spectral peak of my channelrhodopsin Chrimson (590 nm). The PCB supports LEDs of any color, and I included both options in the component list.

<p float="left">
  <img src="https://user-images.githubusercontent.com/56094636/139510059-25e6ec9f-84fa-4ee8-97d2-7e0da204128f.png" height="400" />
  <img src="https://user-images.githubusercontent.com/56094636/139510102-7b6ecafc-c936-4aca-ac13-6bff3775d972.png" height="400" /> 
</p>

<p float="left">
  <img src="https://user-images.githubusercontent.com/56094636/139601269-a0dc5495-feea-4ab1-a13c-37a58c444b2e.png" height="440" />
  <img src="https://user-images.githubusercontent.com/56094636/139601339-4830faa3-0bd4-4fae-b7d3-acbf85b5512b.png" height="440" /> 
</p>

[grubClub PCB](https://user-images.githubusercontent.com/56094636/139601286-2ef72724-cccf-4f6b-9c9d-bd818d46505a.mp4)
