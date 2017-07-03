Product Plan Concept - Anna Barklund
===

Personal Learning Goals:
---
Reinforce Python. Learn Python3  
Learn to use some machine learning tools in python  
Learn Django (and compare it to Rails)  
Interested to know how Django works as an API  
Reinforce Javascript  
Reinforce Google API  
Learn how to use a google map on the web page    



Problem Statement:
---
The app will point out three locations that will serve as cluster centers for a number of addresses within a certain area on a map.  
Imagine a scenario that a company can deliver packages via drones from a truck, where will this trucks optimal position be. The assumption is that the calculation is done before the three trucks leaves the distribution center.  


Market Research:
---
There are some products that calculate where the middle point is between two addresses or calculates some specific location (like a coffee place or a park) that is located between two addresses. The obvious  use for these applications are to find where you and your friends can meet up.    
[Geomidpoint]( http://www.geomidpoint.com/)   
[Meetways](https://www.meetways.com/?utm_expid=11145340-3.PALpznZgSnGUbcwGj5eUBg.0&utm_referrer=https%3A%2F%2Fwww.google.com%2F)   
[App to meet far away friends](http://www.makeuseof.com/tag/5-apps-find-halfway-points-meet-faraway-friends/)


However I have not seen any app that calculates optimal centeroides for multiple clusters of addresses.   
Even though I have not found such an app, I did find information about the problems calculating these centeroides using k-means, which is my intent. These problems relates to the fact that the world actually is round and not flat, so using longitude and latitude as coordinates for that k-means calculations does not give an accurate solution. This is specifically problematic the closer to the poles one comes and around the meredian. I have decided that for this app I will use the k-means anyway for practice.   

For this problem I need to have lots of real addresses. It was not easy to find a way to gather lots of real addresses. Finally I found [Seattle historical sites](http://web6.seattle.gov/DPD/HistoricalSite/).   

User Personas:   
---
Probably most interesting for delivering companies.   


Technology selections:
---
**Back-end**  
Python3  
Django   

**Front-end**  
jQuery   
Backbone   

**Web infrastructure**  
[Pythonanywhere](https://www.pythonanywhere.com/)  
and   
Heroku   

**External API**  
[Google Maps API](https://developers.google.com/maps/web/)   
