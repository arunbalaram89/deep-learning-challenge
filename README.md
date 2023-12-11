# Deep Learning and Neural Network Challenge 

# Introduction

This challenge looked at training a Neural Network, along with the 

# Table of Contents
Introduction
Description - Neural Network Report
Installation
Contribution


# Description
This report looks at the model test that was done on this data.  

NEURAL NETWORK REPORT 

Data Preprocessing
The variables removed were the EIN column and the NAME column, as these columns did not have significance to the model. (No unique values). 
Application and Classification (both columns used) and tested three times to determine if we could achieve 75% accuracy. 

The binning process determines the cutoff value. For this testing, we tried many binning factors. First we chose 500, then we reduced it to 150. 
The final time, we chose a higher number of 1000, to see if we would see a result in the data. 

Compiling, Training, and Evaluating the Model

During the EPOCH (training regimen), there were some training regimen that did touch 74.5%, but never 75%. There were methods of initially 100 training regimens, then 50, followed 
by 150 and even 200. By increasing the EPOCH for both the 2nd and 3rd optimization test, we felt that we could achieve 75% accuracy. 

Another method used was to increase the layer_one and layer_two variable gradually to see if an increase in the trainable parameters would make a difference. All 3 optimization models were around 73% accuracy. 

Summary

Even though the model did not achieve 75%, we felt that the model was very consistent, given the changes in the Data Preprocessing and Training and Evaluating of the model. If the model was done again, we would use values for the binning method (lower the cutoff and include more values) plus increasing the trainable parameters, plus an additional layer. Finally, to train the model, increase the EPOCH to 500. These changes may result in the model achieving the desired 75% accuracy. 



# Installation

Google Colab Notebook


# Contribution/Credit

Arun Balaram
DV Tutors - Justin Moore
