# skills-network-labs-8
IBM Skills practice assessments

Practice task
In this task, you need to create XMLHttpRequest to fetch data for news article.

For this you need to create one json file for news article just like you have worked with health.json.

Create javaScript code using XMLHttpRequest. For this you need to create object for xhr and define variable named url and assign link for json file.

Create javascript code to fetch news article from step 3 to step 6 provided in the previous lab instructions.

Then check the output for the same.

Perform git add, git commit and git push to push all your latest work.


Summary
Setting up fetch request:

You have created an object xhr to get data to define where the data is present.

You asked for data using xhr.open('GET', url, true); to prepare to receive data in a specific format (xhr.responseType = 'json';).

Using the received data:

You created the function xhr.onload = function() { ... } to retrieve specific information like articles, and decided where to show them on the webpage using document.getElementById('articles').
Putting it all together:

For each article, you created webpage parts like title descriptions and filled them with data.

You then fetched these parts on the webpage and sent the request to get the data xhr.send();.


