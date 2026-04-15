# ex-17
# Nikunj Deep Upadhyay
# entc b1
# 25070123081
THEORY
1. Data Visualization
Data Visualization is the graphical representation of data using charts, graphs, and plots. It helps in:


Understanding patterns and trends


Comparing values


Identifying relationships between variables


Libraries used:


Matplotlib → Basic plotting


Seaborn → Advanced and attractive statistical plots


Pandas → Data handling and DataFrame creation



2. Types of Charts Used
a) Line Chart


Used to show trends over time


Data points are connected using lines


Example: Study hours across days


Helps identify increase/decrease patterns

b) Multiple Line Chart


Displays multiple datasets on the same graph


Useful for comparison (e.g., Study Hours vs Marks)



c) Bar Chart


Used for categorical comparison


Height of bars represents values


Example: Marks for each day

d) Histogram


Shows distribution of data


Divides data into bins (intervals)


Helps understand:


Frequency distribution


Data spread


Central tendency



e) Scatter Plot


Displays relationship between two variables


Each point represents one observation


Example:
Study Hours vs Marks → shows correlation

f) Conditional Scatter Plot


Adds categorical distinction using colors


Helps classify data (e.g., Pass/Fail)



g) Seaborn Plots


Enhanced visualization with better styling


Built on top of Matplotlib


Types used:


Line Plot


Histogram (with KDE – smooth curve)



3. Visual Encoding
Visual encoding means representing data using:


Position (x, y axes)


Color (categories like Pass/Fail)


Size (bar height, frequency)


Shape (markers like circle, square)



⚙️ ALGORITHM
Algorithm: Basic Data Visualization using Python
Step 1: Import Libraries


Import required libraries:


matplotlib.pyplot


seaborn


pandas


numpy (if needed)





Step 2: Create Dataset


Define data in dictionary form


Convert dictionary into DataFrame using pandas



Step 3: Plot Line Chart


Select x-axis and y-axis data


Use plt.plot()


Add title, labels


Display using plt.show()



Step 4: Plot Multiple Line Chart


Use multiple plt.plot() calls


Add labels for each dataset


Use plt.legend()



Step 5: Plot Bar Chart


Use plt.bar()


Assign categories to x-axis


Assign values to y-axis


Add labels and title



Step 6: Advanced Bar Chart


Store bars in a variable


Loop through bars


Display values on top using plt.text()



Step 7: Plot Histogram


Select numerical data


Use plt.hist()


Define number of bins


Add labels and title



Step 8: Add Mean Line (Optional)


Calculate mean using NumPy


Use plt.axvline() to show mean



Step 9: Plot Scatter Plot


Use plt.scatter(x, y)


Label axes and title



Step 10: Conditional Scatter Plot


Create category column (Pass/Fail)


Assign colors using condition


Pass colors to plt.scatter()



Step 11: Use Seaborn


Use sns.lineplot() for line chart


Use sns.histplot() for histogram


Enable KDE for smooth curve



Step 12: Display Output


Use plt.show() after each plot



CONCLUSION


Different charts serve different purposes:


Line → Trend


Bar → Comparison


Histogram → Distribution


Scatter → Relationship




Seaborn improves visualization aesthetics


Proper visual encoding makes data easy to understand



If you want, I can also convert this into exam-ready answers (2, 5, or 10 marks) or write it in PDF/PPT format 👍
