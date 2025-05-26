Butuh

# Sample data
categories = ['Red Banner', 'Blue Flag', 'Green Shield']
values = [50, 90, 90]

# Create the bar chart
plt.figure(figsize=(8, 6))
bars = plt.bar(categories, values, color=['red', 'blue', 'green'])

# Add a red banner (styled title)
plt.title('Sales by Product Type', fontsize=16, color='white', backgroundcolor='red', pad=20)

# Axis labels
plt.xlabel('Product Type')
plt.ylabel('Sales')

# Display the chart
plt.tight_layout()
plt.show()