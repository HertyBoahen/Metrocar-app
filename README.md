# Metrocar-app
Funnel analysis 

There are a growing number of transport services around the globe. As an industry of ridesharing service, Metrocar believes it is a good choice for users to discover the app easily, book and pay for their services without any concerns . Metrocar has released a public dataset which can be found on Beekeeper studio which contain data 
of 
 App downloads
 sign ups
 Ride requested
Driver_accepted
Ride_completed
payment_info
Review.


The novelty of our analysis is  by using a combination of SQL, Spreadsheet and Tableau public to generate  clusters of user information  from DOWNLOAD to PAYMENT. This will  provide useful guidelines about the Metrocar ride-sharing app. Furthermore our data extracts insights on a high granularity level where the rides are based on the day and hour they started. Moreover we added more useful features like age_range and platform (ios, web, android) in our to provide areas with a high number of trips in any given day and time. 

During my ride count analysis, I considered the fact that a user count has  to have multiple journey counts. I thought it would be better to count each user as a unique count. Furthermore then  i decided to keep the age range ‘Unknown’  as user age was relevant information too. 


Creating CSV FILES USING SQL

Since there were about 40000 columns in a file , I used SQL to extract relevant information that can help me create a business friendly dashboard that the stakeholders of  the company can understand .

Additionally  with the help of funnel analysis ,gained better understanding in the dynamics of the ridesharing app from the point at which users download the app  on their devices to the last step of the user rating the riding experience ,  

Lastly , we will answer specific business questions from the stakeholders.










What steps of the funnel should we research and improve? Are there any specific drop-off points preventing users from completing their first ride?
Upon visualizing the diagram on Tableau I realized that out of the unique users (23608 + 100%) who downloaded the app on their devices, only 74.65% proceeded to the signups stage. A powerful but mostly overlooked point is user-rating. Users are supposed to brag about the app in order for other users to be enticed to follow through the steps and request their first ride. If we want to boost download, marketing budgets should  allocate funds to advertise the app of social media sites such Facebook and Instagram. Tech bloggers and  influencers can also promote the app. Additionally users should also be familiar with the new interface. Imagine being given a task without giving any instructions. A short video explaining the onboarding process is necessary to complete the set. Another significant drop off point is the process to ride_requested to ride_completed. 12406 users were recorded to request a ride, however I realized that 6233 users completed the ride . This is a significant red flag that needs investigating. From my own personal experience, users cancel the ride when they are on the way to the destination . Also users are not conscious where their pick up point is. Users should be advised where to choose a pick up stop where the driver can easily park and wait for some few minutes. Drivers should also be given the option to call the passengers if needed. 
https://public.tableau.com/views/funnel_data_16997810384970/Sheet1?:language=en-GB&:display_count=n&:origin=viz_share_link 




Other factors that may have contributed to a large drop off in ride completion may be that the wrong size of car was requested. For example, ordering a 4 seater car for 5 passengers. Drivers will not risk their job by going ahead with the ride. Some companies like Uber or Bolt offer XL versions for large capacity rides. 
Metrocar currently supports 3 different platforms: ios, android, and web. To recommend where to focus our marketing budget for the upcoming year, what insights can we make based on the platform?

Any random information security personnel agree that iOS devices are far more safe to use than android devices. iOS devices are currently only made by Apple which has a sophisticated anti malware and antivirus system on the App Store. Thus, in our dataset 60% of the users have an Apple phone.  Android phone users who are about  30%  cannot brag about this feature. Google playstore hardly monitors security threats and malware. 
User interfaces in Apple phones are designed  simply and are of higher quality. Android apps cost more and their interface is clustered. 
Web users have the lowest user count (10%)of users. The reason being, most users are on the move and tend to keep their smartphones handy rather than carrying a pc monitor.  That market budget should focus on every platform  proportionally. It is important to continue to keep all the users that have already signed up and are frequent users.
What age groups perform best at each stage of our funnel? Which age group(s) likely contain our target customers?
From the results of the users () that performed best at each stage was the age group category 35-44. These groups generated the highest revenue (126085 usd) in the morning peak hours. 
Metrocar should target all age groups.  The demand for rides in the older age group(45-54 years) is very low. Our target is to make a simpler view interface to elderly users.
https://public.tableau.com/app/profile/hernita.boahen/viz/otherinformation/Sheet3#1 
Surge pricing is the practice of increasing the price of goods or services when there is the greatest demand for them. If we want to adopt a price-surging strategy, what does the distribution of ride requests look like throughout the day?
https://public.tableau.com/app/profile/hernita.boahen/viz/otherinformation/Sheet1#1 
Surge pricing occurs when the demand of ride requests is more than the supply of riders near a given area. In our database, there is a spike of commuters in the peak hours between 7:30 am and 9:30 am  as well as between 15:30 and 19:30 pm. This corresponds to the time people resume their days by going to work, school/ or running errands as well as returning back home in the evening. People will pay the higher price just to make it back home in time.






What part of our funnel has the lowest conversion rate? What can we do to improve this part of the funnel?

The lowest conversion rate was ride accepted to ride completed. In all only about half (50.77%)of the rides that were accepted and completed. Something specific could have prompted the users/ and or drivers to cancel the ride. 
Here are a few suggestions on how to tackle this matter. 
Define who your  core customers are (example customers who travel to and from specific locations (like school, work, sporting event etc) on many occasions. Then organize pick up/ drop off  with them at a very attractive price. 
Offering rewards programs for users if  they refer a friend. 
Offer different payment methods
Keep an eye on the user rating -dirty car , bad manners , bad hygiene etc puts people off and respond individually to has ever given a bad rating. Drivers should  engage in conversation with the customers( if the situation seems fit).
 



Tableau dashboad link , funnel steps and platform
https://public.tableau.com/app/profile/hernita.boahen/viz/funnel_data_16997810384970/Dashboard2#1

https://public.tableau.com/app/profile/hernita.boahen/viz/otherinformation/Dashboard1 
https://public.tableau.com/app/profile/hernita.boahen/viz/Ridersinfo/Sheet1#1







