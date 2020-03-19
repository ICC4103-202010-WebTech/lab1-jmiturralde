**ACTIVITY**

*3.- How is the list of news articles structured with HTML?*

Well, basically the information is order by using the table tag “table”. This tag offer as the possibility of separate the data in an efficient and elegant way. Every article is within a table row, this can be accomplished by using the "tr" tag, in which data is inserted with the "td" tag, creating a perfectly order line in the website. The reason why you con then click on the title of the article and follow his url is because they use an "a href=.." tag.

*4.- Briefly describe what you see in files with names starting with hn.js and news.css. How are
these files different? What is their purpose?*

The hn.js document has all the function that let the page run free. For example, the comments functions allow as to see all of the comments of the corresponding article by calling the “Document.getElementsByClassName(), that returns an object similar to an array that has all of the names of the indicated class. 
By the other hand, the news.css gives all the visual style of the page. Giving for example what type of typography to use or what font size to be use for the different text in the page.
Having said that, the two documents are totally different from each other, but everyone maintain an important roll in the proper display of the page. 

*5.- How many requests has it taken for the browser to download the Hacker News main page? What are the
HTTP request methods in each case? Check out the HTTP response headers and find out
what kind of web server is used for this website.*

It took a total of 7 requests for the browser to download the Hacker News main page, on each case the request method used was the “GET” request, in which the manage to get the information from. Finally, searching in the response headers we can find out that the website use the **nginx** server. 