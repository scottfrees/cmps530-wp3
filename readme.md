# Weekly Project 3
This week we are using the same project from last week's analysis of movie data - with some twists.

- Instead of using a dictionary to represent an individual Movie, create a Movie class.  You'll still have a dictionary of Movie classes (rather than a dictionary of dictionaries).
- Instead of working on the project as one long executable script, use a Jupyter notebook, and separate your data loading/cleaning/organizing, and each analysis, into individual cells.
- Instead of outputting to CSV files, display results in Jupyter instead, as nicely formatted tables
  - You can leave out tags when outputting the results of the last analysis (frequently rated movies), since those are so lengthy.
  - Skip outputting JSON in the frequently rated movies as well.

*This project is not graded*

## The Data
The same data is used for this project as last week's.  DVC is already set up for you - just do a typical `dvc pull`.

## Use a Jupyter Notebook
I have provided a single Jupyter Notebook, with a cell to load the `movies.csv` file and output the count of movies.  This is just an example of opening a file in Jupyter - feel free to remove it.

Launch the notebook `jupyter notebook` and select `wp3.ipynb`.

Your notebook should not be one giant Python cell.  I recommend the following:
1. A cell at the top containing your class definition, and any critical initialization / package installation.
2. A cell to load your dictionary of movie objects
2. A cell to compute Number of Genres
3. A cell to compute Top Rated Tags
4. A cell to compute  Frequently Rated Movies