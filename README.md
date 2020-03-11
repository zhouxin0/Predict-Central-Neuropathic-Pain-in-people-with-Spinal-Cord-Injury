# Predict-Central-Neuropathic-Pain-in-people-with-Spinal-Cord-Injury
A feature engineering project
# Data
18 participants
    10 participants who developed neuropathic pain within 6 months
    8 participants didn’t develop neuropathic pain within 6 months

Resting state brain Electroencephalogram (EEG) data with eyes closed (EC) and eyes opened (EO)

48 electrodes recording electrical activity of the brain at 250 Hz 

2-class problem
    participant will develop neuropathic pain 
    participant will not develop neuropathic pain within 6 months

preprocessing already applied
    signal denoising and normalization
    temporal segmentation
    frequency band power estimation

180 rows (18 subjects x 10 repetitions) x 432 columns (9 features x 48 electrodes)

# Objective Measure

Leave one subject out cross-validation accuracy, sensitivity and specificity

# Report

Describe feature engineering strategy and give evidence for why your strategy is better than others.

# Reference
University of Glasgow COMPSCI 5090
