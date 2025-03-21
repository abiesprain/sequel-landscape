# What Does the Current Movie Sequel Landscape Look Like?
If you haven't already, check out the YouTube video to this story [here](https://youtu.be/RzOZ_-lTkhA).

### Gathering The Data 
I used The Movie Database (TMDB) free API to collect data on the top 25 movies of every year (since 1916). 

[Data Collection Code (Python)](TMDB_data_collection.ipynb)

There are two major CSV files that are outputs of this process (or if you just want to skip to the R code you can download them):
* [top25_per_year.csv](top25_per_year.csv)
* [movies_in_specified_collections.csv](movies_in_specified_collections.csv)

From here, I brought this data into R. 

### Data Analysis and Visualization
[Data Analysis Code (R)](movie_sequels.Rmd)

By the end, you'll have two CSV outputs of this process:
* [top25_final.csv](top25_final.csv) (If you want to just explore the data I would download this)
* [blender_csv.csv](blender_csv.csv) (This is the data needed for visualizing in Blender)

### Visualization in Blender
[Blender Code (Python)](blender_code)
You'll use this, along with [blender_csv.csv](blender_csv.csv) to create a "city of sequels"

Enjoy!
