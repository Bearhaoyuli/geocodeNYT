# Geocoding NYT articles using Python

This script automatted the process of geocode the article locations and map making process based on user inputted creterias 

Before this program can run, users should "pip install" a few modules that are not in the standard Python library. 

In order to do that, user should open up the start menu and search for CMD (for windows). 

After the command prompt is opened, user should navigate to the file path of where the "Scripts" folder is located for Python, in this should be pip.exe. This should be within the “Python27” folder. Copy this file path. 

Use the "cd" command to change the working directory and paste the file path mentioned above directly after the “cd” command in the command prompt. 
After the directory has been set up, users should use type "pip install *desired library*" to install the libraries that did not exist in the standard library or that are not already on your computer and are needed for our script to run.

These libraries include: "nytimesarticle", "geopy", "bs4","requests"

Users should also change the "inputWorkspace" and "folderPath" within the script to match where the project folder is located within their computer.  

Make sure to close the GUI window after the "success" message popped up in order for the script to continue running.

Links to the module documents: 
“Tkinter”: https://www.tutorialspoint.com/python/python_gui_programming.htm 

“requests”: https://github.com/kennethreitz/requests, http://docs.python-requests.org/en/master/

“json”: https://docs.python.org/2/library/json.html

“csv”: https://docs.python.org/2/library/csv.html

“os”: https://docs.python.org/2/library/os.html 

“nytimesarticle”: https://pypi.python.org/pypi/nytimesarticle/0.1.0

“articleAPI”: https://developer.nytimes.com/article_search_v2.json

“geopy”: https://geopy.readthedocs.io/en/1.11.0/

“HTMLParser”: https://docs.python.org/2/library/htmlparser.html

“bs4”: https://www.crummy.com/software/BeautifulSoup/bs4/doc/

