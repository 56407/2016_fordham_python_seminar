This repo corresponds to a Python seminar that was taught to students of a few different programs at the *Fordham Graduate School of Business* in October of 2016. 

The bulk of our time was spent working through a variety of technciques for data maniuplation in Pandas and as such, the materials here reflect that. Our coursework was broken up over four sessions in roughly the following way:

	1) Python fundamentals
	2) Python practice & Intro to Pandas
	3) Deeper into Pandas
	4) Heavy-duty data engineering in Pandas, with some light modeling at the end

**stock_csvs/** contains 500 csv files, each with daily stock price data for one of the 500 stocks in the S&P 500, with a date range of Jan 1998 - August 2013. Presumably, this is the data for the 500 stocks in the S&P 500 as of August 9th, 2013, where this data set ends. This was a free data set obtained from https://quantquote.com/historical-stock-data.

**ppts/** contains the powerpoint presentations delivered in class. Though these presentations generally did a pretty mediocre job of predicting what would take place in subsequent classes, they did stay pretty close to whatever was covered in their respective sessions.

**text_example/** contains a Jupyter notebook that walks through a practice example - searching for names in a text file using built-in Python data structures. This has a lot of notes around what is being done and why - a great place to start for someone interested in learning or refreshing on some of the Python fundamentals. 

**output/** contains output from some of the programs run. 

**code/** is where the bulk of the code lives. 
	
	-The module stock_data.py contains functions used for aggregating the 500 csv's into a workable format
	
	-The pandas_basics notebook provides a first look at DataFrames and columnar access
	
	-pandas_more takes things a little further, introducing heirarchical columns
	
	-correlation_fun is where things start to get a little more interesting. We take a look at some of the stocks whose returns were most correlated to 
	others'
	
	-build_tables is really the culmination of our data wrangling efforts - we compile both daily and monthly tables that provide a deeper look into a stock's price measures

Additionally, in code/, there lies:
	
	-The basic_examples Jupyter notebook, which provides some very intro-to-Python style activities
	
	-The additional_exercises folder, which contains on-the-fly exercises from class, some with solutions and others without
	
	-And lastly, the python_demo module - a less polished & heavily commented version of stock_data, sent out pre-seminar as glance into what one can do with Python

Some of the code we worked with during the seminar is not currently here. In the case of the feature_building module & notebook, this was replaced with build_tables. The modeling notebook has also been taken down. That is because it was quite frankly not very good. I am in the process of replacing this with a few new examples, having been chipping away at all the updates I've had floating around in my head since the seminar. This will go up sooner rather than later. I just want to make sure it is at least somewhat soild before posting. 

A few final details:
- This code was all written using Python 3.5 with Pandas as a heavy dependency. Some of this code will run in 2.7, (in fact most will) but there will be some issues
- I have not yet had a second set of eyes on a lot of these updates. That too is being worked on. In the meantime if you see anything out of line please let me know 

Thank you again for your participation in the seminar! 





