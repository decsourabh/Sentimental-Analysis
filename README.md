# TwitterAnalysis

We are trying to Analyse Twitter Data which we are streaming using Apache Flume into HDFS.

We are using Twitter4j API of Flume to connect to streaming Data of Twitter


Pre-requisites:

1. All deamons are running.
2. Java, Flume and Hive is installed and configured.
3. metastore.db using Java 'Derby' in Embedded mode is configured. Other RDBMS like; MySQL can also be use.
4. Knowledge of Hadoop HDFS, Hive and Flume.


1. Setup Twitter account:

Setup Twitter application to get consumerKey and accessToken details.
Login/Open Twitter account.
Click on create app link.
Fill necessary details.
Enter full web site URL. Last forward slash (/) is required; otherwise it will not validate. Example; http://www.yahoo.com/
Accept the agreement and click on ‘create your Twitter application’.
Go to ‘Keys and Access Token’ tab.
Copy the consumer key and the consumer secret.
Scroll down further and click on ‘create my access token’.
Copy the Access Token and Access token Secret.
Note down all four key at some place, will need this in Flume config file.
