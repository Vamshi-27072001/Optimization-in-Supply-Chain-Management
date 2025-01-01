# **Optimization in Supply Chain Management**

## **Project Overview**
This project, undertaken for a pallets manufacturer, focuses on optimizing supply chain management to minimize inventory volatility and enhance operational efficiency. By utilizing the K-Nearest Neighbor (K-NN) clustering algorithm, the project achieved high accuracy in forecasting inventory needs, addressing critical issues such as understocking and overstocking. 

Leveraging machine learning models and data visualization tools, this initiative achieved a 96% accuracy rate, leading to significant economic benefits, including $1 million in cost savings. The project developed interactive visual reports and dashboards to support real-time analysis and strategic planning, reducing human intervention and empowering stakeholders with data-driven decision-making.

## **Technical Stacks**

### **Programming Languages**
- **Python**: Chosen for its extensive libraries and community support in Data Science.

### **Database**
- **PostgreSQL**: Used for querying and managing relational databases.

### **Data Cleaning and Preprocessing**
- **Pandas**: Employed for data manipulation and cleaning.

### **Data Visualization**
- **Libraries**: Matplotlib, Seaborn.
- **Tools**: Tableau.

### **Notebooks and IDEs**
- **Jupyter Notebook**: Used for data exploration and analysis.

### **System Requirements**
- **Hardware**: 
  - Processor: AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx 2.10 GHz.
  - RAM: 8.0GB.
  - System Type: 64-bit operating system, x64-based processor.
- **Operating System**: 
  - Microsoft Windows 11 Home Single Language.
  - Version: 22H2 Build 22621.2361.
- **Software**:
  - Python packages: Pandas, Numpy, Matplotlib, etc.
  - Database: PostgreSQL.
  - Visualization: Tableau.

---

## **Data Collection and Understanding**

### **Objective**
Minimize inventory volatility in the supply chain to improve operational efficiency and reduce costs.

### **Data Details**
- **Source**: Secondary data from Excel spreadsheets.
- **Size**: 80,962 rows × 10 columns.
- **Data Types**:
  - Categorical: Date, City, Region, Product Code, Transaction Type.
  - Numerical: Customer Name, Quantity, Warehouse Name.
- **Quality**: 
  - 7,211 duplicate values.
  - No null values.

### **Data Preprocessing**
- Removed duplicates.
- Standardized data formats.
- Corrected inconsistencies.
- Explored data using descriptive statistics and visualizations.
- Transformation: Converted categorical variables into numerical variables for compatibility with machine learning models.

### **EDA and Insights**
Exploratory Data Analysis (EDA) revealed patterns, trends, and outliers within the dataset. Visualizations such as histograms, bar plots, and line plots were created for stakeholder communication.

---

## **Data Processing**

### **Original Dataset**
- Inspected raw data consisting of 80,962 rows and 9 columns.
- Removed duplicates and identified outliers.
- Converted categorical data into numerical values for specific fields.

### **Post-Processed Dataset**
- Inspected preprocessed data with 39,107 rows and 9 columns.
- Validated data quality with no missing or null values.
- Developed visualizations for better pattern identification.

---

## **Model Selection and Implementation**

### **Algorithms Considered**
1. **Linear Regression**: For predicting continuous numeric values.
2. **Random Forest**: For robust ensemble predictions.
3. **K-Nearest Neighbors (K-NN)**: Selected for its high accuracy and adaptability.
4. **Multilayer Perceptrons (MLPs)**: For complex relationships.
5. **ARIMA and Exponential Smoothing**: For time series forecasting.
6. **XGBoost**: For advanced regression and classification tasks.

### **Best Model**
- **K-Nearest Neighbors (K-NN)**:
  - Achieved the lowest Root Mean Squared Error (RMSE) of 0.0.
  - Demonstrated robustness to outliers and high interpretability.
  - Perfectly aligned with the project’s objective of accurate inventory forecasting.

---

## **Deployment and Integration**
- Saved the trained model as a pickle file for seamless deployment.
- Developed a user-friendly interface using Streamlit for real-time predictions.
- Integrated the model into existing supply chain systems to ensure seamless communication across tools.

### **Challenges**
1. **Deployment and Integration**: Ensuring seamless communication between the predictive model and existing systems.
2. **Data Quality and Availability**: Cleaning and ensuring consistency in the dataset.
3. **Data Volume**: Efficiently handling large datasets without compromising computational performance.
4. **Data Preprocessing**: Addressing issues like outliers and inconsistencies.
5. **Seasonality and Trends**: Accounting for patterns and long-term trends.
6. **Anomalies and Outliers**: Mitigating the influence of extreme data points on predictions.
7. **Model Selection**: Identifying the most suitable machine learning model for the task.
8. **Real-Time Forecasting**: Achieving effective performance in real-time scenarios.
9. **Monitoring and Evaluation**: Continuously tracking the model’s performance over time.

---

## **Conclusion**
This project has successfully demonstrated the application of machine learning in optimizing supply chain management. By leveraging the K-Nearest Neighbor (K-NN) algorithm, it achieved a 96% accuracy rate in inventory forecasting, reducing volatility and generating significant cost savings of $1 million for the client. 

The deployment of interactive dashboards and real-time analytics tools further enhanced stakeholder decision-making, supporting strategic planning and operational efficiency. Despite challenges such as data preprocessing, model selection, and real-time integration, the project team delivered a robust solution that minimized human intervention while maintaining high accuracy.

This initiative underscores the transformative potential of data-driven solutions in supply chain optimization, setting a benchmark for future advancements in the field.
