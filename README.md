# Netflix - Save Excel Spreadsheet to Text File

This will read in a spreadsheet containing a list Netflix Movies and TV Shows into a pandas dataframe.

It will then format the data in the dataframe as follows:
- Show ID: Remove S and add Leading Zeroes
- Date: Format to YYYY-MM-DD
- Type: Convert to Upper Case
- Remianing Fields: Remove any characters over the specified limit

After that it will create 2 new Dataframe based on the original but will filter them by Type (Movie & TV Show).
Then using numpy save the results of each of these new dataframes to a text file.
