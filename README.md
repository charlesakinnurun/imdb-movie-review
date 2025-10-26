## Introduction
![Movie Review](/image.jpg)
The project is a sentiment-analysis implementation applied to movie review text, likely using the Internet Movie Database (IMDb) review dataset.
It contains data of labelled reviews (positive/negative), a Jupyter notebook for exploration and model development, and a Python script to run or deploy the trained model.
The workflow includes text-preprocessing (cleaning, tokenising), feature engineering (vectorising text), training a classification model and evaluating its performance.
It serves as a practical example of applying machine learning to natural language data, especially text classification tasks.
While useful as a learning resource, the documentation is minimal and the codebase appears to be designed at an introductory or educational level.

### Procedures
- Data Loading
- Data Exploration
- Data Preprocessing
- Pre-Training Visualization
- Data Encoding
- Feature Engineering
- Data Splitting
- Model Pipeline 
- Model Comparison
- Hyperparameter Tuning
- Model Evaluation of Tuned Model
- Post-Training Visualization
- Function for New Prediction

#### Usage Instructions
To run this project locally:
1. Clone the repository:
```
git clone https://github.com/charlesakinnurun/imdb-movie-review.git
cd imdb-movie-review
```
2. Install required packages
```
pip install -r requirements.txt
```
3. Open the notebook:
```
jupyter notebook model.ipynb

```

#### Project Structure
```
customer-personality/
│
├── model.ipynb  
|── model.py    
|── imdb.csv  
├── requirements.txt 
├── .gitignore
├── LICENSE
├── image.jpg       
└── README.md 
```

#### Dependencies
Key Python libraries used in this project include:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- jupyter

You can install all dependencies via:
```
pip install -r requirements.txt
```

#### Contributing
Contributions are welcome! If you’d like to suggest improvements — e.g., new modelling algorithms, additional feature engineering, or better documentation — please open an Issue or submit a Pull Request.
Please ensure your additions are accompanied by clear documentation and, where relevant, updated evaluation results.

#### License
This project is licensed under the MIT License. See the [LICENSE](/LICENSE)
 file for details.