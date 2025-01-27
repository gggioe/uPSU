When prototyping or reverse engineering something, it is essential to have multiple positive and negative voltage rails. In many of those cases, 1.5A is enough so, due to the low cost, i decided to use lm317. In the ONsemi LM317 linear regulator datasheet, is mentioned a laboratory power supply application (Figure 22.), however, due to the old design, some components went obsolete. At this point i decided to reverse engineer the simple schematic in order to make it work with newer components, while doing so i also took the opportunity to extend the output to around 30V and add some other features like a tracking pre-regulator and a simple way to put multiple modules in series. Due to the similarity, by changing some component values, higher current alternatives such as lm350 or lm338 can be used. Due to the isolation, if multiples in series are connected the center connection can be used as ground when a negative voltage rail is required. 

### Schematic
![alt text](https://github.com/gggioe/uPSU/blob/main/Simulation/uPSU_sch.png)

### Waveforms
![alt text](https://github.com/gggioe/uPSU/blob/main/Simulation/uPSU_wf.png)
