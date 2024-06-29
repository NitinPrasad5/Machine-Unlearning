
## Problem: 
Machine learning models often retain learned information even after the data used to train them is deleted. This can lead to privacy concerns and regulatory compliance issues, especially when handling sensitive information. Machine unlearning addresses this challenge by enabling models to "forget" specific data without retraining from scratch, ensuring privacy and compliance while maintaining model performance.

## About the project:
The aim of Unlearnify is to develop an advanced machine unlearning framework that enhances the efficiency and accuracy of removing specific data from trained models. By integrating a noise-induced impairment model with a student-teacher framework and incorporating curriculum learning,this project shows significant improvements in both forget accuracy and retain accuracy.


## Usage

### Running the Code

1. Download the repository and upload it to a drive folder.
2. Navigate to the root directory containing the `Main.ipynb` file.
3. In the second cell of the IPYNB file, change the folder path to the path of your folder on your drive.
4. Run the cells one by one; results will be produced accordingly.

Results will be saved in CSV files as specified in the scripts (look for filenames ending with `-out`).

### Code Flow

- **dataset.py**: Contains the code for downloading and arranging the data in the required format.
- **metrics.py**: Contains the code for evaluation metrics.
- **model.py**: Contains the code for the model architecture.
- **unlearn.py**: Contains the code for unlearning algorithms.
- **utils.py**: Contains the code for training utility functions.

### Workflow in IPYNB Files

1. Download the data.
2. Split the data into forget and retain sets as required.
3. Train the original model on all the data.
4. Evaluate the performance of the original model.
5. Apply unlearning algorithms to the model.
6. Evaluate the performance of the unlearned model.

## Results

- **Forget Accuracy**: Improved by 3%
- **Retain Accuracy**: Enhanced by 5%



