# Reviews from Bo

## Reproducibility report
It is quite convenient to reproduce the project since I only had to change 1 line (to change the directory to my local path) in that file to run the code and to get the same result.

## Overall opinion
- Reproducibility: See 'Reproducibility report';
- Clean documentation: The raw data has been isolated so that it won't be changed after the analysis; 
- Coding style: All the variables are named in a clear way, and Feya has commented basically every logical step in
the code;
- Use of git: There are over 10 records of commit to properly show Feya's ideas during the process.

## Suggested improvements
- df["median_price"] = "median_price" this line is giving the string 'median_price' as the value to the column, not the values of the variable 'median_price', even though this column doesn't affect the final output;
- In the 'README.md' or 'analysis.ipynb', there is no indication about on what version of Python should the reproducer run the analysis;
- There 2 files named as 'README' in this project. Maybe the contents could be combined into one file to avoid confusion.

