Water Quality EDA

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a water quality dataset to analyze the potability of water based on various physicochemical properties. The dataset includes parameters like pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, and Turbidity to determine whether a water sample is potable (drinkable) or not.

📂 Dataset Information

The dataset used in this project is available here:
(https://www.kaggle.com/datasets/adityakadiwal/water-potability/data)


Features:

ph: Acidity or alkalinity of water.

Hardness: Presence of dissolved minerals.

Solids: Total dissolved solids in water.

Chloramines: Level of disinfectants in water.

Sulfate: Sulfate ion concentration.

Conductivity: Water's ability to conduct electricity.

Organic_carbon: Organic content in water.

Trihalomethanes: Chemical compounds formed during chlorination.

Turbidity: Cloudiness of water due to suspended particles.

Potability: (1 = Potable, 0 = Non-potable)

🔍 Analysis Performed

Data Cleaning & Preprocessing

Identified missing values in pH, Sulfate, and Trihalomethanes.

Imputed missing values using the mean of respective columns.

Checked data types and confirmed correctness.

Descriptive Statistics

Analyzed mean, median, standard deviation, min-max values.

Identified that the pH values are normally distributed around 7.

Data Visualization

Histogram & KDE Plots: Distribution of features.

Box Plots: Identified outliers in pH and other parameters.

Pair Plot: Explored relationships between variables.

Correlation Heatmap: No strong correlations were found among the features.

Scatter Plot (pH vs Conductivity): No clear separation between potable and non-potable water.

📊 Key Findings

The pH distribution is normal, mostly between 6 and 8.

There are outliers in pH levels, especially in non-potable water.

Weak correlations exist between most features, meaning no single factor determines potability.

Non-potable water shows higher variance in pH levels, indicating unstable quality.

Conductivity and Sulfate show a slight positive correlation.

🚀 Future Improvements

Feature Engineering: Create additional attributes to improve potability classification.

Outlier Treatment: Apply techniques like IQR-based filtering or transformation.

Machine Learning: Implement classification models to predict water potability.

Data Balancing: Handle the class imbalance in potable vs. non-potable samples.

📎 How to Use

Clone the repository:

git clone https://github.com/AjinkyaPatil13/water-quality-eda.git

Install dependencies:

pip install pandas numpy matplotlib seaborn

📜 License

This project is open-source and available under the MIT License.

