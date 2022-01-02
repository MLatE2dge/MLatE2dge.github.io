# Machine Learning @ the Extreme Edge

<div style="text-align: justify">Today, one of the challenges is real-time and energy-efficient information extraction and processing at the edge by using Artificial Intelligence (AI). However, there is a recent trend to implement machine learning (ML) on end-point devices. These end-point devices are located on the extreme edge, the border between the analog (physical world) and the digital world. Such an end-point device consists of one or more sensors and a resource-constrained embedded device, a device with a limited amount of memory, computing power and power consumption. Today's challenge is to the develop accurate, energy-efficient machine learning models that can be deployed on end-point devices.</div>

<br>

![workflow](./img/workflow.png)

<br>

<div style="text-align: justify"> <b>Machine Learning at the Extreme Edge (ML@E2dge)</b> looks at how a developer can apply machine learning in the development of an accurate, energy-efficient, and intelligent wireless battery-powered monitoring system. Starting from a case study, a tiny machine learning model is developed, optimized and deployed. In the project, we limit ourselves to a supervised machine learning regression problem. The end-point device is a Cortex®-M4 ARM® microcontroller (nRF52840, Nordic Semiconductor), in combination with an Inertial Measurement Unit (IMU) sensor (MTi-3, Xsens). In the project open-source software frameworks such as scikit-learn, TensorFlow and Keras are used, in combination with Edge Impulse Studio. For the experiment, metrics and version tracking, MLOps (Machine Learning Operations) frameworks such as ml<i>flow</i> and Weights and Biases are explored.</div>

<br>
