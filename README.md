# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="716" height="534" alt="image" src="https://github.com/user-attachments/assets/e3256ba4-20a2-45b6-9335-837026d7f8c1" />
<br>
<br>
<img width="684" height="534" alt="image" src="https://github.com/user-attachments/assets/228f905a-86da-4688-b443-058fe671237a" />

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()

 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="684" height="508" alt="image" src="https://github.com/user-attachments/assets/d2882b94-748e-4e6a-a10f-29a294a4dcc8" />
<br>
<br>
<img width="689" height="566" alt="image" src="https://github.com/user-attachments/assets/bb72b8ee-bd81-4c85-9079-89d493ae2af1" />

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="561" height="512" alt="image" src="https://github.com/user-attachments/assets/f4664834-b4e0-4a73-bd79-07d8482a4ba5" />
<br>
<br>
<img width="542" height="495" alt="image" src="https://github.com/user-attachments/assets/4d367b45-ac1f-459a-86c2-77f4f6f0d502" />

```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="691" height="514" alt="image" src="https://github.com/user-attachments/assets/d36ab6e7-75e9-42f7-95b8-c15879dab4e0" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="698" height="563" alt="image" src="https://github.com/user-attachments/assets/0df7ffec-d13a-40e0-bd5a-51c53260b248" />

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="665" height="510" alt="image" src="https://github.com/user-attachments/assets/72e3e5f4-7ced-4093-b6d0-00b58e7d759c" />

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="711" height="444" alt="image" src="https://github.com/user-attachments/assets/455f1cda-11f7-4634-a33e-42fb62c13825" />


```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

<img width="706" height="595" alt="image" src="https://github.com/user-attachments/assets/29e6fc29-79b8-43ce-bac5-1d8fc22096a1" />







# Result:

 Thus, all the data visualization techniques of matplotlib has been implemented.
