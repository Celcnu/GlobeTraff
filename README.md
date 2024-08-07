# What is GlobeTraff
GlobeTraff is a traffic workload generator for the creation of synthetic traffic mixes. It was proposed by Konstantinos V. Katsaros et al. of Athens University of Economics and Business in 2012. Readers can refer to their published paper for more details.

> [GlobeTraff: A Traffic Workload Generator for the Performance Evaluation of Future Internet Architectures](https://ieeexplore.ieee.org/document/6208742)


# How to install GlobeTraff

**1. Run the "setup" script in the project root directory**

`./setup`

Or you can execute the commands one by one, according to the content of the "setup" script. This can help you quickly locate the error.

**2. Import "JavaGUI" project into your NetBeans**

Directly build & run the project. If no errors are thrown, you should see the following GUI.

![](JavaGUI/src/globetraff/resources/globetraff-gui.png)


# How to use GlobeTraff

Simply djust the knob to set the parameter to the value you want, then you click the "Generate" button. After that, you will see the workload file in JavaGUI/data.

# Bugfix
A.  "Permission denied" error
- ./freq: 1: ../freqsize: Permission denied
- ./numWebRequests: 1: ../lc.pl: Permission denied
- ...
- Add execution permissions to the corresponding files, for example, "chmod +x ../lc.pl" under path JavaGUI/



