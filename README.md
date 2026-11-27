# MCTA 4364 Machine Vision — RoboVision Challenge (DataHack 3.0)

**Track:** Track 1 (Kaggle Competition)  
**Competition Link:** https://www.kaggle.com/competitions/robovision-challenge-datahack-3-0

## Group Members
| Name | Matric No. |
| :--- | :--- |
| Siti Heidi Amira Binti Azrul | 2111970 |
| Athirah Haziqah Binti Baderulhisham | 2210240 |
| Izzah Zahira Binti Norazlee | 2217696 |

## Project Overview
This repository contains the data exploration, stratified validation split, and baseline regression pipeline for predicting 24-dimensional continuous robot action vectors (`action_0` to `action_5`, 4 values each) from `640x480` RGB images and camera metadata.

## Environment Setup
1. Create and activate a Python 3.11 environment (`mv`):
   ```bash
   conda create -n mv python=3.11 -y
   conda activate mv