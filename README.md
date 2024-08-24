###  Developed by : Nivetha A
### Register No : 212222230101
### Date:

# Ex.No: 01A PLOT A TIME SERIES DATA

# AIM:
To Develop a python program to Plot a time series data of world population.

# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Plot the data according to need and can be altered monthly, or yearly.
4. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
file_path = 'world_population.csv'  
data = pd.read_csv(file_path)
print(data.head())
plt.figure(figsize=(10, 6))
plt.plot(data['2022 Population'], data['2020 Population'], marker='o', linestyle='-', color='b')
plt.title('World Population Over Time')
plt.xlabel('2022 Population')
plt.ylabel('2020 Population')
plt.grid(True)
plt.show()
```

# OUTPUT:

![image](https://github.com/user-attachments/assets/aefdbbeb-2c2b-45e1-91bb-3db4e482662e)


![image](https://github.com/user-attachments/assets/14da74a3-5113-46ad-b27a-ee521972a9e4)

# RESULT:
Thus we have successfully created the python code for plotting the time series of the given data.
