# SQL-on-Cassandra-with-Open-Source-Notebooks

Introduction to a few open source notebooks that can be used to do SQL and joins on [Cassandra](https://cassandra.apache.org/), a NoSQL database. We cover [Jupyter](https://jupyter.org/), [Zeppelin](https://zeppelin.apache.org/), [Quix](https://github.com/wix/quix), and [Polynote](https://polynote.org/), with live demos of Jupyter (using [Spark](https://spark.apache.org/) + Cassandra) and Quix (using [Presto](https://prestodb.io/) + Cassandra)

## Accompanying Materials
- [Blog](https://blog.anant.us/open-source-notebooks-and-cassandra-doing-sql-on-cassandra-tables/)
- [Webinar](https://youtu.be/i0LNtBEtm8g)
- [Slideshare](https://www.slideshare.net/AnantCorp/webinar-open-source-notebooks-and-cassandra)
- Doing SQL and Reporting on Apache Cassandra with Open Source Tools Series:
  1. [Presto and Cassandra](https://blog.anant.us/presto-and-cassandra/)
  2. [Spark and Cassandra](https://blog.anant.us/spark-and-cassandra-sql-on-cassandra/)
  3. [Open Source Notebooks and Cassandra](https://blog.anant.us/open-source-notebooks-and-cassandra-doing-sql-on-cassandra-tables/)

## [Quix Notebook](https://github.com/wix/quix)
- No importable/exportable notebooks currently
- Will be using queries that are available in the `Code.txt` file [here](https://drive.google.com/file/d/1FMxHAOeDaRhn4jvmQV4JNgNz7POp4L6j/view). Live instructions can be seen in the webinar linked above.


## [Jupyter Notebook](https://jupyter.org/)
- [Notebook For Demo](https://github.com/adp8ke/SQL-on-Cassandra-with-Open-Source-Notebooks/blob/master/Spark%20%2B%20Cassandra%20%2B%20Jupyter%20Notebook%20-%20Doing%20SQL%20on%20Cassandra%20with%20Jupyter.ipynb)

## [DataStax Studio](https://www.datastax.com/dev/datastax-studio) for creating demo keyspace, creating tables, and seeding tables
- [Notebook For Demo](https://drive.google.com/file/d/1FMxHAOeDaRhn4jvmQV4JNgNz7POp4L6j/view)
- If using CQLSH vs DataStax Studio Notebook, then you can still take the notebook above and use the CQL commands and queries in the `Code.txt` file
