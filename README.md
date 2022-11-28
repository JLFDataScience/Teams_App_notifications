# Automate daily tasks. An example of push notifications to Microsoft Teams. Scraping with Java Framework. 
### BDNS Scrapping to create app Teams notifications

Among my professional tasks, one of them is to explore public grants that may be published for scientific projects or projects of my own organization and send them to the corresponding departments as part of a Science&technological scouting system. It´s a repetitive and time-consuming task, so I thought about developing a small application that will automate this process and free up my time for other tasks.  
That´s why in this post I´ll describe in a simplified way an application that automates the personalized search in a Spanish database of grants and subsidies, the capture of information and it´s sending through a notification through Teams of Microsoft.  
### Description of the technical development of the App  
We´ll connect to a Spanish public database that uses Java / Ajax as a framework so BeautifulSoup are not designed to invoke JavaScript functions so I use the Selenium library as an alternative to extract the information since it imitates in the browser what a user would do to make a query.
