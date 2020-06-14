# robo_advisor
# Project Title: 
Robo Advisor Guided Project
 
# Getting Started: 
Create a repo on GitHub such as "robo_advisor".  Add a README.md file, Python gitignore, and MIT # LICENSE.

Clone the repo onto GitHub Desktop.

From GitHub Desktop, open Visual Code Studio, create a folder titled app and within create a .py file (such as robo_advisor.py) and copy your items into the .py file:

print("-------------------------")
print("SELECTED SYMBOL: XYZ")
print("-------------------------")
print("REQUESTING STOCK MARKET DATA...")
print("REQUEST AT: 2018-02-20 02:00pm")
print("-------------------------")
print("LATEST DAY: 2018-02-20")
print("LATEST CLOSE: $100,000.00")
print("RECENT HIGH: $101,000.00")
print("RECENT LOW: $99,000.00")
print("-------------------------")
print("RECOMMENDATION: BUY!")
print("RECOMMENDATION REASON: TODO")
print("-------------------------")
print("HAPPY INVESTING!")
print("-------------------------")

Create a requirements.txt file and paste the below items within the file:
requests
python-dotenv
 
 Open GitBash from GitHub Desktop

# Installing:
An Anaconda virtual environment will need to be set up.  Within GitBash type:

   conda create -n stocks-env python=3.7 # (first time only)

    conda activate stocks-env

Also install the packages within the requirements.txt file:

    pip install -r requirements.txt

To test the virtual environment, run the above given script by typing within GitBash:
python robo_advisor.py
 
# Running the tests:

To run the test, ________

# Built With:
Python

Anaconda

Visual Studio Code

# Versioning:
GitHub Desktop used for versioning.

For the versions available, see the tags on this repository.

# Authors:
prof-rossetti - Initial work and provided guided project

jkg363 - Completed guided project

# License:
This project is licensed under the MIT License - see the LICENSE.md file for details

# Acknowledgments:
Guided project by: prof-rossetti

SOURCE: https://github.com/prof-rossetti/intro-to-python/tree/master/projects/robo-advisor

# README.md Template from:
SOURCE: README-Template.md https://gist.github.com/PurpleBooth/109311bb0361f32d87a2