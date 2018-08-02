# Wikipedia viewer
https://codepen.io/kam773/pen/QmXgGo
# The Project
Allows the user to either be linked to a random Wikipedia article or search Wikipedia and be returned search results based on their input. Once the user has submitted their search request, the page loads the top 10 results detailing the title, a short text overview on that topic as well as a link for the users to click through to the main Wikipedia page.
![wikipedia viewer](https://user-images.githubusercontent.com/33424405/43582534-161c4e2e-965d-11e8-92c5-1c0428707948.png)
# The Logic
The handling of the search results is through JavaScript. Once the users clicks submit a variable is created which holds the value of the text input box. We then make a call to the Wikipedia API with a getJSON call which responds with the data we need. 

