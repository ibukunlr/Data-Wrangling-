
This project involves data wrangling , analysing and visualising a the tweet archive of Twitter user @dog_rates, also known as WeRateDogs, using python libraries (Pandas, Matplotlib and seaborn). 
After gathering, accessing and cleaning the datasets , I came up with 3 visualizations and insights .

First insight was on the distribution of sources to ascertain where the users were tweeting from.Using a horizontal bar chart,it was deduced that a lot of the users were tweeting from an iphone as Twitter for iphone has the highest no of records of 2042 which is about 95% of the total records, followed by Vine-make a scene with no of records recorded as 91 about 0.04%, with Twitter-web client in the 3rd position with 31 records and tweetdeck has the least no of records (11) ,an insignificant percentage.
![image](https://user-images.githubusercontent.com/77775532/190391737-43ba1a2f-ed23-4392-8013-7f725686d7be.png)



Second insight I made was on the distribution of dog stages, A large amount of data was missing in this particular column,over 80 % of the stages werent recoreded, 0.10% was recorded for pupper, 0.03 % for doggo, and 0.01% was recorded for puppo. We cant really give an accurate report for this particular analysis as a result of the large missing values which could be as a result of data entry error, lost files, equipment malfunctions among other things.

![image](https://user-images.githubusercontent.com/77775532/190391841-f96c6889-cadb-4336-bc84-e9f8881b7b7d.png)

Lastly, I found the correlation between the favouritecount and the retweet count of the tweets, to ascertain if there is a relationship between them, this was achieved by using a scatterplot.Upon plotting , I discovered that there is a strong positive correlation between the two variables, that is as the favourite_count increases, the retweet_count also increases. The R^2 (co-efficient of determination ) was 0.91.

![image](https://user-images.githubusercontent.com/77775532/190392061-8cb75dd2-7a2e-4895-8715-0f271c9a1c44.png)

