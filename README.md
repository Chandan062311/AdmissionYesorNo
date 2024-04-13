# Machine Learning Project: Predicting Admission Chance

This project aims to predict the chance of admission for students based on various features such as GRE score, TOEFL score, university rating, etc. We explore different machine learning algorithms to build regression models and compare their performance.

## Dataset

The dataset used in this project is the Admission dataset, which consists of the following columns:

- GRE Score
- TOEFL Score
- University Rating
- SOP (Statement of Purpose) Rating
- LOR (Letter of Recommendation) Rating
- CGPA (Cumulative Grade Point Average)
- Research (Whether the student has research experience)
- Chance of Admit (Target variable)

## Approach

We followed the following approach in this project:

1. **Data Exploration**: We explored the dataset to understand its structure, distribution, and relationships between features.

2. **Data Preprocessing**: We handled missing values, encoded categorical variables, and split the data into training and testing sets.

3. **Model Building**: We implemented four regression models using different algorithms:
   - ElasticNet Regression
   - Random Forest Regression
   - Neural Network Regression
   - AdaBoost Regression

4. **Model Evaluation**: We evaluated the performance of each model using the R2 score metric.

5. **Model Comparison**: We compared the R2 scores of all models to determine which algorithm performs best for this prediction task.

## Usage

To run the project:

1. Clone this repository:
  git clone https://github.com/Chandan062311/AdmissionYesorNo.git
2. Install the required dependencies:
  pip install -r requirements.txt
3. Run the main script:
   python main.py


## Results

The comparison of regression models based on the R2 score is as follows:

- ElasticNet Regression: R2 Score = 0.75
- Random Forest Regression: R2 Score = 0.82
- Neural Network Regression: R2 Score = 0.68
- AdaBoost Regression: R2 Score = 0.78

Based on the R2 scores, Random Forest Regression performs the best for predicting admission chance in this dataset.

## Contributing

Contributions to improve the project are welcome! You can contribute by:

- Adding new features to the dataset
- Experimenting with different machine learning algorithms
- Optimizing model hyperparameters
- Improving data preprocessing techniques

## License

This project is licensed under the MIT License. 


   
 
