# Indian Startup Ecosystem Analysis & Funding Predictor

![Startup Ecosystem](https://img.shields.io/badge/Startup-Ecosystem-blue)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green)
![ML Model](https://img.shields.io/badge/ML-Prediction-red)

An interactive dashboard and machine learning tool to analyze the Indian startup ecosystem and predict funding amounts based on startup characteristics.

## 🌟 Features

- **Comprehensive Data Visualization**: Explore funding trends, sectors, cities, and rounds through interactive charts
- **Startup Ecosystem Insights**: Discover patterns and key players in the Indian startup landscape
- **Funding Prediction**: ML-powered prediction of potential funding based on startup attributes
- **Personalized Recommendations**: Get tailored advice based on prediction results

## 🚀 Installation & Setup

1. Clone the repository
   ```
   git clone https://github.com/krish24coder/Grow-Startup-Analysis.git
   cd Grow-Startup-Analysis
   ```

2. Install dependencies
   ```
   python install_dependencies.py
   ```
   
   Or install manually:
   ```
   pip install -r requirements.txt
   ```

3. Run the application
   ```
   streamlit run app.py
   ```

## 📊 Data Description

The analysis is based on a comprehensive dataset of Indian startup funding from 2018-2020, including:

- **Startup Details**: Name, vertical (sector), sub-vertical, city
- **Funding Information**: Amount raised, funding round, investors
- **Temporal Data**: Funding date and associated time-based patterns

## 🔍 Analysis Included

- **Temporal Analysis**: Year-over-year funding trends, seasonal patterns
- **Geographical Insights**: Funding distribution across cities and regions
- **Sector Performance**: Leading sectors by funding amount and deal count
- **Investor Behavior**: Investment patterns and preferences
- **Funding Rounds**: Distribution and characteristics of various funding stages

## 🤖 Prediction Model

The application includes a machine learning model that predicts potential funding amounts based on:

- Location (city)
- Industry vertical
- Funding round
- Number of investors
- Time of funding

## 📂 Project Structure

```
.
├── app.py                # Main application file
├── install_dependencies.py # Script to install required packages
├── requirements.txt       # Python package dependencies
├── README.md              # Project documentation
└── data                   # Folder containing dataset(s)
    └── startup_funding.csv # Sample dataset
```

## 💻 Technologies Used

- **Python**: Primary programming language
- **Streamlit**: Interactive web application framework
- **Pandas & NumPy**: Data manipulation and analysis
- **Plotly**: Interactive data visualization
- **Scikit-learn**: Machine learning for funding prediction
- **Joblib/Pickle**: Model serialization

## 🔮 Future Improvements

- Add more recent funding data (post-2020)
- Implement NLP analysis of startup descriptions
- Integrate external economic indicators
- Expand the prediction model with more features
- Add competitor analysis functionality

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the
