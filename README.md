# innovation
All the innovation and POC projects are placed in this location

This is a open source software build for solving issues in QA. There is no warranty or gaurantee for using this software.

There is a document which details tools configuration and documentation in order to perform Monitoring and Dashboarding with Open source tools ELK or known as Elastic Stack.

ELK is Elastic Search - Logstash  - Kibana :

Elastic Search:

Elasticsearch is the distributed search and analytics engine at the heart of the Elastic Stack. Logstash and Beats facilitate collecting, aggregating, and enriching your data and storing it in Elasticsearch. Kibana enables you to interactively explore, visualize, and share insights into your data and manage and monitor the stack. Elasticsearch is where the indexing, search, and analysis magic happen.

Elasticsearch provides real-time search and analytics for all types of data. Whether you have structured or unstructured text, numerical data, or geospatial data, Elasticsearch can efficiently store and index it in a way that supports fast searches. You can go far beyond simple data retrieval and aggregate information to discover trends and patterns in your data. And as your data and query volume grows, the distributed nature of Elasticsearch enables your deployment to grow seamlessly right along with it.

Elasticsearch offers speed and flexibility to handle data in a wide variety of use cases:

1. Add a search box to an app or website
2. Store and analyze logs, metrics, and security event data
3. Use machine learning to automatically model the behavior of your data in real time
4. Automate business workflows using Elasticsearch as a storage engine
5. Manage, integrate, and analyze spatial information using Elasticsearch as a geographic information system (GIS)
6. Store and process genetic data using Elasticsearch as a bioinformatics research tool


Data in: Documents and Indices:

Elasticsearch is a distributed document store. Instead of storing information as rows of columnar data, Elasticsearch stores complex data structures that have been serialized as JSON documents. When you have multiple Elasticsearch nodes in a cluster, stored documents are distributed across the cluster and can be accessed immediately from any node.

When a document is stored, it is indexed and fully searchable in near real-time—​within 1 second. Elasticsearch uses a data structure called an inverted index that supports very fast full-text searches. An inverted index lists every unique word that appears in any document and identifies all of the documents each word occurs in.

An index can be thought of as an optimized collection of documents and each document is a collection of fields, which are the key-value pairs that contain your data. By default, Elasticsearch indexes all data in every field and each indexed field has a dedicated, optimized data structure. For example, text fields are stored in inverted indices, and numeric and geo fields are stored in BKD trees.

Ultimately, however, you know more about your data and how you want to use it than Elasticsearch can. You can define rules to control dynamic mapping and explicitly define mappings to take full control of how fields are stored and indexed.

Defining your own mappings enables you to:

1. Distinguish between full-text string fields and exact value string fields
2. Perform language-specific text analysis
3. Optimize fields for partial matching
4. Use custom date formats
5. Use data types such as geo_point and geo_shape that cannot be automatically detected


Data out: Search and Analyze

Elasticsearch provides a simple, coherent REST API for managing your cluster and indexing and searching your data. For testing purposes, you can easily submit requests directly from the command line or through the Developer Console in Kibana. From your applications, you can use the Elasticsearch client for your language of choice: Java, JavaScript, Go, .NET, PHP, Perl, Python or Ruby.

Searching your Data:

The Elasticsearch REST APIs support structured queries, full text queries, and complex queries that combine the two. Structured queries are similar to the types of queries you can construct in SQL. For example, you could search the gender and age fields in your employee index and sort the matches by the hire_date field. Full-text queries find all documents that match the query string and return them sorted by relevance—how good a match they are for your search terms.

Analyzing your data:

Elasticsearch aggregations enable you to build complex summaries of your data and gain insight into key metrics, patterns, and trends.
Because aggregations leverage the same data-structures used for search, they are also very fast. This enables you to analyze and visualize your data in real time. Your reports and dashboards update as your data changes so you can take action based on the latest information.


