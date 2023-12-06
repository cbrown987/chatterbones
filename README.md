# chatterbones
### A skeleton that can talk

#### This is a themed chatbot built by Cooper Brown, Jack Welsh, and Riley Rongere.

## Overview

This is a themed chatbot built to utilize a rasberrypi and an AWS server to take inputs fron
a speaker, generate a response, then speak said response. The model was built using a dataset with 
movie lines to give the chatbot more of a spooky theme. 

## The RaspberryPi and Inputs

The raspberry pi had speech to text software that would take an input, use speech processing software
then send the text to the AWS server

## AWS 

To be written by jack IDK man

## Model

The model was a base pytorch model based off of the work of [Matthew Inkawhich](https://pytorch.org/tutorials/beginner/chatbot_tutorial.html)
Whos chatbot used the same model and the same dataset and our model was largely based on. 
The majority of the work put into the model was adapting and making the model work off of the generated .tar
files that were created. 

### Workloads:
Cooper Brown - model creation, model adaption, bash and python scripting

Jack Welsh - AWS wizard

Riley Rongere - RaspberryPi inputs, model fine-tuning, and python scripting

