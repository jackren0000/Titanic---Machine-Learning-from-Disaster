### **Titanic: Predicting Survival with Machine Learning 🚢**

The sinking of the Titanic is one of the most infamous shipwrecks in history. In this project, we'll use machine learning to predict which passengers were most likely to survive this tragedy. We'll explore the data, build several models, and see which one gives us the best results.

#### **Our Approach 🗺️**

1.  **Data Deep Dive 🏊:** We started by exploring the Titanic dataset to understand the passengers. We looked at features like age, gender, class, and fare to see what stories the data could tell.

2.  **Data Prep 🛠️:** The data needed some work before we could use it. We handled missing values, converted categorical data into numbers, and even created a few new features to help our models.

3.  **Model Mania 🤖:** We didn't just build one model—we built three! We wanted to see which one would give us the most accurate predictions. We used:
    *   **K-Nearest Neighbors (KNN):** A simple model that classifies passengers based on their "neighbors."
    *   **Logistic Regression:** A statistical model that's great for binary classification.
    *   **Random Forest:** An ensemble model that combines multiple decision trees for better accuracy.
    *   **Deep Learning:** A neural network model for more complex pattern recognition.

#### **The Results 🏆**

After training and testing our models, we found that the **Deep Learning model** gave us the best results, with an accuracy of **82.46%**. This shows the power of neural networks in finding complex patterns in data.

#### **Tech We Used 🛠️**

*   Python
*   Pandas & NumPy
*   Scikit-learn
*   PyTorch
*   Jupyter Notebook

#### **Want to See the Code? 🚀**

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Titanic---Machine-Learning-from-Disaster.git
    ```
2.  **Install the libraries:**
    ```bash
    pip install pandas numpy scikit-learn torch jupyter
    ```
3.  **Run the notebook:**
    ```bash
    jupyter notebook titanic-machine-learning-from-disaster.ipynb
    ```