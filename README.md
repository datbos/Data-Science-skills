### Data-Science-skills
This Algorithm assembles job postings of a specified job title and scans the content for specific key job skill terms associated with job title to determin the frequency of term usage and associated "importance" of the skill. 
## Metrics
The individual skill terms are accumlated as per total number of job postings rather than total number of occurances to account for the multiple occurances in the same postings though still reflecting the added "importance" of repeated mention.

## Run parameters
- Job search title can be changed in the xxxxxx code block
- Job search city and state can be changed in the yyyyyyy code block
- Job search terms can be added or changed in the zzzzzzz code block

## Output 
- Number of job postings found and the corresponding number of pages
- Page count as job pages are processed
- Total rume time posted
- Plot of each search term in order of "importance"

## Modification
- improve runtime by changing NLP from NLTK to SpaCy algorithms
- Adjust for international searches

