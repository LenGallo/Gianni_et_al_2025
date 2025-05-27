 - This manuscript is under evaluation in *Sciences Advances*.

## ***Jupyter Notebooks to accompany the paper:***
    
# **Slab underthrusting is the primary control on flat slab size**

### *by G. M. Gianni<sup>1</sup><sup>,</sup><sup>2</sup>, L. C. Gallo<sup>3</sup>, J. Likerman<sup>4</sup>, A. Echaurren<sup>4</sup>, C. R. Gianni<sup>5</sup>, C. Faccenna<sup>1</sup><sup>,</sup><sup>5</sup>*


*(1) German Research Centre for Geosciences (GFZ), Potsdam, 14473, Germany. *(2) Institute of Geophysics of the Czech academy of Sciences, Prague, &  1401, Czechia. *(3) Centre for Planetary Habitability, University of Oslo, Norway.* *(4) Consejo Nacional de Investigaciones Científicas y Técnicas, Buenos Aires, Argentina.* *(5) Dip. Scienze, Università degli Studi Roma Trè, Rome, 00154, Italy.* 

Citation: G. M. Gianni, L. Gallo, J. Likerman, A. Echaurren, C. Gianni, C. Faccenna. Slab underthrusting is the primary control on flat slab size. Submitted Sciences Advances.

## Overview 

In this project, we present an approach that integrates the calculation of trench and flat-slab hinge kinematics, along with flat-slab size, across both active and extinct flat slab events to assess flat subduction propagation mechanisms (i.e., forward and backward modes). To achieve this, we analyzed well-resolved absolute plate motion models, which were compared with a global subduction geometry model (Slab2.0, along with regional geophysical surveys) and space-time magmatic patterns, providing insights into the extent of both active and ancient flat slabs. 

## Contents

This repository contains all the notebooks and code required to reproduce our statistical analysis. 

## Repository Structure
 - Code: Detailed Jupyter notebooks that guide you through the entire analysis workflow to reproduce figures 4, 5, and supplementary fig. S2.
 - Data: Plate kinematic data are presented using different absolute reference frames, along with estimated flat slab extents for both active and ancient flat subduction. The latter is derived using two different methods (A and B in Fig. 3) to assess potential flat slab extents based on space-time diagrams (see text for details).

## How to Reproduce the Analysis

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/guidogianni/Gianni_et_al_2025

2. **Set Up the Environment:**  
   ```bash
   conda env create -f environment.yml
   conda activate ml_env
3. **Run the Notebooks:**  
Open the Jupyter notebooks in the `ml_env` environment and execute the cells sequentially to reproduce the complete analysis pipeline.
