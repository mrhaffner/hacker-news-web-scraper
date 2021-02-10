This is a web scraper built with python for the Zero To Mastery Course: The Complete Python Developer as part of a code along project.
This web scraper looks at the stories on the first two pages of Hacker News, and returns a list of dictionaries to the CLI. 
The dictionaries contain the title, numbers of votes, and story link. The list is sorted from most to least votes and ignores stories with under 100 votes.

In order to run this project, you will need to install the beautifulsoup4 and requests modules.