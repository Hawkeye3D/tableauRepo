# tableauRepo
Tableau Workbooks
https://public.tableau.com/profile/kevin.mcclard#!/

NYC RIDE Homework

I will say from the outset that the biggest problem with getting this homework done was not having a good understanding of Tableau's data management.   I blame Trilogy's teaching methods for that, not the teachers.   I was successful in downloading all of the monthly data from the NYC Bike Ride dataset, a process which I think is unduly long and tedious, especially for those who do not have gigabyte bandwidth.  A better way is for Trilogy to provide the dataset, with a set of instructions on how it was obtained and how long it took to download.  Trilogy should see itself as a facilitator of learning how to use packages efficiently.  Wasting hours downloading data for an assignment is not productive.  It may be a real world issue in a work environment, but this is NOT a work environment, it is an educational environment and there is a significant difference.  The next big issue was understanding that for large data sets, they should be extracted.  The extraction is Tableau's magic bullet for taking extremely large data sets, indexing them, and optimizing the internal matrices so that they can be accessed quickly.  It works very well, but can be time consuming.  Once done,however, a 15 billion byte data set works pretty much like a 1500 byte data set.

What I did:

1- downloaded each zip file for each month from June 2013 to Sept. 2019.

2-Wrote a python loop to extract the data for each zip file and store it in a separate directory

3-Use EM Editor to combine all CSV files into a single master file.  Could have been done with Python easily enough, but EM Editor is a good tool to use for this type of thing.  There are many ways to combine data files including from the command line.(Before doing that I did lots of things the hard way, extracting subsets, linking files and such before I realized that part of what makes Tableau so successful is that it makes much of what I did transparent, and I did not have to do anything to preprocess that data. )

4-In Tableau, I clicked 'Extract' and then opened the master file.  About an hour later, Tableau had processed all the the data into a Hyper file, and I was ready to play with Tableau, creating worksheets, dashboards and storybooks.  
