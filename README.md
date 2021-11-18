# GEMINI API PROJECT
The following is an instructional overview of the GEMINI API Project

OVERVIEW:
The challenge this script sets out to overcome is the Price Deviation alert - Price Deviation - "Generate an alert if the current price is more than one standard deviation from the 24hr average"
The Script does the by accomplishing the following:
Pulls data from the Gemini API.
Converts the data into 2 different dataframes (std loss and std gain) via pandas.
Uses pandas specific methods to calculate the standard deviation.
Updates the dataframes to only inlcude those pairs which are 1 std above and below calculated value.
Uses seaborn to make thos pairs in easy to visualize graphs.
Performs info and error logging and saves it in a seperate file.

Included in the repository is:
A script for the API challenege.
An example of the log file produced.

IDE Recs + instructions:
To run this script I would suggest using the Jupyter IDE as I find it is the easiest to work with when utilizing data vizualzation modules as this script does!
Open the notebook in Jupyter, click on 'kernal', and select 'restart and run all'.
The script will run, and a logging file will populate on the main Jupyter file pag.

Further Improvements:
I'd like to have the 25th, 50th, and 75th percentile mapped out for the 24 hour % price change in a standard gaussian distribution model.

Other interesting checks I would like to implement:
I would like to answer all the questions in the project email including Price change and Volume deviation.
I would like to implement a single indepth data vizualization looking at all 3 of those metric. Possibly using a pairplot or another seaborne data viz option.
Exploring more advanced finance oriented statistical methods such as Monte Carlo would be exciting. 

Approach:
My approach for this task was to use data science oriented methods as opposed to traditional data processing.
I have worked with large data sets many times and the easier it is to comprehend and vizualize, for both non-technical and technical staff, the more effective it wil be at relaying information.

Time it took me to write this script:
I stopped at about 4 hours per instructions.









