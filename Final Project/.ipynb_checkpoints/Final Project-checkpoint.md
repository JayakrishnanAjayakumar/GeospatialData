<h1>Final Project : COVID in Cuyahoga </h1>


The final assignment is based on the nine questions given below


The questions
--------------------------------

1)	Create three different professional maps (with all the necessary elements) for Test positivity (total positive cases/total tests) rate for census tracts within the City of Cleveland for the period (2020-05-01to2020-08-01, 2020-08-01to2020-11-01, 2020-11-01to2021-02-01). 

Required files

a)  City of Cleveland Boundary File (https://cwru.box.com/s/p1lfgqhw1xhi53tbo0e219pni8jk58j7)

b)  Census tracts for Ohio (https://cwru.box.com/s/eskcdycjs5gmidzgi8b6wivt27x6tche)

c)  Covid datasets (https://cwru.box.com/s/plbp1s90tjncz8dnn8s4d46263su110v). You can use filter by attributes to query with the required interval based on 'day' attribute. Say for the interval 2020-05-01to2020-08-01 you can query using day>='2020-05-01' and day<'2020-08-01'


2)	Create a professional map for testing rate (defined as total tests/total population) for census tracts within the City of Cleveland

Required files

a)  City of Cleveland Boundary File (https://cwru.box.com/s/p1lfgqhw1xhi53tbo0e219pni8jk58j7)

b)  Census tracts for Ohio (https://cwru.box.com/s/eskcdycjs5gmidzgi8b6wivt27x6tche)

c)  Covid dataset (https://cwru.box.com/s/plbp1s90tjncz8dnn8s4d46263su110v)

**Note: For population use the field E_TOTPOP from census tract.**
       
3)  Create a professional map of death rate (total number of deaths/total population) for Ohio Counties.

Required files

a)  Ohio Counties Covid deaths https://cwru.box.com/s/whup139cicpqyalacxlcwmcyjfd6kkdi

b) Ohio County Shapefile https://cwru.box.com/s/3hl1aflu2m9gvm4ihhtckrrh37d28ai8

c)  Total Covid deaths across counties in Ohio https://cwru.box.com/s/whup139cicpqyalacxlcwmcyjfd6kkdi

4) 	Create a professional map for city of Cleveland with parcels having more than 10 positive covid cases for   elderly people (age 60 and above) with in them. The matching parcel polygon should be colored red. Also take a screenshot of the final attribute table.

Required files

a)  Cleveland Parcel Data https://cwru.box.com/s/atsd1m0rrqwzilddozhr7g32f9c3zxtx

b) Covid dataset (https://cwru.box.com/s/plbp1s90tjncz8dnn8s4d46263su110v)

**Note : If you get an error which states that some of the geometries are invalid, 
go to Settings --> Options --> General --> Invlaid features filtering (select skip features wtih invalid geometries)**

            
5)  Create two different professional map for total test positivity rate (total positive/total tests) and sovi score for the census tracts with in the City of Cleveland (for SOVI score use RPL_THEMES..higher the value higher the vulnerability). Align them side by side for a visual comparison 

Required files

a)  City of Cleveland Boundary File (https://cwru.box.com/s/p1lfgqhw1xhi53tbo0e219pni8jk58j7)

b) Covid dataset (https://cwru.box.com/s/plbp1s90tjncz8dnn8s4d46263su110v)

c) Census tract with SOVI scores (https://cwru.box.com/s/eskcdycjs5gmidzgi8b6wivt27x6tche)


6)  Create a professional map of SOVI scores for the ZIP polygons in Cleveland. As SOVI data is not available for ZIP codes, you have to use the SOVI raster grid to assign SOVI scores for the ZIP.

Required files

