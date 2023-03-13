# salesforce-marketing-cloud

This script reads a list of website URLs from a CSV file, sends HTTP requests to each website, and searches for specific keywords in the HTML content of each website. The keywords used are related to email marketing, digital marketing, newsletters, marketing automation, and Salesforce Marketing Cloud. If a keyword is found in the HTML content of a website, the script prints a message indicating that the website may be a good potential customer for Salesforce Marketing Cloud based on that keyword. The script requires the `requests` and `BeautifulSoup` libraries to be installed in Python. The CSV file should have one URL per line.

Example output:

```
http://www.example.com may be a good potential customer for Salesforce Marketing Cloud based on the keyword 'newsletter'.
http://www.exampleone.com/ may be a good potential customer for Salesforce Marketing Cloud based on the keyword 'digital marketing'.
http://www.exampleone.com/ may be a good potential customer for Salesforce Marketing Cloud based on the keyword 'newsletter'.
http://www.exampletwo.com may be a good potential customer for Salesforce Marketing Cloud based on the keyword 'newsletter'.
http://www.examplethree.com may be a good potential customer for Salesforce Marketing Cloud based on the keyword 'digital marketing'.
```
