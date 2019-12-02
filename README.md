# d2p
 Miniproject for Oxford Interdisciplinary Biosciences DTP data management and statistics course. Example data from 2-photon calcium imaging of mouse somatosensory cortex. 


## setup instructions
* Download git bash for windows https://gitforwindows.org/
* make a code directory (e.g. Documents/code)
* use the git bashj to clone the d2p type: 'git clone https://github.com/sarmstg/d2p.git' into git bash
* download anaconda https://www.anaconda.com/distribution/
* run jupyter notebook from anaconda navigator
* Create a new notebook in which you can work

## Tasks to get started 
* Load the .npy data from the repo data folder
* Make some plots of the fluoresence data on different trial types and outcomes, do you want to average at all?
* Is there more neural activity on go and nogo trials? How about hit or miss trials?
(Does this depend on how you average??
* Push your new notebook back to the repo in the jupyter folder

## What is the structure of the data?
* The session1.npy file is a 3d array of shape [n_cells x n_trials x time]
* The trial_info.npy dictionary has values that tell you about the trial (each array should have the length n_trials)

## Useful links
* The two presentations shown at the start
https://docs.google.com/presentation/d/1FhbRND5hbArppZ0r7mmPciL3ZQ0w4Qsm4On-TY_aKFM/edit?usp=sharing
https://docs.google.com/presentation/d/11A9RlTV3TscO1kQBNb2sUs-e9Wg3A9OH3NSXCBOlfLM/edit?usp=sharing








