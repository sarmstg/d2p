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

## Potential project focus?
* Can the trial outcome (hit vs miss) be predicted from activty preceeding stimulation? This would involve analysing if there is a difference in the first 5 frames [0,1,2,3,4] of hit and miss trials.
#### How can you tell if there is a difference in neural activity?
* The first pass analysis would be to take a mean across the first 5 frames, so you have a matrix of shape [n_cells x n_trials]. This matrix can be passed to several differnet methods of classification e.g. a Support Vector Machine or a logitic regression (you will need to split your data into test and training). If this doesn't work, we can come up with an alternative to averaging across frames. 


## Useful links
#### The two presentations shown at the start
* https://docs.google.com/presentation/d/1FhbRND5hbArppZ0r7mmPciL3ZQ0w4Qsm4On-TY_aKFM/edit?usp=sharing
* https://docs.google.com/presentation/d/11A9RlTV3TscO1kQBNb2sUs-e9Wg3A9OH3NSXCBOlfLM/edit?usp=sharing
#### Analysis tools
* https://www.datacamp.com/community/tutorials/support-vector-machines-r
* https://www.datacamp.com/community/tutorials/logistic-regression-R








