# Gianni_et_al_2025
Repository accompanying Gianni et al. (2025)
 - This manuscript is under evaluation in *Sciences Advances*.

## ***Jupyter Notebooks to accompany the paper:***
    
# **Slab underthrusting is the primary control on flat slab size**

### *by G. M. Gianni<sup>1</sup><sup>,</sup><sup>2</sup>, L. C. Gallo<sup>3</sup>, J. Likerman<sup>4</sup>, A. Echaurren<sup>4</sup>, C. R. Gianni<sup>5</sup> C. Faccenna<sup>1</sup><sup>,</sup><sup>5</sup>*


*(1) German Research Centre for Geosciences (GFZ), Potsdam, 14473, Germany.*(2) Institute of Geophysics of the Czech academy of Sciences, Prague, &  1401, Czechia. *(3) Centre for Planetary Habitability, University of Oslo, Norway.*  *(3) Department of Geophysics, Stanford University, Stanford, United States.* *(4) Consejo Nacional de Investigaciones Científicas y Técnicas, Buenos Aires, Argentina.* *(5) Departamento de Ciências da Terra, Universidade de Coimbra, Portugal.* *(6) Institute of Earth Sciences (ISTE), University of Lausanne, Switzerland.*  *(7) Department of Geophysics, University of São Paulo (USP), Brazil.*  *(8) Faculdade de Ciências e Tecnologias, Universidade Federal de Goiás, Brazil.*  *(9) Instituto de Geociências e Ciências Exatas, Departamento de Geologia, Rio Claro (SP), Brazil.*



*(1)  


   
    \
    \small$^{4}$National Scientific and Technical Research Council (CONICET), Capital Federal, \& 1414, Argentina.\and
    \small$^{5}$Dip. Scienze, Università degli Studi Roma Trè, Rome, \& 00154, Italy.\and
   % \small$^{5}$Instituto de Estudios Andinos Don Pablo Groeber, Universidad de Buenos Aires, \& 2160, Argentina.\and
	% Identify at least one corresponding author, with contact email address
	\small$^\ast$Corresponding author. Email: guidogianni22@gmail.com\and
	% Joint contributions can be indicated like this
	\small$^\dagger$These authors contributed equally to this work.
}
Citation: Gallo, L. C., Domeier, M., Antonio, P. Y., Sapienza, F., et al. (2025). Unraveling Remagnetization Sources using Statistical Learning. Earth and planetary Science Letters, 662, 119390. https://doi.org/10.1016/j.epsl.2025.119390

## Overview 

In this project, we introduce a novel approach that integrates geochemical data with rock magnetic measurements. By training a Random Forest regressor on the extracted geochemical features, our method provides accurate predictions of remagnetization. Unlike traditional machine learning methods, which often prioritize predictive accuracy, our statistical learning framework focuses on uncovering the geochemical mechanisms behind remagnetization through feature importance analysis. This approach not only yields robust predictions but also offers valuable insights into the complex processes driving remagnetization.

## Contents

This repository contains all the notebooks and code required to reproduce our analysis. Using a geochemical dataset collected alongside rock magnetic data, we employ a Random Forest regressor trained on the geochemical features to accurately predict the extent of remagnetization.

## Repository Structure
 - Code: Detailed Jupyter notebooks that guide you through the entire analysis workflow—from data preprocessing and feature extraction to model training and evaluation.
 - Data: Documentation and links to the high-resolution geochemical and rock magnetic datasets used in our study.

## How to Reproduce the Analysis

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/LenGallo/Gallo-etal-2025_Statistical-Learning-Remagnetizations

2. **Set Up the Environment:**  
   ```bash
   conda env create -f environment.yml
   conda activate ml_env
3. **Run the Notebooks:**  
Open the Jupyter notebooks in the `ml_env` environment and execute the cells sequentially to reproduce the complete analysis pipeline.
