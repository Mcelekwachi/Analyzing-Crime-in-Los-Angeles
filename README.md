# Analyzing-Crime-in-Los-Angeles
Support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. 
Los Angeles, California 😎. The City of Angels. Tinseltown. The Entertainment Capital of the World!

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where you can help!

You have been asked to support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. They plan to use your insights to allocate resources effectively to tackle various crimes in different areas.

The Data
They have provided you with a single dataset to use. 
It is a modified version of the original data, which is publicly available from Los Angeles Open Data.

Column	Description
'DR_NO'	Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.
'Date Rptd'	Date reported - MM/DD/YYYY.
'DATE OCC'	Date of occurrence - MM/DD/YYYY.
'TIME OCC'	In 24-hour military time.
'AREA NAME'	The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example, the 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles.
'Crm Cd Desc'	Indicates the crime committed.
'Vict Age'	Victim's age in years.
'Vict Sex'	Victim's sex: F: Female, M: Male, X: Unknown.
'Vict Descent'	Victim's descent:
A - Other Asian
B - Black
C - Chinese
D - Cambodian
F - Filipino
G - Guamanian
H - Hispanic/Latin/Mexican
I - American Indian/Alaskan Native
J - Japanese
K - Korean
L - Laotian
O - Other
P - Pacific Islander
S - Samoan
U - Hawaiian
V - Vietnamese
W - White
X - Unknown
Z - Asian Indian
'Weapon Desc'	Description of the weapon used (if applicable).
'Status Desc'	Crime status.
'LOCATION'	Street address of the crime.
# Re-run this cell

Project Instructions
Explore the crimes.csv dataset and use your findings to answer the following questions:

Which hour has the highest frequency of crimes? Store as an integer variable called peak_crime_hour.
Which area has the largest frequency of night crimes (crimes committed between 10pm and 3:59am)? Save as a string variable called peak_night_crime_location.
Identify the number of crimes committed against victims of different age groups. Save as a pandas Series called victim_ages, with age group labels "0-17", "18-25", "26-34", "35-44", "45-54", "55-64", and "65+" as the index and the frequency of crimes as the values.
