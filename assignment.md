# Assignment

## Brief

Write the Python codes for the following questions.

## Instructions

Paste the answer as Python in the answer code section below each question.

### Question 1

Question: How do you create a 2x2 subplot grid in matplotlib and select the first subplot?

Answer:

```python
fig, axes = plt.subplots(2, 2)
ax = axes[0, 0]  # Select first subplot (top-left)
```

### Question 2

Question: How to plot a line and set the color to red and style to dash in a matplotlib plot?

```python
x = [1, 2, 3, 4]
y = [1, 4, 9, 16]
```

Answer:

```python
plt.plot(x, y, 'r--')
```

### Question 3

Question: How to plot a histogram with 30 bins for `data` in matplotlib?

```python
data = np.random.randn(1000)
```

Answer:

```python
plt.hist(data, bins=30)
```

### Question 4

Question: How can you set the x-axis and y-axis labels in a matplotlib plot?

Answer:

```python
ax.set_xlabel('X-axis Label')
ax.set_ylabel('Y-axis Label')
```

### Question 5

Question: How do you create a bar plot in seaborn using the `tips` dataset to show the average tip amount per day?

```python
import seaborn as sns
tips = sns.load_dataset('tips')
```

Answer:

```python
sns.barplot(x='day', y='tip', data=tips)
```

### Question 6

Question: How to create a box plot for total_bill categorized by day in the `tips` dataset using seaborn?

Answer:

```python
sns.boxplot(x='day', y='total_bill', data=tips)
```

## Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
