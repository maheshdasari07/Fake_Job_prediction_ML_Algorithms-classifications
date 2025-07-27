# Fake_Job_prediction_ML_Algorithms-classifications
To avoid fraudulent post for job in the internet, an automated tool using machine learning based classification techniques is proposed in the paper. Different classifiers are used for checking fraudulent post in the web and the results of those classifiers are compared for identifying the best employment scam detection model. 
PROPOSED SYSTEM
 The target of this study is to detect whether a job post is fraudulent or not. Identifying and eliminating these fake job advertisements will help the job seekers to concentrate on legitimate job posts only. In this context, a dataset from Kaggle is employed that provides information regarding a job that may or may not be suspicious.

A.Implementation of Classifiers
 In this framework classifiers are trained using appropriate parameters. For maximizing the performance of these models, default parameters may not be sufficient enough. Adjustment of these parameters enhances the reliability of this model which may be regarded as the optimised one for identifying as well as isolating the fake job posts from the job seekers.

B.Performance Evaluation Metrics 
While evaluating performance skill of a model, it is necessary to employ some metrics to justify the evaluation. For this purpose, following metrics are taken into consideration in order to identify the best relevant problem-solving approach. Accuracy is a metric that identifies the ratio of true predictions over the total number of instances considered. However, the accuracy may not be enough metric for evaluating model‘s performance since it does not consider wrong predicted cases. If a fake post is treated as a true one, it creates a significant problem. Hence, it is necessary to consider false positive and false negative cases that compensate to misclassification. For measuring this compensation, precision and recall is quite necessary to be considered.
#Requirments
Operating System	Windows 10/11
Development Software	Python 3.10
Programming Language	Python
Domain	Machine Learning
Integrated Development Environment (IDE)	Visual Studio Code
Front End Technologies	HTML5, CSS3, Java Script
Back End Technologies or Framework	Django
Database Language	SQL
Database (RDBMS) 	MySQL
Database Software	WAMP or XAMPP Server
Web Server or Deployment Server	Django Application Development Server




# Fake Job Prediction Using ML Algorithms

This project aims to combat fraudulent job postings on the internet by using machine learning (ML) classification techniques. By detecting fake job advertisements, we help job seekers focus only on legitimate opportunities.

---

## 📂 Project Structure

```
Fake_Job_prediction_ML_Algorithms-classifications/
│
├── data/                # Datasets (raw and processed)
├── notebooks/           # Jupyter notebooks for exploration and experiments
├── src/                 # Source code for data processing and model building
│    ├── data_preprocessing.py
│    ├── feature_engineering.py
│    ├── model_training.py
│    ├── model_evaluation.py
│    └── utils.py
├── models/              # Trained ML models
├── webapp/              # Django web application code
│    ├── fake_job_detector/
│    ├── templates/
│    ├── static/
│    └── manage.py
├── requirements.txt     # Python package requirements
├── README.md            # Project overview (this file)
└── LICENSE
```

---

## 🚀 What Does the System Do?

- **Goal:** Identify whether a job posting is real or fake using machine learning.
- **Why:** Fake job ads waste time and may scam job seekers. Our tool automates the detection process.
- **How:** We train and evaluate several ML classification algorithms on features extracted from job postings.

---

## 🛠️ How Does It Work?

1. **Data Preparation:**  
   Collect and preprocess job post data (cleaning, feature extraction).

2. **Model Training:**  
   Train various ML classifiers (e.g., Logistic Regression, Random Forest, SVM) with tuned parameters for best performance.

3. **Performance Metrics:**  
   Evaluate models using:
   - Accuracy
   - Precision & Recall
   - F1 Score
   - ROC-AUC

4. **Web Deployment:**  
   The best model is integrated into a Django web application, allowing users to input job details and get predictions in real time.

---

## 💻 Requirements

| Component             | Details                        |
|-----------------------|-------------------------------|
| OS                    | Windows 10/11                  |
| Python Version        | 3.10                           |
| IDE                   | Visual Studio Code             |
| Front End             | HTML5, CSS3, JavaScript        |
| Back End              | Django (Python framework)      |
| Database              | MySQL (via WAMP/XAMPP)         |
| Web Server            | Django Development Server      |

---

## 🏁 Getting Started

1. **Clone the repository:**  
   `git clone https://github.com/maheshdasari07/Fake_Job_prediction_ML_Algorithms-classifications.git`

2. **Install dependencies:**  
   `pip install -r requirements.txt`

3. **Prepare the data:**  
   Place your dataset files inside the `data/` folder.

4. **Train the models or explore with notebooks:**  
   Use scripts in `src/` or open Jupyter notebooks in `notebooks/` for experimentation.

5. **Run the web application:**  
   ```
   cd webapp
   python manage.py runserver
   ```

---

## 🏆 Conclusion

Our machine learning-based solution helps job seekers avoid scams by automatically detecting fraudulent job postings. By leveraging multiple classifiers and evaluation techniques, the system provides reliable predictions to guide users toward genuine job opportunities.

---

## 📄 License

See [LICENSE](LICENSE) for details.
Design/Modelling	Rational Rose

CONCLUSIONS 
Employment scam detection will guide job-seekers to get only legitimate offers from companies. For tackling employment scam detection, several machine learning algorithms are proposed as countermeasures in this paper. Supervised mechanism is used to exemplify the use of several classifiers for employment scam detection. Experimental results indicate that Random Forest classifier outperforms over its peer classification tool. The proposed approach achieved accuracy 98.27% which is much higher than the existing methods.
