# IndeedJobScraper
Web scraping jobs with the keyword "Python Developer" from the popular job listing platfrom  "indeed.com" (indian servers)  
Used python for the same. I tried to use the Request library only at first but kept getting 403 errors due to the robust security of Indeed, so had to use an API for getting the html code.  
API used was scrapingDog.  
Used beautifulSoup4 for parsing the code and extracting the required tags and text.  
Made dataframes using pandas and calculated the average salary for my hometown - Indore using numpy.  
The scraped and extracted data is stored in the form of a csv file in the same repository.

