## Natural Language Processing (NLP) for Data Science Desired Skills
<!---[![Gitter](https://badges.gitter.im/DLTK/DLTK.svg)](https://gitter.im/DLTK/DLTK?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Coverage Status](https://coveralls.io/repos/github/DLTK/DLTK/badge.svg?branch=master)](https://coveralls.io/github/DLTK/DLTK?branch=dev)
[![Build Status](https://travis-ci.org/DLTK/DLTK.svg?branch=master)](https://travis-ci.org/DLTK/DLTK)--->

![Datbos logo](logo.png)

Data Science Skills notebook is a jupyter notebook written in python 2.7 to data mine internet postings of "Data Science" job positions for a given city and count the number of times given data science skill terms appear over all job postings.

The Natural language processing (NLP) uses BeautifulSoup for HTML parsing and NLTK is used for stopword filtering and word tokenizing. 

The goal is to provide information on which tool are most utilized or desired by the community not necessarily the state of the art methods and models and to determine which areas to focus on for joining the research in the data science field.

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
