### Project: Exploratory Data Analysis and Predictive Analysis of SpaceX Launch Data

#### Introduction
SpaceX, a prominent player in the aerospace industry, provided a rich dataset that prompted the "Exploratory Data Analysis and Predictive Analysis of SpaceX Launch Data" project. This initiative aimed to uncover insights into critical aspects of SpaceX's operations, such as their launch success rates, factors influencing payload mass, and the geographical distribution of launch sites. Through a combination of data exploration and predictive modeling, the project sought to gain a comprehensive understanding of SpaceX's activities.

#### Problem
The primary challenge addressed in this project was to analyze SpaceX's historical launch data to identify trends, patterns, and key factors influencing the success or failure of their launches. By doing so, we aimed to provide actionable insights that could potentially improve future launch outcomes.

#### Methods
- **Data Collection and Wrangling:** The project began with the gathering of SpaceX launch data from a dataset sourced from Kaggle. This dataset contained detailed information about each launch. The data underwent rigorous cleaning and wrangling processes to ensure accuracy and consistency. Missing values were handled, duplicates were removed, and the data was formatted for analysis.

- **Exploratory Data Analysis (EDA) and Interactive Visual Analytics:** Following data preparation, an in-depth Exploratory Data Analysis (EDA) was conducted. Utilizing Python libraries such as Pandas, NumPy, and Matplotlib, we created various visualizations, including histograms, scatter plots, and bar charts. These visualizations provided insights into the distribution of payload mass, success rates across different launch sites, and more. Interactive visualizations were also developed using Plotly and Dash, enabling a dynamic exploration of the data through an intuitive dashboard.

- **Predictive Analysis:** Building on the insights gained from EDA, machine learning algorithms were employed for predictive analysis. Logistic Regression, Support Vector Machines (SVM), and Decision Trees were utilized to predict the success or failure of SpaceX launches based on various features. These models were trained on a portion of the dataset and evaluated on unseen data to assess their performance.

#### Results and Inferences
- **EDA with Visualization Results:**
  - Histogram: The majority of launches fell within the 0-5000 kg payload mass range, with a peak around 2000 kg.
  - Scatter Plot: Launch site CCAFS SLC-40 exhibited the highest success rate among launch sites.
  - Bar Chart: Successful launches tended to have a slightly higher average payload mass compared to failed launches.
  - ![EDA Visualization Results](https://github.com/vgopika999/FINAL-PROJECT/blob/main/EDA%20visualisation%20result.png)

- **EDA with SQL Results:**
  - SQL Query: Count of Successful Launches by Launch Site highlighted the success rates of different launch sites.
  - SQL Query: Average Payload Mass by Launch Outcome provided insights into the relationship between payload mass and launch success.
  - ![EDA SQL Results](https://github.com/vgopika999/FINAL-PROJECT/blob/main/EDA%20SQL%20results.png)

- **Interactive Map with Folium Results:**
  - Folium Map: The geographical distribution of launch sites was visualized, showcasing locations and their proximity to coastlines and highways.
  - ![Folium Map](https://github.com/vgopika999/FINAL-PROJECT/blob/main/Folium%20map.png)

- **Plotly Dash Dashboard Results:**
  - Dashboard: An interactive interface was provided to explore various aspects of the SpaceX launch data, allowing users to interact with and analyze the data dynamically.
  - ![Dash Result](https://github.com/vgopika999/FINAL-PROJECT/blob/main/Dash%20result.png)

- **Predictive Analysis (Classification) Results:**
  - Logistic Regression: Achieved an accuracy of 85%.
  - SVM: Achieved an accuracy of 82%.
  - Decision Trees: Achieved an accuracy of 78%.
  - Best Performing Model: Logistic Regression emerged as the best performing model with an accuracy of 85%.
  - ![Predictive Analysis Results](https://github.com/vgopika999/FINAL-PROJECT/blob/main/Predictive%20analysis%20result.png)

#### Conclusion
The "Exploratory Data Analysis and Predictive Analysis of SpaceX Launch Data" project yielded valuable insights into SpaceX's launch operations. Through thorough data exploration and predictive modeling, we identified patterns in launch success rates, analyzed factors affecting payload mass, and visualized the geographical distribution of launch sites. The interactive visualizations and predictive models developed offer a robust framework for understanding and predicting SpaceX launch outcomes. This project serves as a testament to the power of data science in extracting actionable insights from complex datasets.

#### Future Steps
- Incorporate additional features such as weather data to enhance predictive models.
- Analyze the impact of specific rocket types on launch success.
- Explore real-time data integration for more dynamic analysis.

#### Appendix
**Tools Used:**
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Plotly, Dash
- SQL
- Folium
- Machine Learning (Logistic Regression, SVM, Decision Trees)
- SPSS

**Data Source:**
- Kaggle SpaceX Missions Dataset
