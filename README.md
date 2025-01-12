# C.A.N. (Compact Astronomy Node)  
*A DIY radio telescope built using a paint can and an RTL-SDR dongle.*  

## About  
## About  
The Compact Astronomy Node (C.A.N.) project aims to make radio astronomy more accessible with low-cost, open-source radio telescopes. Inspired by **PICTOR: A free-to-use Radio Telescope**, the C.A.N. telescope is built from a 5L metal paint can, acting as a cylindrical waveguide. It uses a $30 RTL-SDR v4 with a 2.5 MHz bandwidth for signal processing.

While larger radio telescopes like the [Dwingeloo Radio Telescope (DRT)](https://www.camras.nl/) use larger dishes, better LNAs, and higher-bandwidth SDRs, C.A.N. focuses on providing an affordable, compact alternative for radio astronomy. 

Check out the **PICTOR GitHub repository** [here](https://github.com/0xCoto/PICTOR) and the **PICTOR website** [here](https://www.pictor).

## Example Experiment  
Measure the **21 cm Neutral Hydrogen line** at **1420 MHz (L-Band)** to perform basic Hydrogen mapping of the Milky Way IE how many arms it has. 

## Materials  
Refer to the [Materials List](materials_list.md) for all components required to build the C.A.N. telescope.  

### TODO List:
<details>
  <summary><strong>Tasks:</strong></summary>

  ### Completed:
 
  ### In Progress:
  - [ ] Aquire Materials

  ### To Do:
  - [ ] Write GNU code for the SDR to record data
	-[ ] simple FFT, and save into a file
        - [ ] add flow chart into `README.md`
  - [ ] Assemble Paint Can
	- [ ] basic testing
  - [ ] Add instructions for assembly into the materials list
  - [ ] Write a simple analysis script
  - [ ] Write an observation script that uses the GNU Radio to record an observation
  - [ ] Write an observation scheduler script to automaticaly run the observation script
  - [ ] Write a script, and notebook to determine when the plane of the Milky-Way is in the field of view
  - [ ] Write a script for continious drift scan observations for Hydrogen Intensity Mapping
	- Gets a pretty plot
  - [ ] Combine scripts + a RaspberryPi into telescope backend
  - [ ] Write a script for Pulsar folding, and stacking
	- with 2.5 Mhz of bandwidth this is Hard, and size of telescope
	- Try stacking Pulses 
  - [ ] Find location for permenant set up
  - [ ] Write a `theory_of_operation.md`
  - [ ] Expand `README.md` to be more engaging
  - [ ] Make Website for telescope, have abililty to (easily) schedule an observation 
  - [ ] Make Youtube science content, and `jupyter-notebook` walkthroughs
	- Include theory of operation at varius levels
	- Simple Galactic Arm analyis + Dopler shift 
  - [ ] Test sensitivity in freqency band for weather satelites
  - [ ] Make docker image? of analysis backend for easier reproduceabililty 
</details>



## License

[GPL-3.0](https://github.com/afinemax/C.A.N.-Compact-Astronomy-Node/blob/main/LICENSE)

## Contributing  
Contributions are welcome! Please feel free to fork the repository and submit a pull request. See the TODO list for tasks.  

