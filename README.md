# IndoML Datathon 2024 Submission

This project was made as a submission for IndoML Datathon 2024 Phase 1, which is a hackathon that took place as part of the IndoML 2024 event.

## Project Overview

Provide a brief description of your project here. Explain the problem you are solving, your approach, and the results you achieved.

## Folder Structure

The following is the folder structure of the project:

```
IndoML-Challenge/
├── input_data/
│   ├── attribute_train.data
│   ├── attribute_train.solution
│   ├── attribute_val.data
│   ├── attribute_val.solution
│   └── attribute_test.data
├── logs/
│   └── training_log.txt
├── notebooks/
│   ├── Imputation.ipynb
│   ├── Ecommerce_CatPrediction.ipynb
│   ├── Model_for_Imputation.ipynb
│   └── XGBoost_Classifier.ipynb
├── submissions/
│   └── submission_v5.zip
├── main.py
├── requirements.txt
└── README.md
```

### Purpose of Each File

- **input_data/**: Contains the input datasets for training, validation, and testing.
  - `attribute_train.data`: Training data features.
  - `attribute_train.solution`: Training data labels.
  - `attribute_val.data`: Validation data features.
  - `attribute_val.solution`: Validation data labels.
  - `attribute_test.data`: Test data features.

- **logs/**: Contains log files generated during training.
  - `training_log.txt`: Log file for tracking the training process.

- **models/**: Contains the saved models.
  - `finetuned_fT5_impute/`: Directory containing the fine-tuned T5 model for imputation.

- **notebooks/**: Contains Jupyter notebooks used for various stages of the project.
  - `Imputation.ipynb`: Notebook for data imputation.
  - `Ecommerce_CatPrediction.ipynb`: Notebook for category prediction in e-commerce data.
  - `Model_for_Imputation.ipynb`: Notebook for training the imputation model.
  - `XGBoost_Classifier.ipynb`: Notebook for training and evaluating the XGBoost classifier.

- **submissions/**: Contains the submission files.
  - `submission_v1.csv`: First version of the submission file.
  - `submission_v2.csv`: Second version of the submission file.

- **main.py**: Main script to run the project.

- **requirements.txt**: List of dependencies required to run the project.

- **README.md**: Project documentation file.


## Installation

Describe the steps required to install and set up your project.

```bash
# Clone the repository
git clone https://github.com/yourusername/IndoML-Challenge.git

# Navigate to the project directory
cd IndoML-Challenge

# Install dependencies
pip install -r requirements.txt
```

## Usage

Provide instructions on how to use your project. Include examples if possible.

```bash
# Example command to run your project
python main.py --input data/input_file.csv --output results/output_file.csv
```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

Include the license under which your project is distributed.

## Contact

For any questions or inquiries, please contact [Santhosh G S](santhoshgs013@gmail.com).
