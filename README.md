# data-for-social-good
# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As an movie enthuiast, I enjoy watching movies, <br> 
> I want to find the best movies by gathering data, <br> 
> so that I can share to others and find movies based on my tastes. 

## Dataset 

Include a hyperlink to the source of your dataset used for this project. Additionally, provide a short description of each column used from the dataset, and the data type. 

Example: 

Dataset: https://www.kaggle.com/datasets/sansuthi/global-co2-emissions 
- **Country** (String) - name of the country 
- **Population** (int) - number of people in the country 
- **CO2Emissions** (double) - carbon dioxide emission in kilotons 

Dataset: https://www.kaggle.com/datasets/sankha1998/tmdb-top-10000-popular-movies-dataset
- **Title** (String) - name of the movie
- **Overview** (String) - summary of movie
- **VoteCount** (double) - number of people who voted on movie
- **Rating** (double) - average of ratings on movie

## UML Diagram 

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get display on this README. 

![UML Diagram for my project](UMLdiagram.png)

## Description 

Write a description of your project here. In your description, include as many vocab words from our class to explain your User Story, the chosen dataset and how your project addressed that users goals. If your project used the Scanner class for user input, explain how the user will interact with your project.

The project I made with my groupmates used a dataset from IMdb about movies, it included the title, overview, vote count, and ratings. The userStory was to be a movie enthusiast that wants to find the best movies which is why we got that dataset. To organize the data we used code to make it easier for users to view. On code.org we started by creating file readers to take the informaiton from the dataset and turn it into a singular 1d array. We created a method that traverses the array with a for loop to concatenate the information to be printed altogether to form a list that prints all of the movie's state. Our project ensures that users can get the best movie experience that they desire. 
