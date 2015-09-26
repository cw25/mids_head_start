## Storing and Retrieving Data

_No one really knows what this course is about because it has been changed multiple times since creation._

Data comes in many forms, usually broken into two categories; structured, like a spreadsheet or a relational database; unstructured, like comments on the web or health records between different hospitals.

Big data comes in multiple flavors, usually a combination of V's.
**__Velocity__** a.k.a. the firehose; sensor data is a good example, or twitter stream.
**__Volume__** changes each year relative to user and new technology, but generally anything that takes a lot of planning and design to figure out how to store, move, or process the amount of data. 
**__Variety__** means the type of data or range of possible formats changes frequently or makes it hard to join to other data sets.
**__Varacity__** includes concerns about whether the data was collected properly or can be readily accessed.

As a data scientist, you'll need to know how to get data, put it some place, clean it up and hook it up with other data. This course should prepare you do those tasks in an efficient, programmatic manner. The more you learn to automate data preparation and manipulation tasks, the more time you get to spend on the analysis and presentation pieces.

## Resources:

**Basics like Terminal and Python**
- Command Line Crash Course, be prepared... http://cli.learncodethehardway.org/book/
- Think Python: How to Think Like a Computer Scientist, free e-book and great intro to python. http://www.greenteapress.com/thinkpython/html/index.html
- Data Science Tookbok, a virtual environment for data science that you can have up and running quickly. **__Use this if you are on Windows.__** http://datasciencetoolbox.org/

**Relational Databases**
- PostgreSQL vs Microsoft SQL Server, a crazy person rant that explains a lot about how features you want in a relational database. http://www.pg-versus-ms.com/
- Use the Index Luke, a free e-book on why indexes help SQL and how to create them. http://use-the-index-luke.com/sql/preface

**Data Transformation in Python**
- Learn Pandas, the python library for dataframes and data analysis. https://bitbucket.org/hrojas/learn-pandas
- Online JSON Viewer, so you know the format is valid. http://jsonviewer.stack.hu/
- Regular Expressions Quickstart. Usually called regex, a standard library in python called `re` and generally good way to do pattern matching. http://www.regular-expressions.info/quickstart.html
- Readable regex in python, http://tonysyu.github.io/readable-regular-expressions-in-python.html#.VgZakSBVhBe

**MapReduce**
- MapReduce, slides from Google research authors. http://research.google.com/archive/mapreduce-osdi04-slides/index.html
- Hadoop, an open-source Apache project for distributed data processing. https://hadoop.apache.org/
- Spark, an open-source Apache project for fast, large-scale data processing. http://spark.apache.org/
- mrjob and S3 tutorial. mrjob is python library for writing MapReduce functions. S3 is Amazon cloud object storage. https://www.classes.cs.uchicago.edu/archive/2013/spring/12300-1/labs/lab5/
- Word Count MapReduce example using local and EMR, http://www.lichun.cc/blog/2012/06/wordcount-mapreduce-example-using-hive-on-local-and-emr/
- Guide to Setting Up a cluster of virtual machines running Hadoop and Spark. https://github.com/dnafrance/vagrant-hadoop-spark-cluster
- Hortonworks Sandbox, tutorials for getting started with Hadoop. http://hortonworks.com/products/hortonworks-sandbox/#tutorial_gallery

**Natural Language Processing**
- NLTK, python Natural Language Toolkit, a library for processing textual data. http://www.nltk.org/
- TextBlob, a python library that makes processing textual data even easier than NLTK. https://textblob.readthedocs.org/en/dev/
- Whoosh! An embedded search engine written in python. http://sowingseasons.com/blog/introduction-to-whoosh.html
- Audiogrep, a python library that transcribes audio files and helps you search them. https://github.com/antiboredom/audiogrep

**Web Scraping**
- BeautifulSoup, a python library to get data out of webpages. http://www.crummy.com/software/BeautifulSoup/
- lxml, python library for working with XML and HTML. https://github.com/lxml/lxml/
- Scrapy, the basics. A python library that lets you "scrape" webpages. https://seanmckaybeck.com/scrapy-the-basics.html
- Grab, an alternative to Scrapy. http://docs.grablib.org/en/latest/
- Mechanize, a python library to build programmatic web browsing bots. https://pypi.python.org/pypi/mechanize/

**NoSQL databases**
- Comparison of NoSQL Options, with features and best use cases. http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis
- MongoDB, an open-source BSON (binary JSON) data storage application. https://docs.mongodb.org/manual/?_ga=1.138812147.1950857371.1443257647
- Cassandra, an Apache open-source project offering great performance. http://cassandra.apache.org/
- Neo4j, graph database, useful for mapping relationships like in a network. http://neo4j.com/