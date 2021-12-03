# PyBer_Analysis

## Overveiw of Analysis

In this analysis, I went through rideshare data and summarized the results determined by weather a city is Urban, Suburban or Rural. Some of the data that I went through was figuring out the total number of rides per city type, total number of drivers per city type, the total amount of fares collected per city type, average fare per ride, and average fare per rider. 

## Results

Analyzing the ride share data leads to some pretty intersting results

The first thing we can look at is the breakdown is the total number of rides for each city type. We can do this by counting the number of ride id's per city in the entire rideshare data frame.

<img width="236" alt="Screen Shot 2021-12-02 at 9 07 38 PM" src="https://user-images.githubusercontent.com/92888170/144548692-f7f942fe-04d7-462e-90e5-3d996d974ad7.png">

  - There were 1,625 rides in Urban cities
  - There were 625 rides in Suburban cities
  - There were 125 rides in Rural cities
  
The next thing that can look at is the breakdown of the total number of drivers for each city type. We do this by summing the number of drivers for each city in the rideshare data frame

<img width="288" alt="Screen Shot 2021-12-02 at 9 13 34 PM" src="https://user-images.githubusercontent.com/92888170/144549204-1602ba0e-00a0-4395-8f3e-cbf9a7ae222b.png">


  - There were 2,405 drivers in Urban cities 
  - There were 490 drivers in Suburban cities
  - There were 78 drivers in Rural cities
  
Now the we know how many drivers and rides for each city there were, the next thing that we can look at is how much total fares were collected per city. This is done in a similar fashion to how we got the total number of drivers.

<img width="288" alt="Screen Shot 2021-12-02 at 9 16 10 PM" src="https://user-images.githubusercontent.com/92888170/144549446-dbbe1326-e1f8-4b5b-ba36-ec8e3ee3c264.png">

  - $ 39,854.38 was collected in fares in Urban cities
  - $ 19,356.33 was collected in fares in Suburban cities
  - $ 4,327.93 was collected in fares in Rural cities

Now that we know how much each city collected in fares, it is only natural to figure out the average fare per driver and the average fare per ride in each city.

The average fare per ride breaks down like this:

<img width="204" alt="Screen Shot 2021-12-02 at 9 23 56 PM" src="https://user-images.githubusercontent.com/92888170/144550053-57a52a94-6594-42d7-b9b3-33436406d517.png">

  - $24.53 was the average fare per driver in Urban cities
  - $30.97 was the average fare per driver in Suburban cities
  - $34.62 was the average fare per driver in Rural Cities

The average fare per ride breaks down like this:

  - $55.49 was the average fare per ride in Urban cities
  - $39.50 was the average fare per ride in Suburban cities
  - $16.57 was the average fare per ride in Rural Cities

The total data breakdown summmary ended up looking like this:


<img width="601" alt="Screen Shot 2021-12-02 at 9 31 20 PM" src="https://user-images.githubusercontent.com/92888170/144550633-aa78d2ac-2cd9-4997-9cba-b78a18d229d2.png">

The final thing that was analyzed was how the total fare by city type changed over time. More specifically, I tracked how the total fare per city changed from January 2019 through the end of April 2019 on a week by week basis. These were the results in the form of a line graph:

![Pyber_fare_summary](https://user-images.githubusercontent.com/92888170/144550912-deeb0144-5589-416c-8d70-7d4da729e889.png)


## Summary

Now, based on the data that I analyzed and graphed, I can come to some conclusions on some reccomendations I can make for the buisiness. The thing that stands out to me is how profitable Urban cities are to the total fares collected. I want to try and galvanize as much activity in Urban cities as I can since they collected more fares than Suburban and Rural cities combined. I would do this by offering perks for people to drive in the city, maybe through an incentive program. The next thing I notice is that the average fare per driver in Rural cities is less than in Suburban cities, despite the fact that there were far less drivers in Rural cities. This leads me to believe that the company should try and take advantage of this differnce and add more rural drivers. Althouyght there are less drivers, the data shows that each driver is cheaper per ride in Rural cities. In a perfect world, I would like raise the fares for the RUral cities because there are less drivers so there is more of a demand for them. The finral thing I would do is to incentivives riders, maybe by giving out free rides, in Suburban cities. The average fare per ride was more double in Suburban cities, so I think the company can afford a cheaper fare per ride if it leads to more total rides in the long run adopting the serivce. 
