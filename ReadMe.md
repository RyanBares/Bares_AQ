# Read Me
The purpose of this file is to overview how to navigate the EPA's data API known as the Air Quality System (AQS).  

The homepage for the AQS can be found here: https://aqs.epa.gov/aqsweb/documents/data_api.html

The AQS API works by sending requests via any web browser (i.e. chrome, firefox).  Once the request is recieved the API will send a response / data to the html page from which the request was issues.So all you need to do is enter a line of code with the appropriatly structured request into the address bar of a web browser and wait for the data.

# Request Example
https://aqs.epa.gov/data/api/sampleData/bySite?email=ryan.bares@utah.edu&key=tauperam29&param=42401&bdate=20181201&edate=20181230&state=49&county=035&site=3006

If you were to use the above request you would get CO data (param=42401) for the enitre year of 2018 (bdate=20181201, edate=20181230) from DAQ Hawthorne (site=3006) located in Salt Lake County (county=035), Utah (state=49).  Note that the email is registered to my utah.edu account, which was issues the key (token) tauperam29.  To register your email and get a key specific for your uses follow the steps below.


# STEP 1: Set up a user name and get a key (token)
Open a web broswer and enter the following command into the address bar:
https://aqs.epa.gov/data/api/signup?email= **myemail@example.com**

Replace "myemail@example.com" with the email address you want associated with your key.  The API will return a message informing you that the request was recieved and a key will be sent to the email you entered.  

The key they send you will be used in all subsequent data requests.  If you loose it you can always request a new one.

In the example request used in the "Request Example" section above you can see the email (email=ryan.bares@utah.edu) and the key (key=tauperam29) are two of the first user variables you input. 


# API Structure


# Common Paramaters for Air Quality Data

Species                      | Paramater Code
-----------------------------|----------------------------------
Carbon Monoxide (CO)         |
Nitrogen Oxide (NO)          | 
Nitrogen Dioxide (NO2)       | 
Oxides of Nitrogen (NOx)     |

# Common Paramaters for Air Quality Data



