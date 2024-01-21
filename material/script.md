# Introduction

## Data everywhere

Data refers to raw facts, figures, or information that can be recorded, stored, and processed. It can take various forms, including numbers, text, images, audio, and more. Data can be collected from various sources and serves as the foundation for generating insights, making decisions, and understanding patterns in different contexts.

* It can be data about nature : animal population, the surface of forests, how far are the stars in our galaxy.

* It can be data about society : the average age and gender of a population, how many persons are employed or unemployed.

* It can be data about you : what do you like to buy, where do you live, what are your political or religious opinions.

Not all data is public. Not all data should be collected.

Data has become as important as water or clean air :

* Data is everywhere : anything can be expressed as data - and once it is data, it can be exploited.
* Data can be collected automatically : Computers and electronic devices (sensors) are constantly producing and sharing data.
* Data is willingly given out by individuals : Your phone analyses what you are saying, where you are going, what you are buying.
* Data is easier and easier to process : Artificial intelligence can nowadays extract data from situations that would previously require too much work by persons (reading text, interpreting speech).

## Data and human rights

In 2018, it was revealed that Cambridge Analytica, a political consulting firm, harvested data from millions of Facebook users without their consent. This data was then used to create targeted political advertisements, influencing voters' opinions in various elections, including the U.S. presidential election in 2016, and the Brexit referendum in the United Kingdom.

## A resource that must be protected

In 2018, the fitness application Strava revealed the location of several secret US military bases, by leaking the running statistics of soldiers.

In 2017, the american company Equifax suffered one of the largest data breaches in history, exposing sensitive information, including Social Security numbers, of 147 million people. This information can allow someone to commit bank fraud and identity theft.

## Why are we here today ?

* To have fun with data - to understand how to work with data using freely available technology.
* To make you realise how important data has become in our modern world, and why everyone must be aware of its impact in our lives.

# Python for Data Analysis

## Why learn python ?

### What can Python do for you ?

Imagine a world where you can make your computer do things for you, like automate repetitive tasks or analyze information.

Python is a special language that helps you make this happen.


Python is a programming language, but think of it more like a tool that lets you communicate with your computer. It's known for being friendly and easy to understand, it is made of simple English words such as **if** (=li), **then** (=pak),  **for** (=opakovat).

You can use Python to automate tasks, like renaming organizing your photos, perform calculations. It's like having a helpful assistant.

With Python, you write commands or instructions in a way that the computer understands. It then follows these instructions and responds accordingly. It's a bit like giving your computer a to-do list. It can take decisions and repeat tasks.


### Who is using Python ?

Python is used in various fields. For example, in finance, it helps analyze trends in stock markets. 

It is useful in science, where scientists around the world employ it to share their research. 

It is useful to make web sites and edit books (both on paper and in electronic format).

It is even used in art, as some artists and creators use it to generate music, make video games or even generate paintings, photos and video sequences.

One of the best things about Python is the community. There are many people around the world who use and love Python. You can find help, share ideas, and learn from others who enjoy exploring this language.

Python is not the property of a commercial company, but of humanity in general. It is free to use and free to share with anyone.

### The power is yours

In a nutshell, Python empowers you to do cool things with your computer, whether you're organizing files, creating art, or diving into new adventures. It's a tool that unlocks your creativity and makes technology work for you.

## Questions About Python

### QUESTION 1 : What can you do with Python ?

1 - only do scientific work.
2 - anything you want but you have to buy it first.
3 - science, art, business... anything you want !

### QUESTION 2 : Why can so many people in the world use Python ?

1 - Because it is simple and so easy.
2 - Because it belongs to everyone.
3 - Because scientists trust it.


## Data in Python

### Variables

In programming, we use variables to store and manage information. They're like placeholders for values that can change, making our code more adaptable - if we change the data, we do not have to change our program.

Just like using bins to organize things, variables help keep our programs organized and efficient.

Here's how you create a variable: you choose a name, like ```favorite_number``` and then you use the equal sign (=) to stick a value in it. For example:

```python
favorite_number = 5
```

Now, ```favorite_number``` is a variable holding the value 5. Anytime you want to use or change this number, you just refer to ```favorite_number```.

Variables are handy because they let you store information and use it later in your program. You can also change what's inside a variable. For instance:

