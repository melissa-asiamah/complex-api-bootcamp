# Complex Studio Ghibli Movie Information App
This is a small app that returns a description of Hayao Miyazaki movies along with a corresponding gif from the movie fitting the title.


![alt tag](http://i65.tinypic.com/20jlp5d.jpg)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, API

I made this by using two APIs. One from a Studio Ghilbi API project site and another from Giphy to produces random gifs of the movies from the 1st API. I first found a list of the titles from with the JSON file of the API and made a forEach loop to extract each title and description which I then added to the input value so when the user enters in the title it will return the description. The description is added to the DOM. The second API for the gifs are in it's own fetch function but within the 1st function. This allows them to work together to produce the result needed.


## Lessons Learned:

THrough building this project, I learned how APIs work. I learned about JSON and how JSON is basically a giant array that holds a bunch of objects with key-value pairs you can access using a combination of dot notation or optional brackets to select which index you need from the JSON array. To loop through the array to select multiple elements of key-value pairs sometimes it is necessary to loop through them with a forEach loop. I learn how to append newly created elements with the appendChild method to add to the DOM to make new elements appear in my HTML.



```
