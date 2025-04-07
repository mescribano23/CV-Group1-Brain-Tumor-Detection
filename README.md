# Research Questions and Extended Experiments

[This repository](https://github.com/MohamedAliHabib/Brain-Tumor-Detection) has been extended with additional research questions to explore the capabilities of the CNN model across different scenarios and datasets.

# Research Questions

To guide our investigation, we decided to breakdown the problem into Research Questions:

- **RQ1: How does modifying the baseline CNN model architecture affect accuracy on tumor detection?**

This research question aims to provide insight into the best architectural choices for a CNN in detecting tumors from MRI scans. The structure of a CNN significantly influences its ability to extract relevant features, generalize across different cases, and achieve high diagnostic accuracy. By systematically evaluating architectural modifications, namely layer depth, kernel size and dropout rate, we can understand the impact of design choices and identify configurations that improve performance. 
    
- **RQ2: How does including data pre-processing and data augmentation techniques affect the accuracy of the CNN model?**

This research question examines how different data pre-processing techniques affect CNN model performance, aiming to identify methods that boost classification accuracy. It also explores data augmentation, including a novel approach, simulating artifacts from auditory (hearing aid) and intracortical (restoring motor/sensory control) neural implants, to enhance model robustness. These synthetic artifacts mimic real-world MRI data variations from implant patients, and we’ll assess their impact on the model’s ability to manage complex data.


- **RQ3: How does the CNN perform on different image tasks and datasets?**

This question assesses the best architecture CNN from **RQ1** in two parts. First, to measure the generalizability of the CNN architecture on other datasets, we evaluate **binary classification** (tumor vs. no tumor) on:

- Brain MRI Images (Dataset I)
- Brain Tumor MRI (Dataset II)
- Brain Tumor Classification MRI (Dataset III)

Second, to measure the the robustness and flexibility of the model, we modify the architecture to perform a different task, specifically **multiclass classification**, on:

- Brain Tumor MRI (Dataset I)
- Figshare Brain Tumor (Dataset II).

## Running the Experiments
To run any of the research question experiments:
1. Navigate to the respective RQ folder
2. Follow the instructions in the notebook files
3. For RQ3, ensure to run `dataset_preparation.ipynb` first to download and prepare the datasets



