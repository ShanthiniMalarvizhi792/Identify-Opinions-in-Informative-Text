# Identify-Opinions-in-Informative-Text

## Description

This project aims to classify text as either opinionated or informative. It uses two distinct models: one trained on an information dataset and another trained on an opinion dataset. The models generate probabilities for the test dataset, which are then normalized and aggregated to compute an opinion score and an information score. Based on these scores, the test text is classified.


## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the Repository**

   >   git clone https://github.com/ShanthiniMalarvizhi792/Identify-Opinions-in-Informative-Text.git

2. **Navigate to the Project Directory**

    >  cd Identify-Opinions-in-Informative-Text


3. **Install Required Dependencies**

    >  pip install -r requirements.txt

## Datasets Used

1. [VoxPopuli](facebook/voxpopuli)
2. [Common Voice](mozilla-foundation/common_voice_9_0)

## Model Used
Gemma-2b

## Project Files

- **Information Model Notebook**: Contains code for training and validating the model on the information dataset.
- **Opinion Model Notebook**: Contains code for training and validating the model on the opinion dataset.
- **Model Evaluations Notebook**: Includes code for testing the models on the classification task. Testing is performed using manually selected headlines from the `kaggle_newspaper_test_dataset` JSON file.


## Usage

- **Train Models:** Use the respective notebooks to train the information and opinion models.
- **Evaluate Models:** Run the Model Evaluations notebook to test and classify the text using the trained models.

For detailed instructions on running the notebooks, please refer to the respective notebooks within the project.
