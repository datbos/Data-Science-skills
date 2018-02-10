## Data-Science-skills
![Datbos logo](logo.png)
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

