# Restaurant-management-system
# Introduction
![GaussianOstrum's GitHub stats](https://github-readme-stats.vercel.app/api?username=GaussianOstrum&show_icons=true&theme=radical)

The *Web ordering system* is to provide the cafeteria with the next day's dishes as a reference. It is used ```HTML5 + CSS3 + JS(jQuery)```for front-end development . The database uses the local database WebSQL , and does not use back-end development. The system implements the following basic functions:<br />

There are three homepage navigation: Homepage, My orders, and order statistics<br />

- In the home page:<br />
  >  Display the dishes of the day, hot dishes, recommended dishes, and display complete information.
  
  >  Realize the ordering, the results are displayed in the appropriate position, and the ordered dishes can be canceled.
  
  >  The "submit" of a la carte is to save the data locally and then reproduce it in "My Order".
- In the My Orders page, data can be extracted from the data center stored locally and displayed, and can be added and deleted.<br />
- On the order statistics page, the statistics of the top three most popular dishes of the day are displayed in a graph. The statistical results use different types of charts to display the following dimensions: dishes, prices, tastes, and ingredients.<br />
# System design
System function structure diagram:
![Screenshot (1307)](https://user-images.githubusercontent.com/66365903/156884819-df16d79c-1b0d-4982-93c1-220807066fb2.png)
# System implementation
Home (Foods of the Day)/Recommended Food/Hot Buying Food
