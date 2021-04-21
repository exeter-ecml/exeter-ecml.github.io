---
layout: paper

title: "Intelligent Process Control – Overcoming the challenge of controlling the processing environment with deep learning"
authors:
- Gregory Daly

venue: International Conference on Data-Driven Plasma Science
year: 2021

link: 

abstract: "
Creating a stable and repeatable processing environment is a long-standing
challenge in the semiconductor industry. Clusters of tools require tuning to
match chambers and produce the same process results and run to run control
strategies are required to correct for process drifts over time. The capability
to perform real-time measurement and control of the state of a processing
plasma could bring significant benefits.


Current approaches have focused on trying to measure specific plasma
parameters, such as electron density, and develop systems to control that
specific parameter[1]. Although these have shown some success they have not
been widely adopted in the industry[2], [3]. In this approach, there is always
difficulty in determining how to use collected sensor inputs and how to
construct a control function for them.


In this work we are presenting our initial progress in using state of the art
deep learning in a unique approach to address this problem. We will demonstrate
how multiple non-invasive plasma diagnostics can be combined in Convolutional
Neural Networks (CNN) to predict the state of the plasma in an industrial
etcher. Our initial focus is on industrially relevant etch plasmas and optical
plasma diagnostics. We will also present some early validation work using
existing plasma probes, that have a good theoretical basis for calculating
plasma parameters.


[1]	B. Keville, Y. Zhang, C. Gaman, A. M. Holohan, S. Daniels, and M. M. Turner, ‘Real-time control of electron density in a capacitively coupled plasma’, J. Vac. Sci. Technol. A, vol. 31, no. 3, p. 031302, Mar. 2013.


[2]	S. Ikuhara, A. Kagoshima, D. Shiraishi, and J. Tanaka, ‘High-accuracy Etching System with Active APC Capability’, 2005.


[3]	S. Umeda, K. Nogi, D. Shiraishi, and A. Kagoshima, ‘Advanced Process Control Using Virtual Metrology to Cope with Etcher Condition Change’, 2018 Int. Symp. Semicond. Manuf. ISSM, pp. 1–4, 2018.
"

who_suggested: Gregory Daly

status: happened
---
- **Note**: This is a talk at ICDDPS rather than a paper.
