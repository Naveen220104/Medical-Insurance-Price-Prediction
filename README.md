# Medical Insurance Price Prediction

## 📌 Project Overview
This project aims to predict the **medical insurance costs** for individuals based on various factors such as age, BMI, smoking status, and gender. The model is trained using machine learning techniques to provide accurate cost estimations, helping insurance companies and individuals understand the key factors affecting medical expenses.

## 📂 Dataset Information
The dataset used for this project contains the following features:
- **age**: Age of the individual
- **sex**: Gender (0 = Female, 1 = Male)
- **bmi**: Body Mass Index (BMI)
- **smoker**: Smoking status (0 = No, 1 = Yes)
- **charges**: Medical insurance cost (Target variable)

## 🛠 Tech Stack
- **Programming Language**: Python
- **Libraries Used**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Model Used**: Random Forest Regressor
- **Deployment**: Flask (if applicable)

## 🚀 Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/medical-insurance-prediction.git
   cd medical-insurance-prediction
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Model Training**
   ```sh
   python train.py
   ```
4. **Run the Flask App (if deployed)**
   ```sh
   python app.py
   ```

## 🔍 Exploratory Data Analysis (EDA)
Performed **data visualization and statistical analysis**, including:
- Distribution plots of BMI, age, and charges
- Correlation heatmaps to identify feature relationships
- Box plots to detect outliers

## 📊 Model Building
- **Data Preprocessing**: Encoding categorical variables, handling missing values
- **Feature Scaling**: StandardScaler for normalization
- **Model Training**: Random Forest Regressor for accurate predictions
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - R-squared Score (R2)
  - Mean Absolute Error (MAE)

## 🎯 Results
- Achieved **high accuracy** with an optimized Random Forest model
- Identified **smoking status** as a significant factor in insurance costs

## 🏗 Future Improvements
- Incorporate **deep learning models** for better accuracy
- Add **real-time API deployment** for insurance companies
- Enhance dataset with **more demographic and health-related features**

## 🤝 Contributing
Feel free to fork the repository and submit pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.

---

