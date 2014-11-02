# crawler.py

This is a python script that crawls the Daily Mail website for headlines, you can set the initial and end date.

## Usage:

1. create a virtual environment
2. `pip install -r requirements.txt`
3. edit crawler.py line [#9](https://github.com/bertez/small-projects/blob/master/dailymail-crawler/crawler.py#L9) to set the date limit (default is six months so the headlines.json will be ~18Mb)
4. `python crawler.py` and wait

The script generates *headlines.json*. 
