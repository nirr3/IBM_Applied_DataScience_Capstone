# IBM_Applied_DataScience_Capstone
A part of the IBM Applied Data Science Capstone on Coursera.



## Introduction:

This Repo was created to fullfil the requirements of the Applied Data Science Capstone offered through Coursera and verified by IBM. Like most Coursera courses and specializations, it requires a project to be submitted for peer review.



## IBM Applied Data Science Markdown.ipynb:

This python notebook was created to pull information from using FourSquare's API as a part of the first weeks homework. The section where the API Key and Secret needs to be enteres has been X:ed out. To be able to reproduce one would need to sign up for a free developer account here:
https://developer.foursquare.com/

## Toronto Webscraping with Foursquare


A pratice exercise built using a Python notebook to using k-means clustering, which is a form of unsupervised learning. It uses clustering and the Foursquare API to segment and cluster the neighborhoods in the city of Toronto. 
It also scrapes a wikipedia page and parse HTML code using the Python package Beautifulsoup, and convert data into a pandas dataframe that is ultimate used to define neighbourhoods for the clustering to be performed on.



## Empowering People to Negotiate a Better Auto Loan Rate.ipynb
This python notebook was created to explain my proposed capstone solution which leverages the Foursquare API to do GeoFencing for Lenders.


## Empowering People to Negotiate a Better Auto Loan Rate Github Notebook.ipynb


### Introduction to the Problem
A major concern for lenders is being left out of the conversation when a potential borrower talks to an autodealer. If lenders could be a part of the conversation the customers is having at the dealership, they could potentially help the customer by providing a lower cost service in the form of lower interest rate or lower payments. The problem is knowing when a person is actually at a car dealership.

In many cases the car-dealers are offering the person who is buying a car a loan and many insurance policies that are significantly marked-up. By enabling financial instutitions to understand when someone is at a car dealership, they are able to help reduce the borrowers total cost of ownership a lot and gives them a better negotiating position with the dealer.

## The Data
As a prototype, Foursquare location data will be used for the Chicago area. Using this information with some coordinate data, we will calculate the distance from the dealership and create a flag whether or not we believe this individual is at a car dealership.

We will also use data from a local csv file with examples of people, their location coordinates (longitude and latitude) and their email addresses.

### Methodology
We will use the foursquare data to gather auto dealership data. We will get a flat files (csv) with people data. In a commercial setting this could potentially come from the company's web development teams. If the company has a mobile app, they may already be capturing this information. We will use the flat file as a prototype.

Using the foursquare auto dealership data and the geopy library we will calculate the distance between each person's location and the dealership list. Anyone who is 100 feet away from the coordinates of the dealership will be included on our list being at the dealership


## Empowering PEOPLE TO NEGOTIATE A BETTER AUTO LOAN[1308].pptx

A PowePoint deck illustrating the problem, data being used, methodology and results of the GeoFencing exercise.




