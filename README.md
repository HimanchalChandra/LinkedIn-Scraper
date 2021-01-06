# LinkedIn-Scraper

The objective of this project was to explore the data related job market and it's requirements
within the industry.More particularly within the company Uber. Also, I wanted to gain more knowledge and experience in web-scraping.

LinkedIn is an American company established in 2002. They created a platform for the social media of professional networking. This platform is mainly used for professional networking which includes employers posting jobs and job seekers posting their resumes or CVs. Eventually most of LinkedIn's revenue started coming from selling access to information about its members to recruiters and sales professionals.
As of 2019, LinkedIn has 610 million registered members in 200 countries. Of these users more than 250 million are active.

The project is divided into three parts:

## 1. Profile Scraper:
I used selenium and beautiful soup to web-scrape Uber's LinkedIn profile. I created a pandas table which consisted of the scraped
information such as employees name, job title, location, and the profile link to the current employee's profile. Then saved the outputs to a csv file. The code for this part is in "LinkedInScraper.py".


## 2. CSV Scraper:
Once the cvs file was created, I started another scraping process which consisted of scraping the output cvs file from the previous scrape
that went into each profile link to grab the information needed for my analysis. This second scrape included information from each employee's experience,
education, and skills. Once I was able to retrieve this information I was able to narrow the results down to only "data scientists" type roles. Once I was able to 
narrow down only to data scientist type roles under the Uber company I was able to make the observations needed to make my conclusions. The code for this part is in 
"ProfileScraper.py".

## 3. Data Analysis:
I ran my analysis on about 1,000 employee profiles. The analysis code is in the Jypyter python notebook "DataAnalysis.ipynb".

## Libraries Used:
1. Selenium
2. BeautifulSoup
3. Pandas
4. Matplotlib
