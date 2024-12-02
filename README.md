# SubscriptionMeter Pro - Real-time Term Deposit Subscription Prediction Web Application 📈📊

SubscriptionMeter Pro is a powerful web application built on top of a Logistic Regression and Gradient Boosting Classifiers (models), designed to predict if the client will subscribe a term deposit. It provides businesses with real-time insights into customer behaviour and helps optimize customer management strategies 💼💰🤖

## Table of Contents 📚

- [Introduction](#introduction) 📝
- [Features](#features) ✨
- [Demo](#demo) 🚀
- [Getting Started](#getting-started) 🏁
  - [Installation](#installation) 🛠️
  - [Running the App](#running-the-app) 🏃
- [App Structure](#app-structure) 🧱
- [Usage](#usage) 📊
  - [Making Predictions](#making-predictions) 📈
- [Technologies Used](#technologies-used) 💻🔬
- [Contributing](#contributing) 🤝🙌
- [License](#license) 📜

## Introduction 🚀

SubscriptionMeter Pro uses a state-of-the-art Logistic Regression and Gradient Boosting Classifiers (models) to predict term deposit subscription. It offers a user-friendly interface for inputting customer data and receiving instant predictions.

## Features ✨

- Real-time customer behavior predictions.
- Interactive user interface.
- Easy-to-use design.

## Demo 🚀

- ### Pictures 📸
  | ![Output variable](https://github.com/user-attachments/assets/2f2d6307-6ab6-4cd1-9716-f6ce2a179eca)| ![Feature_corr](https://github.com/user-attachments/assets/6d8b0b80-e79c-4043-a251-39ea48a87569)

  |![Modelling result](https://github.com/user-attachments/assets/4190c23e-a015-407a-b717-ca0b90e4d0b9)|  

- ### Article Link 🌐
  [Read Article]()

## Getting Started 🏁

Follow these instructions to get the app up and running on your local machine.

### Installation 🛠️

1. Clone the repository:

   ```bash
   git clone https://github.com/Makafui-Kwawu/Bank-Customers-Term-Deposit-Prediction.git
   cd Bank-Customers-Term-Deposit-Prediction
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the App 🏃

Run the Streamlit app using the following command:

```bash
python src/app/app.py
```

Access the app through your web browser at `http://localhost:8501/`.

## App Structure 🧱

- `Home.py`: file is the entry point to the application/main scripts `Home.py`.
- `pages/`: Directory pages directory contains all the pages files.
- `Data/`: Directory stores the data used for the application.
- `models/`: Directory for storing the pre-trained models and the encoder.
- `utils/`: Directory containing all other utility files.

## Usage 📊

### Making Predictions 📈

1. Fill in the customer data in the required fields.
2. Click the "Submit" button to receive a real-time prediction.

## Technologies Used 💻🔬

- Streamlit: Python library for building interactive interfaces.
- Pandas: Data manipulation and analysis library.
- Scikit-Learn: Machine learning library.

## Contributing 🤝🙌

Contributions to the SubscriptionMeter Pro project are welcome. Please follow these guidelines for contributing:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`
3. Make your changes and commit them with clear, concise commit messages.
4. Push your changes to your fork.
5. Create a pull request against the main repository.

## License📜

This project is licensed under the [MIT License](LICENSE).

## Author✍️

Success Makafui Kwawu

Connect with me on LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/smkwawu/)

---

Feel free to star ⭐ this repository if you find it helpful!