a)  Zip Polygons for Cleveland (https://cwru.box.com/s/pquhnbp0xiqoguhq0xstpdw7al1lsdfz)

b) SOVI grid (https://cwru.box.com/s/k98x22ksbsfa4vhndmui2f71xz6ho5s4)  (use svi_2018_tract_overall_wgs84.tif)


7)  Create change raster’s (using subtraction) from the KDE raster’s provided for 3 month intervals from 2020-05-01  all the way up to 2022-02-01. You will create 8 maps in total
             
             Between 2020-08-01to2020-11-01.tif and 2020-05-01to2020-08-01.tif
             
             Between 2020-11-01to2021-02-01.tif and 2020-08-01to2020-11-01.tif
             
             Between 2021-02-01to2021-05-01.tif and 2020-11-01to2021-02-01.tif
             
             Between 2021-05-01to2021-08-01.tif and 2021-02-01to2021-05-01.tif
             
             Between 2021-08-01to2021-11-01.tif and 2021-05-01to2021-08-01.tif
             
             Between 2021-11-01to2022-02-01.tif and 2021-08-01to2021-11-01.tif
             
             Between 2022-02-01to2022-02-05.tif and 2021-11-01to2022-02-01.tif
             
             And finally
             
             Between 2022-02-01to2022-02-05.tif and 2020-05-01to2020-08-01.tif

             Use diverging color ramp (possibly green (low values), yellow, red (high values))

Required files

a) All rasters https://cwru.box.com/s/eyt3yeec6iuc05i1ity3eh0jnbeq642h


8)  From the hospital dataset select all the hospitals inside Cleveland city boundaries having at least 100 beds. Create a graduated symbol professional map showing the number of Covid positive cases for the time interval between 2020-11-01 and 2020-02-01 with in 1000m radius (1KM radius) of the selected hospitals. 

Required files

a) All hospitals https://cwru.box.com/s/av0xuueq98usufwbljl36id96k3m1qwh

b) Covid cases https://cwru.box.com/s/osgegj5fx5fecec9ie8d6ptt9rlz8ikq  (select the file 2020-11-01.shp)


9) Create three different admission rate map (total number of admissions/total positive tests) for census tracts in Cleveland for the time period 2020-05-01 to 2020-08-01, 2020-08-01 to 2020-11-01 and 2020-11-01 to 2021-02-01. 

Required files

a) City of Cleveland Boundary File (https://cwru.box.com/s/p1lfgqhw1xhi53tbo0e219pni8jk58j7)

b) Covid cases https://cwru.box.com/s/osgegj5fx5fecec9ie8d6ptt9rlz8ikq  (select the files 2020-05-01.shp, 2020-08-01.shp, 2020-11-01.shp)

c) Admissions data can be downloaded from https://cwru.box.com/s/4uxrfvmk33y8h8864gh8mpitqy7skxd3



<h2>Task 1 (Written document)</h2>

Everybody has to create a word document with responses to each of the nine questions. The answers should discuss on the type of dataset that was used and what methods you used to solve the problem. The maps or any other artifacts should be professional (attention to details). You should also have a brief discussion on what you deduce from the data. 
    

<h2>Task 2 (Presentation)</h2>

From the nine questions you have to present your results for three questions.

Naveen Kannan (nxk562)  ----- questions (1,8,6)

Anna Magoline (axm1677) ------ questions (9,2, 6)

Neeti Shirke (nxs726) --------- questions (5, 8, 4)

Jeff Kovach (jxk1105) --------- questions (7, 3, 5)

Sneha Yamsani (sxy400) ---------- questions (4, 7, 8)

The total time for a presentation is 8 minutes with 2 minutes for discussion. The presentation should contain details about your question, how you approached the problem and your solution (with maps or any other required artifacts). You should also talk about your deductions based on your solution and how your solution could be generalizable. You can also discuss about potenital hiccups/issues that you faced while trying to solve the problem. You should also have a slide with discussions on how GeoSpatial Data would be useful for you in your career.


Due Dates: 

**Task 1: 07/27/2022 (this is mandatory and everyone should turn up their final document before 11:59pm. There will be deductions for late submissions)**

**Task 2: Your final presentation on 07/28/2022**











    







