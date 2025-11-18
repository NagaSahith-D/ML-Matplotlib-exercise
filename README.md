## Matplotlib Exercises 
This section covers the visualizations I created while practicing **Matplotlib**, a core Python library used for plotting and data visualization.  
Throughout this exercise, I learned how to generate different types of charts, customize them, and integrate Matplotlib with pandas DataFrames.

## Tasks
• How Matplotlib works internally

• How to create various plots (line, bar, scatter, histogram, etc.)

• How to customize plots for readability and presentation

• How to use subplots for multi-visual comparisons

• How to connect Matplotlib with pandas for fast data exploration

• How visualization supports machine learning workflows

## Plot Types
### Line Plot
•	Best for trends or continuous data.

### Bar Plot
•	Good for comparing categories or grouped values.

### Scatter Plot
•	Useful for relationships and correlation analysis.

### Histogram
•	Shows distribution, spread, and skewness.

### Box Plot
•	Reveals outliers and statistical range.

### Subplots
•	Compare several visualizations side-by-side.

## Operations I Performed (Matplotlib Exercises)
•	I imported Matplotlib using `import matplotlib.pyplot as plt` and enabled inline plotting with `%matplotlib inline` so all charts displayed inside the Jupyter Notebook.

•	I created **line plots** to visualize relationships between two continuous variables, and added titles, axis labels, and custom colors.

•	I created **bar charts** to compare counts or aggregated values across categories such as car brands or door types.

•	I created **scatter plots** to show relationships between two numerical features (e.g., Odometer vs. Price) and identify patterns or correlations.

•	I created **histograms** to analyze the distribution of numerical values like car prices or odometer readings.

•	I used **pandas DataFrame plotting** with `.plot()` to generate visualizations quickly, such as:

-	`df["Odometer (KM)"].plot(kind="hist")`

-	`df.plot(kind="scatter", x="Odometer (KM)", y="Price")`

•	I practiced **subplot creation** using `plt.subplots()` to display multiple plots in a single figure, helping me compare visualizations side-by-side.

•	I customized plots using labels, legends, grid lines, different colors, marker styles, and figure sizes to improve clarity and aesthetics.

•	I used axis limits and plot styling options to enhance readability and highlight different aspects of the data.

## Key Syntax and Concepts Used
• `import matplotlib.pyplot as plt`  
  (Imported Matplotlib’s plotting module.)
  
• `%matplotlib inline`  
  (Displayed all plots directly in the notebook.)
  
• `plt.plot(x, y)`  
  (Created a line plot.)
  
• `plt.bar(categories, values)`  
  (Created a bar chart.)
  
• `plt.scatter(x, y)`  
  (Created a scatter plot.)
  
• `plt.hist(values, bins=10)`  
  (Created a histogram with a specified number of bins.)

• `plt.subplots(rows, cols)`  
  (Created multiple subplots in one figure.)
  
• `plt.title("Title")`, `plt.xlabel("X Label")`, `plt.ylabel("Y Label")`  
  (Added titles and axis labels to the plots.)
  
• `plt.grid(True)`  
  (Added a grid to improve readability.)
  
• `df.plot(kind="line")`  
  (Plotted a DataFrame column as a line chart.)
  
• `df["Odometer (KM)"].plot(kind="hist")`  
  (Plotted a histogram directly from a DataFrame column.)
  
• `df.plot(kind="scatter", x="Odometer (KM)", y="Price")`  
  (Created a scatter plot using DataFrame data.)

## Final Understanding
•	Through these Matplotlib exercises, I learned how to create and customize a variety of charts including **line plots, bar charts, scatter plots, histograms, and subplots**.  
•	I also learned how to integrate Matplotlib with pandas DataFrames for quick and efficient data visualization.  
•	These visualization skills helped me better understand data patterns and distributions, an important step in **data analysis and preparing datasets for machine learning models**.

