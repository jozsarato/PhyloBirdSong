# PhyloBirdSong

This repository contains data and code supporting the manuscript Arato & Fitch (2021): Phylogenetic signal in the vocalizations of
vocal learning and vocal non-learning birds, _Philosophical Transactions of the Royal Society B_


The notebook (Birdsong-auditory feature calculation.ipynb) contains Python code to calculate  9 signal processing features for any audio file:

The provided DataLoader Python notebook loads and visualizes the content of the provided .npy files in the Data folder.

This folder also contains:

boostrapped Phylogenetic trees (.nex format): 
3 files: 
1. all passerine species (All_NonPasserines.nex)
2. all non-passerine species (All_NonPasserines.nex)
3. passerine species with calls (Passerine_Call.nex)

9 acoustic feature values for each species  (.csv format)
3 files:
1. all passerine songs  (All Passerine Song.csv) 
2. all non-passerine songs (All Non-Passerines.csv)  
3. passerine species with calls (Stratified Passerine Call.csv)

