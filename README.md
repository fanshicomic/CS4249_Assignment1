The experiment setting:
8 participants, 12 conditions to test. 3 trials per condition and 3 blocks per participants.

What I have modified:
Prepared 8 seperate JSON files for 8 participants, read the participant's id to get the corresponding JSON file.

Similar to total trials and current trial, added total blocks and current block. (experiment.html line 53 - 55, 164 - 181)

After participants have completed one block, disable the next task button and show a continue button.
They can take a break and feel free to continue by clicking the continue button when they like to. Their trial data will also be downloaded after each block is completed. (experiment.html line 121 - 157)

Andd some slight modifications for the above features were done in the ACPToolKit.js file.