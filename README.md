# CD-GA-PPS-122-Final

This the repo for Cam Dublin's final project of the GA-PPS-122 course.

## Problem Statement

In this project, I will solve for a real life problem that we all face.. what am I going to wear today?!

This will be a very high-level outfit suggestion generator and to show the ability of this code, I will be using a sample clothing dataset from kaggle.com. The purpose of this code will be to extract a few different clothing items dependant on the provided input factors and give prospective clothing combinations. 

Also we will create visual representations to highlight popularity of clothing labels and their respective average pricing, as well as showcase the pricing disparity based on gender

## Solution

Create code that will be able to generate an outfit using the provided dataset, `clothing_catalog.csv`. We have this database that provides various types of men's, women's, and unisex clothing. We will also be using data visualization to depict some of the trends amongst these items and pricing implications based on different scenarios 

This will be iterating over multiple clothing items through calculating thir price in USD, converting the clothing based on type and then costruction a set of oufits depending on inputs on quantity and other qualities. We use for loops to iterate through the dataset and assign clothing types and then construct outfits using that logic