# IEEE NetSoft 2020 - Tutorial 4
# A Softwarized Perspective of 5G Networks

This tutorial aims to explore the softwarization in the 5G system composed of the Radio Access Network (RAN) and the core components, following the standards defined by 3GPP, particularly the Release 15. The tutorial provides a brief overview of wireless mobile cellular networks, including basic concepts and the evolution through the called ‘generations’ of mobile networks. From a software perspective, RAN is presented in the context of 4G and 5G networks, which includes the virtualized and disaggregated RAN. A significant part of the tutorial is dedicated to the 5G core, i.e., considering the Service-Based Architecture (SBA), due to its relevance and fully softwarized approach. The tutorial is motivated by a set of experiments. For each experiment, we make available a detailed manual and all the necessary software to replicate it. Some experiments can be reproduced using only a regular computer, e.g., a notebook, but some of them demand specific hardware, e.g., a Software-Defined Radio (SDR).

## Material
* Article
* [Slides](https://drive.google.com/drive/folders/1bhcBX-lZ3fhlUJP2OkF_072KocrmVwnA?usp=sharing "Slides available in the Google Drive")
* Hands-on
  * Demo 1 - In this demonstration, we create an operational eNodeB, i.e., the main element of a RAN, based on LTE technology and open-source software. In addition to RAN, the software is also capable of emulating functional UEs.
    * Experiment 1 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo1-Exp1 "Demo 1 - Experiment 1"), video) - UE and RAN emulated by software without the core.
    * Experiment 2 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo1-Exp2 "Demo 1 - Experiment 2"), video) - UE, RAN, and EPC core, all implemented in software.
    * Experiment 3 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo1-Exp3 "Demo 1 - Experiment 3"), video) - UE in hardware (conventional cell phone), RAN in hardware (SDR) and software, and the EPC core implemented in software.
  * Demo 2 - In this demonstration, we use the 5G core based on the open-source SBA model. In addition to the core, we also present how to emulate RAN and multiple UEs.
    * Experiment 1 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo2-Exp1 "Demo 2 - Experiment 1"), video) - UEs, RAN, and core, all implemented in software.
    * Experiment 2 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo2-Exp2 "Demo 2 - Experiment 2"), video) - UE in hardware (conventional mobile phone), eNodeB in hardware (SDR) and software, and the 5G core implemented in software.
  * Demo 3 - In this demonstration, we combine a RAN based on LTE technology with a LoRa wireless network implemented in hardware. For RAN LTE, we use open-source software and an SDR. We also use an open-source implementation of the SBA-based 5G core software.
    * Experiment 1 ([repository](https://github.com/LABORA-INF-UFG/NetSoft2020-Tutorial4-Demo3-Exp1 "Demo 3 - Experiment 1"), video) - IoT LoRa sensors in hardware, IoT LoRa gateway in hardware and software, RAN in hardware (SDR) and software, and the 5G core implemented in software.
 
## How to cite

```
@article{tutorial4netsoft2020,
}
```
