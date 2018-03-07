## Data-Science-skills
![Datbos logo](logo.png)
# 
# MNIST distributed training with TensorFlow  

## Contents

1. [Background](#Background)
1. [Setup](#Setup)
1. [Data](#Data)
1. [Train](#Train)
1. [Host](#Host)
1. [Predict](#Predict)


## Background

The **SageMaker Python SDK** helps you deploy your models for training and hosting in optimized, productions ready containers in SageMaker. The SageMaker Python SDK is easy to use, modular, extensible and compatible with TensorFlow and MXNet. This tutorial focuses on how to create a convolutional neural network model to train the [MNIST dataset](http://yann.lecun.com/exdb/mnist/) using **TensorFlow distributed training**.


This algorithm assembles job postings of a specified job title and scans the content for specific key job skill terms associated with job title to determine the frequency of term usage and associated "importance" of the skill. 
### Metrics
The individual skill terms are accumlated as per total number of job postings rather than total number of occurances to account for the multiple occurances in the same postings though still reflecting the added "importance" of repeated mention.

### Run parameters
- Job search title can be changed in the Job URL List code block
- Job search city and state can be changed in the Execution code block
- Job search terms can be added or changed in the Key Search Term code block
  * prog_lang_dict
    * R, Python, Java, C++, Ruby, Perl, Matlab, JavaScript, Scala
  * analysis_tool_dict    
    * Excel, Tableau, D3.js, SAS, SPSS, D3
  * hadoop_dict,
    * Hadoop, MapReduce, Spark, Pig, Hive, Shark, Oozie, ZooKeeper, Flume, Mahout
  * database_dict ,
    * SQL, NoSQL, HBase, Cassandra, MongoDB

### Output 
- Number of job postings found and the corresponding number of pages
- Page count as job pages are processed
- Total rume time posted
- Plot of each search term in order of "importance"

### Modification/Improvements
- improve runtime by changing NLP from NLTK to SpaCy algorithms
- Adjust for international searches
- integrate into Docker and flast for integrated independent execution

