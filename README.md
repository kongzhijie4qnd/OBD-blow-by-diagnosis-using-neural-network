# OBD-blow-by-diagnosis-using-neural-network
### using neural network to predict engine OBD status

## 1. Basic blow by diagnosis
using 3 sensors data to predict engine status(binary classification problem)
dataset: 3 Cranck angle based Pressure set in blow by system, engine load, engine speed.
environment: BlowByk.yml 
Import data -> Feature engineering and selection -> scaling -> neural network hyperparameter selection -> training
Since sensor 1 is dedicated to this diagnosis a without sensor 1 method is tested in the end with around 89% accuracy

## 2. lattice
Lattice is used for better interpretation.
environment: BlowBykLat.ynl

## 3. Knowledge Distillation:
A demo.
enviroment: BlowBykDist.yml
