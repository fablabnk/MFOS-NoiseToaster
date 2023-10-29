# MFOS Noise Toaster


> ##### Forked from *[Sam Zeter](https://github.com/samzeter/noise-toaster)*

## Status

Work in progress -> Revision 0.6.1

## Motivation

My first project to get back to electronics and learn something new along the way.
This repository is for the documentation of my journey to a fully functional analog synthesizer and may help other people to build one too.

This is my first electronics project for a long time and I decided to build the __Music From Outher Space -__ __*Noise Toaster*__,  because of the great documentation and the book 'Make: Analog Synthesizers' by Ray Wilson.

## How to use this repository

This repository contains all files for building the Noise Toaster and the PCB of the synth.
If you want to make your own PCB, only compress all the files in the 'Noise Toaster PCB/Gerber Files' directory to a .zip file and upload it the PCB manufacturer of your trust.

## Project Structure
.  
│  
└── MFOS-NoiseToaster/  
&ensp;&ensp;&ensp;&ensp;│  
&ensp;&ensp;&ensp;&ensp;├── 'front panel'/   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;├── classic/  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'front panel template - classic.svg'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'inverted front panel template - classic.svg'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── alternative/  
&ensp;&ensp;&ensp;&ensp;├── 'Noise Toaster PCB'/   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'Gerber Files'/  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── *.gbr   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'Noise Toaster PCB.kicad_pcb'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'Noise Toaster PCB.kicad_pro'   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'Noise Toaster PCB.kicad_sch'   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'aa.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;&ensp;Audo Amplifier    
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'areg.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;Attack Release Envelope Generator    
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'lfo.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;&ensp;Low Frequency Oscillator   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'ps.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;&ensp;Power Supply    
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'vca.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;Voltage Controlled Amplifier  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'vclpf.kicad_sch'&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;Voltage Controlled Low Pass Filter  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'vco.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;VCO - CV Mixer and Expo Converter  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'vco_rswg.kicad_sch'&ensp;=>&ensp;VCO - Ramp/Square Wave Generator   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'wng.kicad_sch'&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;White Noise Generator  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'fp.kicad_sch'&ensp;&ensp;&ensp;&ensp;&ensp;=>&ensp;&ensp;&ensp;&ensp;Front Panel  
&ensp;&ensp;&ensp;&ensp;├── 'Bill of Material'/   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'BoM checklist.md'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'interactive BoM.html'    
&ensp;&ensp;&ensp;&ensp;├── README.md  
&ensp;&ensp;&ensp;&ensp;└── TODO.md  

## Usefull links and resources

* [Musik From Outer Space](http://musicfromouterspace.com/)
* [MFOS - Noise Toaster - Dokumentation](http://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&PROJARG=NOISETOASTER/NOISETOASTER.php&VPW=1493&VPH=725)
* [Ray Wilson - YouTube Channel](https://www.youtube.com/@Musicfromouterspace)
* [MFOS Noise Toaster Presentation - Video by Ray Wilson](https://www.youtube.com/watch?v=smFKx6gfOd0)
* [Noise Toaster in action - Video by Ray Wilson](https://www.youtube.com/watch?v=qHlyuIe3wuU)
* [Make: Analog Synthesizers by Ray Wilson](https://learning.oreilly.com/library/view/make-analog-synthesizers/9781449356200/)

---
![CC-BY-NC-SA](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

