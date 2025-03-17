# What Does the Current Movie Sequel Landscape Look Like?
Here's the roadmap:

### Gathering The Data 
I used The Movie Database (TMDB) free API to collect data on the top 25 movies of every year (since 1916). 

[Data Collection Code (Python)](TMDB_data_collection.ipynb)

There are two major CSV files that are outputs of this process:
* [top25_per_year.csv](top25_per_year.csv)
* [movies_in_specified_collections.csv](movies_in_specified_collections.csv)

From here, I brought this data into R. 

### Data Analysis and Visualization
[Data Analysis Code (R)](movie_sequels.Rmd)

Enjoy!
