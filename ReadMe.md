# Read Me
The purpose of this file is to overview how to navigate the EPA's data API known as the Air Quality System (AQS).  

The homepage for the AQS can be found here: https://aqs.epa.gov/aqsweb/documents/data_api.html

The AQS API works by sending requests via any web browser (i.e. chrome, firefox).  
Once the request is recieved the API will send a response / data to the html page from which the request was issues.
So all you need to do is enter a line of code with the appropriatly structured request into the address bar of a web browser and wait for the data.
Details of how to strucutre the request are below

# Request at a structure
https://aqs.epa.gov/data/api/sampleData/bySite?email=ryan.bares@utah.edu&key=tauperam29&param=42401&bdate=20181201&edate=20181230&state=49&county=035&site=3006

If you were to use the above request you would get CO data (param=42401) for the enitre year of 2018 (bdate=20181201, edate=20181230) from DAQ Hawthorne (site=3006).  Note that the email is registered to my utah.edu account, which was issues the key (token) tauperam29.  To register your email and get a key specific for your uses follow the steps below.


# STEP 1: Set up a user name and get a key (token)



# API Structure


# Common Paramaters for Air Quality Data

Species                      | Paramater Code
-----------------------------|----------------------------------
Carbon Monoxide (CO)         |
Nitrogen Oxide (NO)          | 
Nitrogen Dioxide (NO2)       | 
Oxides of Nitrogen (NOx)     |

# Common Paramaters for Air Quality Data



