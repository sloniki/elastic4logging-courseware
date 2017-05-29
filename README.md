# Elastic for Logging #

## Description ##
Elastic Search has become a favorite in the realm of search engines by broadening its scope and ease-of-adoption  
Easy to use for any developer combined with powerful query language made Elastic Search an attractive choice for agile teams  
Automatic sharding, replication, and healing makes Elastic Search rewarding to configure and to operate for system administrators  
Filebeat and Logstash for data ingest makes Elastic product suite appealing for logs processing and aggregation  
Kibana rich Search and Dashboard cababilities facilitates logs monitoring and processing  
Watcher in X-Pack streamlines alerting and discovery of trends and/or abnormalities


## Audience ##
* Developers who wants to be familiar with NoSQL Databases and with modern Search Engines
* Operations and DevOps looking for a way to monitor logs and to react to abnoramlities
* Architects who are familiar with Relational Data Modeling, but who have little experience with new Polyglot Persistence model

## Course's Objectives ##
* Bring Elastic Search novices to the level where they would feel familiar with installing, configuring and using Elastic products
* Explore ElasticSearch Dsl: query, filter, and aggregation
* Install and configure Logstash and Filebeat for logs ingest 
* Install and configure Kibana for data analysis
* Setup X-Pack and Watcher for Alerting

## Prerequisites ##
* Recent hands-on experience with Linux bash terminal
* Familiarity with JSON and logs data formats
* Recent administrative and troubleshooting experience on Linux OS
* Scripting and/or programming hands-on recent experience

## Outline ##
### Introduction ###
* Terminology, basic concepts, implementation, setup, and basic operations
* Data modeling with ElasticSearch
* Distributed database architecture
* Understanding ElasticSearch cluster, shards, and replicas
* Analysis of mappings, indexing, and their operations

### Search, Filter and Aggregation Dsl ###
* Understanding search Query DSL
* Overview of Filter DSL compared to Query DSL
* Syntax for Aggregation Queries

### Kibana ###
* Setup and configuration
* Discover
* Visualize
* Dashboard

### Logstash ###
* Setup and initial configuration
* Configuring logs transformation
* Using Kibana to visualize logs data

### Filebeat ###
* Setup and initial configuration
* Sending logs to Elastic Search using Filebeat
* Using Kibana to visualize logs data

### Watcher ###
* Setup and configuration
* Setting up alarms and notificaitions

### Preparing for Production ###
* Discussion on capacity planning and data population
* Performance tuning and monitoring
* Aws hosted Elastic Search