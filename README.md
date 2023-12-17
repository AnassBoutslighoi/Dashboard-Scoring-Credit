# Dashboard Scoring Credit - Eqdom 

### Implement a Credit Scoring Model

## Overview

This project aims to develop a **credit scoring model to assess the probability of default payments by clients.** It's designed to support decision-making in granting or denying loans to potential clients. The code includes the implementation of a Streamlit dashboard for visualizing, interpreting, and comparing client credit scores and related information.
**Web App from streamlit:** [Streamlit Share](https://dashboard-scoring-credit-eqdom.streamlit.app/)

### Description

For this project, data was manipulated using Python in Jupyter Notebooks with Streamlit app development.

The dashboard utilizes various libraries such as Pandas, Matplotlib, Seaborn, Pickle, Shap, Plotly Express, ZipFile, and Scikit-Learn's KMeans to create an interactive web interface. It allows users to:

- View individual client scores and interpretations.
- Visualize descriptive information related to a client's financial background.
- Compare a client's information against the overall dataset or similar client groups.

### Evaluated Skills
- Presenting modeling work orally
- Deploying a model via an API in the web
- Using version control software to ensure model integration
- Writing a methodological note to communicate the modeling approach
- Creating a dashboard to present modeling work

### Setup

To run this project locally, the following steps can be followed:

1. **Installation**: Ensure Python and necessary libraries are installed. If you haven't installed **Python**, consider directly installing the **Anaconda distribution.**
Anaconda is a Python distribution designed for Data Science.

This allows the installation of Python and its Data Science libraries like Pandas, Matplotlib, Seaborn, Scipy, Numpy, etc...
It also includes Jupyter notebook, which is essential and highly recommended!
Get it here: [Anaconda](https://anaconda.org/).

2. **Dependencies Installation**:

    ```bash
    pip install streamlit
    pip install pandas
    pip install matplotlib
    pip install numpy
    pip install scipy
    pip seaborn==0.11.0
    pip plotly>=4.4
    pip requests==2.25.1
    pip Pillow==8.1.0
    pip scikit_learn>=0.24.1
    pip lightgbm==3.2.1
    pip shap>=0.39

    ```

3. **Running the Dashboard**:

    ```bash
    streamlit run app.py
    ```

## Project Details

### Data Sources

The project uses data from the Kaggle dataset [Home Credit Default](https://www.kaggle.com/c/home-credit-default-risk/data).

### Dependencies

- **Streamlit**
- **Scipy**
- **Pandas**: Version >=1.1.3
- **Matplotlib**: Version >=1.19.2
- **Numpy**: Version >=1.19.2
- **seaborn**: Version==0.11.0
- **matplotlib**: Version>=3.2.2
- **plotly**: Version>=4.4
- **requests**: Version==2.25.1
- **Pillow**: Version==8.1.0
- **scikit_learn**: Version>=0.24.1
- **lightgbm**: Version==3.2.1
- **shap**: Version>=0.39

## Additional Information

- **Author**: Anass Boutslighoi
- **Dashboard Link**: [Dashboard Scoring Credit - Eqdom](https://dashboard-scoring-credit-eqdom.streamlit.app/)
- **Github Link**: [Dashboard Scoring Credit - Eqdom]https://github.com/AnassBoutslighoi/Dashboard-Scoring-Credit/)

## Note

This project was developed as an end-of-study project and was transferred from the original author to Eqdom.

For more information about the project, you can refer to the Streamlit documentation [here](https://dashboard-scoring-credit-eqdom.streamlit.app/).

