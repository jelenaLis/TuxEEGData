# Tux EEG Data

Experiment from paper 
Mladenovic et al., Towards Identifying Optimal Biased Feedback for Various User States and Traits in Motor Imagery BCI, 
IEEE Trans Biomed Eng. 2022 Mar;69(3):1101-1110.
doi: 10.1109/TBME.2021.3113854. Epub 2022 Feb 18.

In this experiment subjects played a modified BCI game called, Tux Racer, and controlled a penguin to catch fish on left or right with left-right hand motor imagery, respectively.

There are 3 groups of subjects who received either non altered feedback, or altered feedback (positively biased or negatively biased): 
files named with suffix "noadapt", "adapt_positif" and "adapt_negatif".

Instruction video to subjects given https://www.youtube.com/watch?v=X-u9tdjZL6I
(in French as the experiment was conducted in France).

During the machine calibration of 2 runs per 5mins (eeg data with suffix "_acquisition"), subjects received fake feedback (files with suffix "_fake") where they perceived the penguin to move randomly from left to right position of the ski course. They were told about the random feedback in the instruction video and repeated by the experimenter.

Files with suffix "_EEG" contain raw eeg data recorded from openvibe; 
6 runs from testing last 6mins each, a trial (during which a subject imagines one hand motor imagery) lasts around 7s, and there are around 40 trials per run (for both classes).

There are 2 sessions per subject, namely, subject 1 for session 1 and 1_2 for session 2.

NOTE:
Subjet 19 session 2
Electrode 20 removed from run 2 (included) until the end, config files and output suffixed with "fix".

Subjet 3 session 2
Electrode 3 removed from run 3 (included) until the end, config files and output suffixed with "fix".




## Data

Pending submission to open-access platform, stay tuned. 
