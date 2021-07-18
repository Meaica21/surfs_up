# Surfs_up Temperatures Trend Analysis

## Overview of the analysis: Explain the purpose of this analysis.

W. Avy would like to invest into a Surf’n Shake Shop and would like to ask for an analysis about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


## Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

  •	One major point is the use of SQLAlchemy  library that translates Python classes to tables on relational databases and automatically converts function calls to SQL statements     as shown in Figure 1 below.
  
  ![Figure 1 Usage of SQLAlchemy  library](https://user-images.githubusercontent.com/83877498/126053989-861c3b45-3b84-4358-abd8-b07fe1e2a19d.PNG)
  
  Figure 1: SQLAlchemy Library Usage
  
  •	Secondly, was the use of SQLite strftime() function to format a datetime value based on a specified format.
    As an example below, retrieval of the temperature for the month of June and Dec and I’ve used the string format %m - month: 01-12
    
   ![Figure 2 SQLite Date Format](https://user-images.githubusercontent.com/83877498/126054005-24410a7f-0cdf-457e-b90f-ec3853fd8400.PNG)
   
   Figure 2: SQLite Date Format
   
   •	Lastly, the use of sql function and converting into a list. Creating Dataframe from the list and sorting the data.
   
   ![Figure 3 SQLFunction,List and Dataframe](https://user-images.githubusercontent.com/83877498/126054104-459b4015-88d8-411b-8492-3336078ba003.PNG)
   
   Figure 3: SQL functions, List and Dataframe
   
## Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

  December is colder than June by about only 4 degrees Fahrenheit.  The minimum temperature can drop as low as 56 degrees in December, which, is significantly lower than 64       degrees in June.  However, since the standard deviations are only about 3 degrees, temperatures don’t usually change drastically in within either month.  This, combined with     the fact that the averages are also similar, means that there is little difference in temperature between the two months.
  
  ![Figure 4 June and Dec Summary Statistics](https://user-images.githubusercontent.com/83877498/126054115-adba9e42-219f-4de5-be88-4728054f3bb0.PNG)
  
  Figure 4: June and Dec Temperatures summary statistics 
  
  




