 coursera_capstone_project
 
Introduction
Objective

In this project, we will study area classification using Foursquare API data and ML segmentation and clustering. The aim of this project is to segment areas of Delhi and Mumbai based on the most common places captured from Foursquare in India.

Using segmentation and clustering, we hope we can determine:

the similarity or dissimilarirty of both cities classification of area located inside the city whether it is residential, tourism places, or others
Data

Data is acquired from following two -

-- For Mumbai (https://www.mapsofindia.com/pincode/india/maharashtra/mumbai/)

-- For Delhi (https://www.whatsuplife.in/delhi/blog/zip-pin-postal-code-pincodes-delhi/)

and these will converted to csv by parsing the html text

Data is in form of Area along with their Pincodes for each city. We will further fetch the lattitude and longitude for each areas and store to a DataFrame for analysis and also to a separate CSV file to avoid scrapping again.

This data (Area, Pincode, City, Latitude, Longitude) will be help to identify common places using FS API.

