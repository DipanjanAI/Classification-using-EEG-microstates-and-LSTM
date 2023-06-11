# Classification-using-EEG-microstates-and-LSTM
This project provides tools to study the relation between different microstates and their non linear interaction with each other using LSTM and diffrent dictionary leanning algorithms.

# Abstract-
In our present study, we want to find out the topological maps which vary in terms of extent of correlation between two populations.We propose a linear model for expressing EEG topologies in the form of linear equations.
The EEG data has been reduced along spatial coordinates (electrodes) from 19 features
(19 electrodes) to 2 features. 
In the present study, we demonstrate fitting of a linear model consisting of learned EEG
maps Dictionary learning algorithms were used to learn EEG
maps and corresponding sparse coefficient matrix. In order to find out functionally
connected brain states map which significantly vary between two populations in terms of
their connectivity, we have analyzed the the classification accuracy of K-SVD, K-means
and LASSO based online dictionary learning algorithm using both GFP peaks and single
source GFP peaks and by measuring the corelations using LSTM ntworks The proposed tool is tested with
a dataset containing good and poor task performers.


# Studying functional connectivity in the brain using EEG
Many studies have tried to understand the connectivity among different parts of the brain in order to study the dynamics of the brain. 
Some of these works include the directed coherence-based method which can explain the
connectivity among different parts of the brain in a particular direction. These directional
base connectivity tools have been used in order to understand how different parts of the
brain communicate with each other. Nonlinear correlation measurement methods such as auto mutual
information trophy and Shannon entropy are used to calculate the nonlinear correlation
among different reasons of the brain. One of the methods which have been used in these
connectivity-based papers is granger’s causality method which uses the concept of mutual
entropy to calculate the connectivity between various parts of the brain.This analysis
helps to find functional connectivity across a given time scale. Some of the major tools
which have been used to study connectivity are directed model base tools which include
the direct directed transfer function and full frequency direct transfer function which
captures the connectivity between two different regions of the brain in a specified
direction. Non-directed connectivity methods such as global field synchronization to
study synchronicity among different parts of the human brain during a task. Complexity
measurement tools such as Omega complexity measure the spatial complexity of thebrain
across a time scale, using covariance and using the concept of principal component
analysis. 

# Dictionary Learning
Sparse Dictionary Learning is a representation learning approach that seeks to identify a
sparse representation of the input data in the form of a linear combination of fundamental
elements, as well as those basic elements themselves. A dictionary is made up of these
elements, which are known as atoms. The dictionary atoms do not have to be orthogonal
which is a major advantage as it has been observed that the functional states of the brain
are often not orthogonal to each other, and they can be an over-complete spanning set.
The dimensionality of the signals being represented might be larger than the
dimensionality of the signals.



To understand about EEG microstates and the data that has been used please refer to this research paper-https://www.nature.com/articles/s41598-020-79423-7

All datasets presented in this study are openly available in PhysioNet at https://doi.org/10.13026/C2JQ1P. All epochs that have been preprocessed are available on Figshare at https://doi.org/10.6084/m9.figshare.13135130.

In this project I would like to thank Frederic-vW for provind basic function to extract microstates in the source file https://github.com/Frederic-vW/eeg_microstates . Some of them has been used in this project.
