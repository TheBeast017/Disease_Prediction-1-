### **Disease Prediction System using Machine Learning**
This project focuses on predicting diseases based on user-input symptoms using **machine learning techniques**. The system analyzes a dataset of symptoms and their associated diseases, encoding symptom severity and applying a **neural network classifier (MLPClassifier)** for accurate disease prediction. The model achieves an impressive **99% accuracy** by training on a dataset that converts categorical symptom data into numerical values using **one-hot encoding**.

#### **Key Features and Implementation**
- **Data Preprocessing**: The dataset, containing symptoms and corresponding diseases, was cleaned and preprocessed. Missing values were handled, and categorical symptom data was converted into numerical values using **one-hot encoding** for model compatibility.
- **Symptom Severity Mapping**: Symptoms were mapped to severity weights using a predefined severity dataset, ensuring accurate input representation for the model.
- **Model Training**: A **Multi-Layer Perceptron (MLP) Classifier** from Scikit-learn was trained on the preprocessed dataset. The model was optimized to achieve **99% accuracy** in disease prediction.
- **User Interaction**: Users can input their symptoms, and the system maps these to severity weights, feeding them into the trained model to predict potential diseases. The model supports up to 17 symptoms for prediction.
- **Model Persistence**: The trained model was saved using **pickle**, allowing it to be reloaded for future predictions without retraining.

#### **Technologies Used**
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn (MLPClassifier), Matplotlib, Seaborn
- **Data Processing**: One-Hot Encoding, Data Cleaning, Severity Mapping
- **Model Deployment**: Pickle for model saving and loading

#### **Impact and Applications**
- **Early Disease Detection**: The system assists in early and accurate disease detection based on common symptoms, potentially improving healthcare outcomes.
- **Scalability**: The model can be extended to include more diseases and symptoms, making it adaptable for broader medical applications.
- **User-Friendly**: The system provides a simple interface for users to input symptoms and receive disease predictions, making it accessible for non-technical users.

This project demonstrates the power of **AI and data processing** in healthcare, showcasing my ability to develop end-to-end machine learning solutions for real-world problems. It highlights my expertise in **data preprocessing, model training, and deployment**, as well as my commitment to creating impactful, data-driven applications.