```python
favorite_number = 7
```

Now, ```favorite_number``` contains 7 instead of 5.

In Python, variables help us keep track of information, make our code flexible, and reuse values whenever we need them. They're like little storage boxes that make our programs more organized and powerful.


### Lists

A list in Python is like a container where you can put multiple items in a specific order. It's a bit like making a checklist or jotting down things you need to do.

For example, a list of your favorite fruits could look like this: 

```python

fruits = ['apple', 'banana', 'orange']

```
You can easily add items in the list :

```python
fruits.append('grape')
print(fruits)
# Output: ['apple', 'banana', 'orange', 'grape']
```

or remove them :

```python
fruits = ['apple', 'banana', 'orange', 'grape']
fruits.remove('banana')
print(fruits)
# Output: ['apple', 'orange', 'grape']
```

### Dictionaries

Think of a dictionary as a special book where each item has a label or a key. It's like having a mini guide that helps you find things quickly.

For instance, a contact list in Python might be a dictionary: 

```python
contact = 
{
  'name': 'John'
 ,'email': 'john@email.com'
 ,'phone': '123-456-7890'
}
```

You use keys like 'name' or 'email' to access specific information.


## Questions About Data in Python

### QUESTION 1 : What method would a Python list use if it wanted to invite a new friend to join the party?

1- party_list.extend(new_friend)

2- party_list.import(new_friend)

3- party_list.append(new_friend)

### QUESTION 2 : If a Python dictionary were a book, what would the keys be equivalent to?

1 - Chapter titles
2 - Page numbers
3 - Table of contents

## Libraries in Python

In Python, a **library** is like a toolbox filled with useful tools. Like in a toolbox, each tool, or **module**, inside the library is designed to perform a specific task. 

Instead of creating everything from the ground up, you can use these pre-built tools to add powerful features to your own programs. You can trust that these tools have been prepared by experts and tested by a large community of users.

We are going to use many different libraries today :

* Pandas : A library that specializes in storing and transforming data.
* Matplotlib : A library that can transform data into charts, to make numerical results more appealing.
* Seaborn : A library that improves Matplotlib to represent statistical data and identify more easily interesting information.


To use a library, we must ```import``` it into our program and give it a shorter name, for instance :

```python
import pandas as pd
import matplotlib.pyplot as plot
import seaborn as sns
```


## Pandas - working with data

Pandas is a Python library that helps you work with structured data effortlessly. It's like having a powerful tool to manipulate and analyze data tables, making tasks like data cleaning and analysis much easier.

If you use Microsoft Excel, imagine being to tell it to clean and update information, do complex calculations with a single instruction (instead of having to cut and paste formulas everywhere).

### Data Frame and Series

#### DataFrame

The core of Pandas is the DataFrame. Think of it as a table or spreadsheet where you can organize and analyze your data.
A DataFrame is composed of columns (also called Series) which can contain different types of data (text, numbers or dates for instance).

You can create a DataFrame with a dictionary associating a name to a list of values :

```python
import pandas

data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Age': [25, 30, 35],
        'City': ['A', 'B', 'C']}

df = pandas.DataFrame(data)
print(df)
```

You can also load a computer file such as an Excel file (in CSV format) to create a DataFrame :

```
df = pandas.loadCSV("myFile.csv")
print(df)
```

## Seaborn and Matplotlib - Visualizing Data

### What are they used for ?

Matplotlib and Seaborn are two Python data visualization **libraries** that make it easy to create attractive and informative statistical graphics. They both work well with Pandas DataFrames and simplify the process of creating charts or other types of diagrams.

### Transforming data into a chart

```python
import pandas
import seaborn
import matplotlib.pyplot as plot

# Creating a Pandas DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Age': [25, 30, 35],
        'City': ['A', 'B', 'C'],
        'Salary': [50000, 60000, 70000]}

dataframe = pandas.DataFrame(data)

# Seaborn Example - Bar Plot
seaborn.barplot(x='Name', y='Salary', data=dataframe, palette='viridis')
plot.title('Employee Salary Information')
plot.xlabel('Employee Name')
plot.ylabel('Salary')
plot.show()

```

## Exercises

## How to continue learning ?

### Online courses

### Foxconn mentors programme