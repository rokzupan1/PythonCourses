# PythonCourses
## Object Oriented Programming with Python - Full Course for Beginners

## Python for Data Science - OOP, Classes and Inheritance
https://www.youtube.com/watch?v=boEUcROx1N8&list=WL&index=1
A class or type's methods are functions that every instance of that class or the type provides. It's how you interact with the data in a object. Sorting is an example o a method that interacts with the data in the object. You can create your own type or class in python. The class has data attributes and methods. We can create objects or instances of that class.

## PythonforDataAnalysts

* [basic_python_datatypes](https://github.com/rokzupan1/PythonCourses/blob/main/basic_python_datatypes.ipynb)
* [numpy_tutorial](https://github.com/rokzupan1/PythonCourses/blob/main/numpy_tutorial.ipynb)
* [pandas_tutorial](https://github.com/rokzupan1/PythonCourses/blob/main/pandas_tutorial.ipynb)
* [NetflixTable1](https://github.com/rokzupan1/PythonCourses/blob/main/netflix_titles.csv)
* [NetflixTable2](https://github.com/rokzupan1/PythonCourses/blob/main/netflix_titles_second.csv)
* [SimpleTable3](https://github.com/rokzupan1/PythonCourses/blob/main/simple_csv.csv)

Python is a high-level, object-oriented programming language. 

- High-level: What you program in Python is abstracted away from the actual operations a computer 
performs to get there. This means that programming is easier to understand.
- Object-Oriented: Your code is designed around the idea of Objects.

Libraries:
Connecting to Data
    - SQL Alchemy: Connect to SQL Databases
    - PySpark: Connect to Big Data
Exploring Data
    - SciPy: Run statistical analyses on data
    - Pandas: Explore data stored in tables
Modeling Data
    - skLearn: Machine Learning
    - Tensorflow: Artificial Intelligence
Visualizing and Presenting Data
    - Dash/Plotly/Streamlit: Make full web-applications

Three things to get started with this course:
- Python: This will get the Python programming language + interpreter on your computer
- Text Editor: This will help you edit and deploy your code. We'll be using VSCode
- Jupyter Notebook: This is a program used by Data Analysts to easily explore data using Python

Focus of this course will be on exploring data. That means that the most used libraries will be
SciPy and Pandas.

We'll be installing Python using a program called Conda. Conda was designed for Data Analysts and 
makes it easy to manage all the extra programs you'll need to organize as you develop your skills.

Python files normally use the .py file extension. If you see this then you know you're looking at 
a Python file. The files that we'll be working with are called Jupyter Notebooks and have the file 
extension .ipynb (this is because they used to be called IPython Notebooks). 

After Conda, I installed VSCode and inside VSCode I installed extensions pyhton and jupyter(possibly
it already came with python). After that we wrote the first line: x = 5 and I was asked to install
ipykernel in order that python can work. 

hashtag is a symbol used for commenting. Markdown is a special formatter that allows you to write out a lot
of text in different formats and can convert into HTML very easily, which is really useful if you want
to show your analysis in a universal format that everyone will understand. 

In this course we will be learning about basic python, Pandas and NumPy. Basic python is something I
need to cover but not something it is the most important to know as a data analyst. 

## SurveyMonkeyDataTransformation
I will learn how to manipulate data using python and pandas in order to turn survey monkey
dataset that comes in a wide format into a long format, that way you can take the data and
visualize it with Power BI and Tableau.
In anaconda prompt: conda install pandas. In my case it was already installed so I was able to import pandas as pd. Important
was also to select the right version of python. In this case I am using: base(Python 3.10.8) 
Through the video: how to import data from excel into pandas, how to rename columns, melting or un-pivoting, do a join, drop columns, aggregate columns.
First I edited the the Excel files following the youtube video:
* [ExcelEdit](https://github.com/rokzupan1/PythonCourses/blob/main/Data%20-%20Survey%20Monkey%20Output%20MyEdit.xlsx)

Then I learned how to get data in a long type of data from a wide type of data. The final version of transposed table is here:
* [MyFinal_Output](https://github.com/rokzupan1/PythonCourses/blob/main/MyFinal_Output.xlsx)

Using this script in pyhton: 
* [My_Data_Manipulation](https://github.com/rokzupan1/PythonCourses/blob/main/Script1%20-%20My_Data_Manipulation.ipynb)
