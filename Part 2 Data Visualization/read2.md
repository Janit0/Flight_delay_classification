# Section name: Data visualization 

# Overview:
This section includes visualization of the data columns to get a rough idea of how the upcoming prediction models will react to the data.

# Software used: 
Python, Tableau and PowerBI

# Sub-sections of visualization w/ results:
Columns selected for visualization were divided as per the division of task during preprocessing.

### 1. Departure Delay: 
Various combinations were used to gain insights related to Dep_delay column.

a>. Dep_delay v/s Dest: A barchart was plotted to display highest number of delays with respect to different destinations. 

Results: ORD (Chicago O'Hare International airport in Chicago, Illinois, USA) and ATL (Hartsfield-Jackson Atlanta International Airport, Georgia, USA) had the maximum number of dep delay.

b>. Dep_delay v/s months: A line graph was plotted to see which month had the highest amount of departure delay. 

Results: February and March had the highest number of departure delays
 

### 2. Destination:  
Various combinations were used to gain insights related to Dest column.

a>. Dest v/s org & distance: using dictionaries, a flight pairing was created "org_dest : distance" where org_dest acted as dictionary key (org = origin m dest = destination) and distance as a key value.

Then, Two bar graphs were plotted to review the top and bottom ranks of distance with respect to origin and destination.

b>. Dest v/s frequency:  Another bar graph was made to review the most visited places in the whole dataset along with the help of dictionaries  

Results: ORD and ATL are again top most visited places, which further assist the earlier visualization of both these places to be having highest dep delay.

### 3. Distance:
Various combinations were used to gain insights related to Distance column.

a>. with the help of PowerBI,  using a bar graph gave a range of distance in the dataset

Results: range = [254, 37447980]

b>. Three more graphs were plotted to see in which month, day of week and by which unique carrier most of the distance was covered.

Results: Month of march had maximum amount of travellers and saturday was the day where travellers commuted the most via airplanes. In addition to this, "AA" was the highest distance covering carrier. 

### 4. Delays: 
Various combinations were used to gain insights related to all of the sub-delay columns.

Results: 
a>. Maximum number of delays in regards to month: March.

b>. 50-50% flight ratio of having and not having carrier delays, march with maximum number of carrier delay whereas February with not having carrier delay.

c>. 7-93% flight ratio of having and not having weather delays.

d>. 50-50% flight ratio of having and not having NAS delays, march being at top in both cases.

e>. Only 0.5% of security delays in the entire dataset.

f>. 56-42% flight ratio of having and not having LateAircraft delays, feb and march being at top in both cases.

### 6. Arrival delay: 
Various combinations were used to gain insights related to Arrival delay columns.

Results: ORD, ATL had highest number of arrival delay.


## Files in the folder:

|File name            | Description...                           |
|---------------------|------------------------------------------|
|Dep_delay viz - Abu  | images of visualization                  |
|Dest Viz - vidhut    | images + coding files for visualization  |
|Distance Viz - Megha | pdf files of visualization               |
|Taxi_In viz - Meera  | coding files for visualization           |
|Delays, freqs        | coding + images for rest of visualization|
