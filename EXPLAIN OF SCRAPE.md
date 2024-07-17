# scripting the providee website

The task is to scrape the website "https://hprera.nic.in/PublicDashboard" to get a list of the first 6 projects under the "Registered Projects" heading. For each project, we need to extract the following details from their detail pages:
There are :

GSTIN No
PAN No
Name
Permanent Address

The Approach Method are :-

There are totally 4 steps to Scripting a website are:
1.Access the website: By using the php pandas selenium webdriver_manager thta are to handle dynamic content and navigate to the 'Registration Project' sections.
2.Extract The Project Link: To extract we firstly should find the link of 6 projects abd 
3.Extract Project Details : we should to view the detail page section and also scrape the required information.
4.Save Data: should store the scarped data in csv file .

we also required libraries like 
requests, beautifulseup4,pandas and selenium.
 and also install the php required driver_manager 

Output explination :-

By using the Python code we do the scripting the website and those it will create the file name "project_details.cvs" in cvs file formate in same directory,which contain the details of the 6 projects under the Registered Projects heading

note 
make sure to install the Google chorm and as we use script for ChromeDriver for Selenium (webdriver_manager)
