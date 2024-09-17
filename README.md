# **Data Wrangling and Data Visualization** 
## 📊&nbsp;&nbsp;Overview
Harness the power of Data Wrangling and Data Visualization to transform raw, messy data into insightful, meaningful visual stories. Whether you're dealing with chaotic datasets or presenting complex patterns, mastering these techniques is essential to understanding and communicating data effectively. In this assignment, we’ll clean, structure, and visualize data from board2.xlsx to uncover hidden insights. Ready to dive into the art and science of data?
## 📊&nbsp;&nbsp;Making Data Behave (So You Don't Have To 😅)
Data wrangling is the process of transforming raw data into a clean and useful format, which is essential for accurate analysis. It’s like trying to organize your messy room – once everything’s in its place, things become a lot clearer. Once wrangled, data visualization takes the stage, helping you uncover insights through charts and graphs, bringing your findings to life. In this assignment, we combine these two skills to turn raw data into valuable, digestible insights using Python’s Pandas and visualization libraries.
## 📊&nbsp;&nbsp;The Basics
- Data Wrangling is the **process of cleaning and organizing raw data** into a structured format.
- It involves dealing with missing values, correcting data types, and reshaping the dataset for analysis.
- Data Visualization uses visual tools like graphs and charts to represent data in a comprehensible way.
- Common tools include Pandas for wrangling and **Matplotlib** or **Seaborn** for visualization.
- The goal is to reveal patterns, trends, or correlations hidden in raw data.
## 📊&nbsp;&nbsp;Setup
1. Install Jupyter Notebook through [Anaconda Navigator](https://www.anaconda.com/download) or directly from their [website](https://jupyter.org)
2. Run the following command in the terminal to start Jupyter Notebook:
```
jupyter notebook
```
4. Download `board2.xlsx`.
5. Open `Instru = [“Name”, “GEAS”, “Electronics >70”].ipynb`, `Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”].ipynb`, and `Visualization.ipynb` within the same file directory as `board2.xlsx`.
6. Execute the codes
## 📊&nbsp;&nbsp;Usage
Access the data by inputting the following command:
```
pd.read_excel('board2.xlsx')
```
_This is will allow you to access the data that will be used as you perform data manipulation tasks_

Sneak peek of the dataset:
| Name | Gender | Track          | Hometown | Math | Electronics | GEAS | Communication |
|------|--------|----------------|----------|------|-------------|------|---------------|
|      | Male   | Instrumentation | Luzon    | 58   | 89          | 75   | 78            |
| S1   | Female | Communication  | Mindanao | 52   | 75          | 90   | 52            |
| S2   | Female | Instrumentation| Mindanao | 83   | 74          | 77   | 57            |
| S3   | Male   | Instrumentation| Visayas  | 65   | 58          | 91   | 68            |
| S4   | Male   | Communication  | Luzon    | 59   | 86          | 43   | 88            |
| ...  | ...  | ...  | ...    | ...  | ...       | ... | ...      |
| S28   | Male | Communication| Visayas | 85   | 53          | 80   | 53            |
| S29  | Male   | Instrumentation | Mindanao | 73   | 48         | 71   | 62            |
| S30   | Male   | Instrumentation | Luzon    | 78   | 81         | 57  | 56            |

### Running the Scripts
Here’s a quick look at how to run the scripts and visualize the results:
```
import pandas as pd
data = pd.read_excel('board2.xlsx')

# _Perform some data wrangling_
filtered_data = data[data['Electronics'] > 70]

# _Visualizing it by using bar graph_
import matplotlib.pyplot as plt
plt.hist(filtered_data['Electronics'])
plt.show()
```
![Screenshot of a bar graph by Matplotlib for Electronics](https://i.pinimg.com/originals/c9/fa/d2/c9fad29d4129997bab474948f7d858b0.png)
## 📊&nbsp;&nbsp;Takeaways
- Start small: Begin by understanding the basics of Python syntax before diving into libraries like Pandas or Matplotlib.
- Practice **data wrangling**: Learn to clean and manipulate data using **PANDAS** (click [here](https://github.com/merkjunnie/ECE2112_Exp-3) to see my outputs) —it's the foundation of many data projects.
- Visualize everything: Use simple visualizations in **Matplotlib** or **Seaborn** to see trends early. It helps to understand your data better.
- Explore documentation: Don't hesitate to check [Stack Overflow](https://stackoverflow.com/) or the [Github](https://github.com/explore) community for help—there's always someone who faced the same problem!
- Experiment and learn: Python coding is all about trial and error. Break your code, fix it, and understand what works best—learning comes from doing!
## 📊&nbsp;&nbsp;Contact
For any questions or feedback, please reach out to:<br>
- Email: johnmarkaparicio.eng@ust.edu.ph <br>
- GitHub: https://github.com/merkjunnie



