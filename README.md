# Pclub_ML_task 

Name: Saigourav Sahoo
Roll no: 240906
Email: saigourav24@iitk.ac.in 

In high-energy physics, particles such as quarks and gluons are produced during collisions in particle accelerators like the Large Hadron Collider. These particles often combine into "jets"—streams of particles that detectors observe. Differentiating between quark jets and gluon jets is important for understanding fundamental physics processes, like studying the properties of the Higgs boson or probing physics beyond the Standard Model.
The provided dataset contains simulated particle jets, generated using Pythia 8, a tool widely used to model particle collisions. It includes jets labeled as either quark or gluon jets, based on their origin, and provides detailed information about each jet.
About the Dataset

X: Contains arrays of jets. Each jet has M particles (maximum multiplicity) and their properties:
p_T​: Transverse momentum of the particle.
Rapidity: A measure related to the angle and velocity of the particle.
Azimuthal angle (ϕ): The angle of the particle in the transverse plane.
PDG ID: Identifies the type of particle.

y: Labels for the jets, where:
0: Gluon jet.
1: Quark jet.

goal is to build a classification model that can distinguish between quark and gluon jets based on the provided features. The dataset can be found here:
https://zenodo.org/records/3164691

Beginning with understanding the dataset and doing some exploratory data analysis to figure out which machine learning model would best achieve this goal
Further, two models are proposed:

1. A Random Forest Classifier with an accuracy of 78%
2. A Deep Learning LSTM network with an accuracy of 79%
