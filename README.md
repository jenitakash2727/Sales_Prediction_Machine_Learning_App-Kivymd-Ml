# 📊 Sales Prediction App

A mobile-friendly application built with **KivyMD** that predicts sales based on advertising spend (TV, Radio, Newspaper) using **Multiple Linear Regression**.  

The app features a **dark-themed, modern UI**, allowing users to:
- Upload CSV datasets
- Preview data
- Train a regression model
- View model performance metrics (R² Score, MSE)
- Visualize prediction results with a scatter plot

---

## ✨ Features

- **📂 File Upload** – Load CSV files via file manager  
- **👀 Data Preview** – View dataset rows + row/column count  
- **⚡ Model Training** – Train a **Linear Regression model**  
- **📊 Results Display** – Shows **R² Score** and **Mean Squared Error**  
- **📈 Plot Visualization** – Dark-themed scatter plot comparing actual vs predicted sales  

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **Kivy** & **KivyMD** (Mobile-friendly UI)
- **Pandas** (Data handling)
- **Scikit-learn** (Machine learning)
- **Matplotlib** (Plotting)

---

## 📂 Project Structure



├── main.py # Main application code
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── prediction_plot.png # Generated plot (after training)



---

## ⚙️ Installation

1. **Clone the repository**  
   ```bash
   git clone  https://github.com/Thanisha2727/Machine-Learning-Sales-Predictor-App-Kivymd-Ml-
   cd sales-prediction-app


python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


pip install -r requirements.txt


| TV    | Radio | Newspaper | Sales |
| ----- | ----- | --------- | ----- |
| 230.1 | 37.8  | 69.2      | 22.1  |
| 44.5  | 39.3  | 45.1      | 10.4  |
| 17.2  | 45.9  | 69.3      | 9.3   |


R² Score: 0.92
MSE: 1.25



Prediction Plot
A scatter plot showing predicted vs actual sales with a diagonal reference line.

✅ Requirements

See requirements.txt
 for full list.

📜 License

This project is licensed under the MIT License – feel free to use and modify.

🙌 Acknowledgements

KivyMD
 for mobile UI components

Scikit-learn
 for regression modeling

Matplotlib
 for plotting


---

## 📦 requirements.txt  

```txt
kivy>=2.3.0
kivymd>=1.2.0
pandas>=2.0.0
matplotlib>=3.8.0
scikit-learn>=1.3.0



Future Enhancements

 Add support for custom column selection

 Export trained model (.pkl)

 Real-time prediction with user inputs

 Add more regression models (Ridge, Lasso, Polynomial)

 Deploy as Android APK

🤝 Contributing

Contributions are welcome!

Fork this repo

Create your feature branch (git checkout -b feature-name)

Commit changes (git commit -m "Add feature")

Push to branch (git push origin feature-name)

Open a Pull Request

📜 License

This project is licensed under the MIT License.
See the LICENSE
 file for details.

🙌 Acknowledgements

KivyMD

Scikit-learn

Matplotlib
