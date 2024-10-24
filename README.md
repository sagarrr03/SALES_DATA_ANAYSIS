# Python_Sales_Analysis
In this project i worked on a Python project to analyze sales data from Diwali.
I'm focusing on which states had the highest spending, and I'm also trying to figure out which product categories were the most popular
also, I used several Python libraries in this project, 
including Pandas, NumPy, Seaborn, and Matplotlib.
I used Pandas and NumPy for data handling, and Seaborn and Matplotlib for visualization. These are all Python libraries that are very useful for data analysis.

#  sales_state = df.groupby(['Marital_Status', 'Gender'], as_index=False)['Amount'].sum().sort_values(by='Amount', ascending=False)                     sns.set(rc={'figure.figsize':(6,5)})                                                                                                              sns.barplot(data = sales_state, x = 'Marital_Status',y= 'Amount', hue='Gender')

# From above code we can see that most of the buyers are married (women) and they have high purchasing power*
