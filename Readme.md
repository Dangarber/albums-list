# Album List

## Installation
I am using Python verison 3.10.7,
i also used pandas and matplotlib

To you can install those individually, or copy my whole environment with the command  
```
pip install -r requirements.txt
```
## Read Data in

*Read in data from rollingstones top albums of all time list. Shown here as "albumlist.csv
Used function full_file = pd.read_csv("albumlist.csv", encoding='latin-1',)
## Manipulate and Clean Your Data
I used drop(columns=["Subgenre"]) to clear up a column I didn't need. I also removed the extra genre's listed after the first comma in the column "genre".
## Analyze
I used these functions to break down my data into useful information. Each reason why is listed in the Markdown's in my AlbumList.ipynb file. These functions are, len, .groupby, .count, .nlargest, .nsmallest, 
## Visualize Your Data
I made two graphs bar and pie. What insight they give is listed in the markdown above each one.
## Interpret Your Data
The indepth interpretation of the my project in on the very last markdown. 