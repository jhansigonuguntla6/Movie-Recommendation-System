# Movie-Recommendation-System


## Description
This project implements a movie recommendation system using machine learning techniques. It predicts movie revenue based on various features and recommends movies to users.

## Dataset
The dataset used for this project is sourced from [YBI Foundation GitHub](https://github.com/YBI-Foundation/Dataset/raw/main/Movies%20Recommendation.csv). 
Preprocessing steps include handling missing values, one-hot encoding categorical variables, and imputing numerical columns.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.

## Usage
1. Run `model_training.ipynb` to train the recommendation model.
2. Adjust parameters in the pipeline for experimentation.
3. Evaluate model performance using mean squared error (MSE).

## File Descriptions
- `data_preprocessing.ipynb`: Jupyter notebook for data cleaning and preprocessing.
- `model_training.ipynb`: Jupyter notebook for training machine learning models.

## Modeling
- Utilizes RandomForestRegressor in a pipeline for scaling and modeling.

## Evaluation
- Model performance evaluated using mean squared error (MSE).

## Results
- Achieved MSE of 1000 on test data.
- Insights gained from movie revenue predictions.

## Contributing
Contributions are welcome. Please open an issue to discuss potential changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Thanks to the YBI Foundation for providing the dataset.

## Contact
For questions or feedback, please contact [Jhansi Gonuguntla](mailto:jhansigonuguntla6@gmail.com).



