# frequent_use
For google_analytics_api:
From Mark Kindem:

1. Gain access to Google Analytics via the auto-link Sabrina ‘sent’ you.
2. Go to Google Developer Console and follow these instructions so you can establish an API with the tool (These instructions are a little dated, but should more or less get you there: https://www.jcchouinard.com/how-to-use-google-search-console-api-with-r/)
3. In your Anaconda environment, install the ‘r-rgoogleanalytics’ and ‘rpy2’ packages if you don’t have them already. 

Basically I punted on trying to write code in python, and instead just used the R Code I already had and used the rpy2 package to allow me to run it (and create pandas dataframes!) in python.

os.environ['R_HOME'] = r'C:\Program Files\R\R-3.6.1' << find your R executable
