# Lab_Sharks_Attacks
Group: Houleye, Lucie, Tania, Sashi
This repository contains our analysis of data, focusing on shark attacks occuring in the USA, and the slides from our presentation.
Link for google slides: https://docs.google.com/presentation/d/1bvZbDIA457SFGRATUbCRIS29S5WXMhehMQWNKLvDLX0/edit#slide=id.g2f3312ab8bc_0_0
Link for https://colab.research.google.com/drive/1CXyKaycmieKJ1i7WScBo9W5VJXdx9F3x?usp=sharing#scrollTo=owKp4RPa2gY3

# Structure

For easy read, each step is detailed before the code as a comment.
1. Starting the code by importing librairies for data exploration and analysis and appropriate file
2. Exploration of the file
3. Filtering dataframe and selecting columns to create the subset we want to analyse
4. Cleaning columns' name format and empty rows
5. Cleaning columns' values using various cleaning techniques and creating relevant columns
6. Importing libraries for data visualisation
7. Creating of various "groupby" and filtered tables as well as charts in order to support our hypothesis and get insights

# User-built functions
1. clean_age() -> using RegEx to clean the values of column 'Age'
2. remove_until_number(s) -> using RegEx to clean values of column 'Date' to only keep numbers and remove non-numerical characters present before the date
3. extract_last_four_digits(date_str) -> extracting the year from a date
4. get_season(date_str) -> generating a season depending on the month
5. categorize_injury(injury) -> using RegEx to categorize the type of injury
6. correct_sex(value) -> using RegEx to clean the values of column 'Sex'
