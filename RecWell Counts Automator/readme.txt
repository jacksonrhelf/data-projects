This is a small program that I made to automate some of the data work I do through
my position as a Data Specialist at UW-Madison University Recreation and Wellbeing.
I was tasked with exporting the daily facility counts data from a company website,
formatting it in Excel, and transferring it into a large spreadsheet for use by 
professional staff. This process was often quite tedious, so I took it upon myself
to create a faster way to do this for use by myself and others who may perform
this task after I leave the university.

My program contains three functions, one for each of the recreational facilities I am
tasked with tracking. The function takes the name of the csv file, the number of days in
the month, the name of the month, and the number of Fridays, Saturdays, and Sundays in 
the month as our hours differ on those days. From this, it formats the csv file
which I obtain from the company website into a DataFrame containing the formatted
data plus a few summary statistics about each location within the building. It then
outputs the DataFrame as an Excel spreadsheet for transfer into the master spreadsheet.