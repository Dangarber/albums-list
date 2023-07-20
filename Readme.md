# Album List

## Installation
I am using Python verison 3.10.7,
i also used pandas and matplotlib

To you can install those individually, or copy my whole environment with the command  
```
pip install -r requirements.txt
```
## Read Data in
 I loaded in two seperate data file's having to accout for some latin characters. I loaded in rolling stone's top 500 album list and ratemymusic.com top 5000 rated albums. 
## Manipulate and Clean Your Data
I cleaned some data by renaming some columns in Rate_My_Music to match some columns in Rolling_stone for and easier merge. I dropped one Genre since both list has one that doesn't match up will. I then had to rename one of the columns from Genre_x to just Genre. 
## Visualize Your Data
I made 3 graphs. Two Bar, One Scatter.


## Data Dictonary

Column Name       | Description
------------------|--------------------------------------------------------------------------------------------------------
Number            | An identifier for each record in the dataset.
Year              | The year in which the album was released.
Album             | The name of the music album.
Artist            | The artist or band who created the album.
Genre             | The main genre of the music album.
Ranking           | Where the album ranked on Ratemymusic.com top 5000 albums.
Release Date      | The exact date on which the album was released.
Descriptors       | Keywords or phrases describing the album's characteristics, style, themes, etc.
Average Rating    | The average rating given to the album by the users on ratemymusic.com
Number of Ratings | The total number of ratings received for the album.
Number of Reviews | The total number of reviews written for the album.