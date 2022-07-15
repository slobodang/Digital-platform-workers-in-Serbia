# Digital-platform-workers-in-Serbia

RESEARCH GOAL 

Exploring the type, employer country and compensation of platform jobs done by Serbian freelancers

1. How many freelancers completed jobs on the platform?
2. What do they do?
3. How much do they earn?
4. Where are their employers from?
5. Are different types of jobs flowing in from different countries?

PROCESS

Getting links with Selenium: 

  Starting the chrome driver.
  Deselecting the online button.
  Iterating through all the profiles on all pages to obtain profile links from them.
  Saving profile links to a list.
  Only 1311 profile links obtained!

Scraping and parsing data:

  Downloading individual profiles.
  Parsing profiles with BeautifulSoup.
  Using BeautifulSoup to find data of interest in the html markup and save it in variables.
  Appending variables to a json file and later a pandas table.

FINDINGS

How many active freelancers are there across the professions?

![image](https://user-images.githubusercontent.com/109330145/179167492-68947c99-0654-4a49-9c5b-53d4165905f1.png)

Majority of registered users never had any jobs on the platform.
Most of the active freelancers are doing creative professions, software development and technology or clerical jobs.

How much do freelancers earn across the professions?

![image](https://user-images.githubusercontent.com/109330145/179167459-8cd12551-7192-44f9-bec8-488da5807c2f.png)

Median calculated only for those who have previous jobs.
Software development and technology and creative and design categories have the highest earnings.
Sales and marketing is calculated on basis of 3 cases so the figure is not representative.

Where are the jobs outsourced from?

![image](https://user-images.githubusercontent.com/109330145/179167427-9e688ea0-8171-42b3-aa68-8aa3cd2fb6f2.png)


Us employers most dominant.
High income anglophone countries the main employers.
Within country outsourcing also present.

Where are jobs outsourced from across professions?

![image](https://user-images.githubusercontent.com/109330145/179167274-8733ab2e-3314-469f-8b84-8779ff44b8c2.png)


Software and technology and Creative and design professions have similar employer origin countries.
Lower income countries dominate writing and translation.
Germany and Serbia overrepresented in Clerical and data entry professions.
Other two professions have too few active freelancers.





