# genai_WS_SNN
Title: Always-On Spiking Neural Network Accelerator for Keyword Spotting with STDP
Introduction:
Our project proposes the development of an energy-efficient hardware accelerator based on Spiking Neural Networks (SNNs) and Spike Timing Dependent Plasticity (STDP) for keyword spotting applications. This accelerator enables always-on or pseudo-on operation, making it well-suited for deployment in low-power edge devices. By leveraging the temporal dynamics of neural spikes, we aim to achieve high accuracy in keyword spotting while minimizing energy consumption.
Objective:
The primary objective of our project is to design and implement an SNN accelerator capable of keyword spotting through STDP-based learning mechanisms. We seek to optimize the hardware architecture to achieve efficient real-time processing while consuming minimal power.
Methodology:
We will begin by designing a compact and efficient SNN architecture tailored for keyword spotting tasks. This architecture will incorporate STDP-based learning mechanisms to adaptively adjust synaptic weights, enabling the recognition of keyword patterns from input data streams. Additionally, we will engineer the hardware accelerator for always-on or pseudo-on operation, employing low-power design techniques to maximize energy efficiency without compromising performance. Furthermore, we will develop a robust keyword spotting algorithm that utilizes the trained SNN model for real-time detection and classification of keywords.
Testing and Validation:
For testing and validation, we will utilize two widely used datasets for keyword spotting and speech recognition:
The (2018) Speech commands dataset version 2, available at http://download.tensorflow.org/data/speech_commands_v0.02.tar.gz.
The (2017) Speech commands dataset version 1, accessible from http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz.
These datasets will allow us to evaluate the accuracy and performance of the developed SNN accelerator across various scenarios and conditions.
