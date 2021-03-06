
# Arduino Instrumental Modules (AIM) for Behavioral Neuroscientists


##### Note: AIM is informally referred to as DNAMIC (Dartmouth Nautiyal Arduino Modular Instrumental Chamber) in the lab. Therefore I might use the two terms (AIM / DNAMIC) interchangeably to refer to the same thing.

<p align="center">
    <img src="https://media.giphy.com/media/iKFyMgWnooZwu8bYSN/giphy.gif" align=center width=500/><br>
    <b><i>Figure 1:</b> Mouse interacting with the AIM box - Currently retrieving water reward from the middle port.</i>
</p>

<p align="left">
  <img src="readme_imgs/diagonal_view.jpg" align=center width=300/><br>
    <b><i>Figure 2:</b> Diagonal View of AIM</i>
</p>

<p align="left">
  <img src="readme_imgs/side_view.png" align=center width=300/><br>
    <b><i>Figure 3:</b> Side View of AIM</i>
</p>

<p align="left">
  <img src="readme_imgs/top_view.jpg" align=center width=300/><br>
    <b><i>Figure 4:</b> Top View of AIM</i>
    <br>
    <br>
</p>

<p align="center">
  <img src="readme_imgs/boxes_in_action.png" align=center width=400/><br>
</p>

**Figure 5:** *AIM boxes in operation within our lab satellite room. Data is collected automatically by Processing software to a computer in the next room.*
___

### What is AIM?

AIM is a customizable, low-cost operant box to train and test various paradigms in mice. Made with Arduino microprocessor, 3D printed parts, and various *off-the-shelf* components. Enables 24-hour data collection, significantly reducing total experiment duration from months to a couple weeks, thus facilitating controlled studies on adolescent mice and revealing high temporal resolution data on mice behavior.

Most importantly, this is an open-source project - any contributions / suggestions / feedback are welcome and appreciated!

___
### Why should you use AIM?

AIM has a couple of key benefits for any behavioral neuroscience labs trying to study adolescene in rodents.


- **1. Decreased Experiment Time**
    - Because subjects have 24 hour access to a specific paradigm, they learn quickly. Paradigms that typically takes months to train can be completed in just a matter of two weeks.

- **2. Inexpensive compared to traditional Med Associates Boxes.**
    - All the materials used to make one AIM box only cost about **$200**. The software used to run the hardware is also free and open-source. In contrast, a typical Med Associates Box cost around $4000. The software rig that can control up to 8 Med Associates Boxes costs about $6,800.

There are other key benefits to using AIM and you can find a complete list of benefits and advantages in the [Introduction]().
But most importantly, it saves ***YOU*** time and money, allowing you to focus on other important lab tasks and allocate grant money to other experiments.

___
### Overview of Project AIM

The purpose of this repository is to provide **hardware manuals and documentations** for anyone who would like to build their own AIM for use in behavioral neuroscience research. This manual is intended for behavioral neuroscientists without previous experience in engineering or computer science. Therefore the manuals sometimes include explanations on the inner workings of major components used in AIM.

AIM is divided into three different repositories. This repository contains the **hardware** build instructions for AIM. The [second repository](https://github.com/jhl0204/DNAMIC_Arduino_Software_Programs) contains the corresponding **behavioral paradigms** for AIM. The [last repository](https://github.com/jhl0204/DNAMIC_Data_Analysis) contains Python codes for **data analysis** of the behavioral output. Data analysis code is currently in development to create a python package.

The below chapters are rendered via the [Jupyter nbviewer](https://nbviewer.ipython.org/) and is read-only.

#### Contents

* [**Chapter 0 - Background and Introduction**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_0.Background_and_Introduction/0_Background_and_Introduction_vF.ipynb) Why we need Arduino Instrumental Modules (AIM)
* [**Chapter 1 - Getting Started - Essential Tips and Tricks**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_1.Getting_Started-Essential_Tips_and_Tricks/1_Essential_Tips_and%20Tricks_vF.ipynb)
* [**Chapter 2 - Modifying the Rodent Cage**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_2.Modifying_Rodent_Cage/2_Modifying_the_Rodent_Cage_vF.ipynb)
* [**Chapter 3 - OM1 Shield**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_3.OM1_Shield/3_OM1_Shield_vF.ipynb)
* [**Chapter 4 - Component Assembly - LED**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_4.Component_Assembly-LED/4_Component_Assembly_LED_vF.ipynb)
* [**Chapter 5 - Component Assembly - Infrared Detectors**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_5.Component_Assembly-Infrared_Detectors/5_Component_Assembly_IR_vF.ipynb)
* [**Chapter 6 - Component Assembly - Solenoid Valves**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_6.Component_Assembly-Solenoid_Valves/6_Component_Assembly_Solenoid_Valves_vF.ipynb)
* [**Chapter 7 - Component Assembly - Reward Spout**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_7.Component_Assembly-Reward_Spout/7_Component_Assembly_Reward_Spout_vF.ipynb)
* [**Chapter 8 - Wiring and Soldering**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_8.Wiring_and_Soldering/8_Wiring_and_Soldering_vF.ipynb)
* [**Chapter 9 - Final Assembly**](https://nbviewer.ipython.org/github/jhl0204/DNAMIC-Hardware-Documentations/blob/master/Chapter_9.Final_Assembly/9_Final_Assembly_vF.ipynb)

* [**Appendix - Bill of Materials**](https://github.com/jhl0204/AIM-Hardware-Documentations/wiki/Bill-of-Materials)

____
### Other open-source projects in the behavioral neuroscience community

1. [Feeding Experimentation Device (FED) - Kravitz Lab](https://github.com/KravitzLab/FED)
2. [CombiCage - Loos Lab](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5309744/)
3. [ArControl - Li Lab](https://github.com/chenxinfeng4/ArControl)
4. [Openmaze.org](http://openmaze.org/) - open source hardware and software for behavioral neuroscience
5. [Openbehavior.com](http://openbehavior.com/) - repository of open source tools for advancing behavioral neuroscience research]


### Development
_____

##### What to Contribute

- Inaccurate / incorrect information regarding components or explanations
- Typos or grammar mistakes
- Component suggestions
- Your own tips, tricks, and experiences for any hardware projects.

- If you decide to make AIMs yourself, send us photos and any hacks/design modifications that you made! We would love to see how this project expands!


Feel free to open an issue or submit a pull request. All contributions are welcome! - there is no minor contribution. If you're unfamiliar with pull request workflow, feel free to email me with your contributions to jun.ho.lee@dartmouth.edu.


### Contributions and Thanks
_____

A big thanks to **Andrew R. Alvarenga** for his generous support and suggestions regarding hardware. Thank you for also allowing me to use the machine shop and test out different prototypes of the 3D printed parts on the 3D printer.

Thank you to undergraduate researchers **Bonnie Shea** and **Selin Capan** for assisting with daily running of the code.


#### Contact

For any questions or issues, contact the main author, **Jun Ho Lee** at jun.ho.lee@dartmouth.edu or the corresponding author **Katherine Nautiyal** at katherine.nautiyal@dartmouth.edu.
