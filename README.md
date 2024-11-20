# Applied Data Science Capstone  

This project is part of the final course in the IBM Data Science Professional Certificate specialization. It demonstrates the application of data science concepts and techniques to a real-world scenario, focusing on SpaceX's reusable rocket technology.  

---

## Project Overview  
SpaceX has disrupted the commercial space industry by drastically reducing launch costs through its reusable rocket technology. A Falcon 9 rocket launch costs $62 million, compared to $165 million charged by other providers. The key to this cost efficiency is reusing the first stage of the rocket.  
This project aims to predict the likelihood of a successful first-stage landing using public data and machine learning models.  

---

## Key Questions  
1. How do variables such as payload mass, launch site, number of flights, and orbit type affect the success of first-stage landings?  
2. Has the success rate of landings improved over time?  
3. Which machine learning algorithm is best suited for binary classification in this scenario?  

---

## Methodology  

### 1. Data Collection  
- **Sources**:  
  - SpaceX REST API  
  - Web scraping from Wikipedia  

### 2. Data Wrangling  
- Filtering relevant data  
- Handling missing values  
- Encoding categorical variables using One-Hot Encoding  

### 3. Exploratory Data Analysis (EDA)  
- Visualizing relationships and trends  
- SQL for in-depth analysis  

### 4. Interactive Visual Analytics  
- Tools used:  
  - **Folium** for geospatial visualizations  
  - **Plotly Dash** for interactive dashboards  

### 5. Predictive Analysis  
- Building, tuning, and evaluating machine learning classification models to ensure accuracy  

---

## Results and Insights  
- Insights on the factors influencing successful landings  
- Evaluation of the best-performing classification model for predicting outcomes  
- Trends in success rates over time  

---

## Tools and Technologies  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly, Folium  
- **Data Access**: SpaceX REST API, Web scraping  
- **Machine Learning**: Binary classification models  

---

## How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone <repository-url>
