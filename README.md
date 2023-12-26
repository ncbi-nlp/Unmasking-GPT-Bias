# Unmasking and Quantifying Racial Bias of Large Language Models in Medical Report Generation

## Overview
![Figure1](https://github.com/user-attachments/assets/e207b705-80c4-4552-9ae6-4b5863a3fe79)

This is the official repo for the article "Unmasking and Quantifying Racial Bias of Large Language Models in Medical Report Generation". 


Large language models like GPT-3.5-turbo and GPT-4 hold promise for healthcare professionals, but they may inadvertently inherit biases during their training, potentially affecting their utility in medical applications. Despite few attempts in the past, the precise impact and extent of these biases remain uncertain.

We use LLMs to generate responses that predict hospitalization, cost and mortality based on real patient cases. We manually examine the generated responses to identify biases.

We find that these models tend to project higher costs and longer hospitalizations for White populations and exhibit optimistic views in challenging medical scenarios with much higher survival rates. These biases, which mirror real-world healthcare disparities, are evident in the generation of patient backgrounds, the association of specific diseases with certain races, and disparities in treatment recommendations, etc.


## Code 
The python codes to reproduce our work are in scripts. 

## Data availability
The PMC-Patients dataset is available at https://github.com/zhao-zy15/PMC-Patients. PMC-Patients data set can be freely downloaded without any data usage agreement.

## Acknowledgments

This work was supported by the Intramural Research Programs of the National Institutes of Health, National Library of Medicine.

## Disclaimer

This work shows the results of research conducted in the Computational Biology Branch, NCBI/NLM. The information produced on this website is not intended for direct diagnostic use or medical decision-making without review and oversight by a clinical professional. Individuals should not change their health behavior solely on the basis of information produced on this website. NIH does not independently verify the validity or utility of the information produced by this tool. If you have questions about the information produced on this website, please see a health care professional. More information about NCBI's disclaimer policy is available.
