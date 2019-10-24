this app is using pixabay api to search for images by the keyword the user inputs in the form 
we will be using a fetch to returns a promise as a placeholder for a response we are going to get asynchronously
when the user adds a keyword in the 'search-term' we will add that term to a url that uses the api and our api key a
that will then return json information
we will then loop though that json information add use the images information to display the images requested onto the image div with an id of images.
if the user inputs an invalid keyword we will add a catch to display an error to the user "sorry, no results found"
to add a better user experence we add a function to remove old photos when a new key word is requested.

//TASKS
1. set up the endpoint to add url, the search term, and api key
2. fetch the json data and return that data
3. then console log the data and add variable for data.hits (which is a list of objects)
4. loop though the objects to extract the images
5. Through the loop: for every image create an image element, add a source url of image, and append that image. the source will can know where to pull image from 
6. add a catch to return a failed response 
7. add a function to delete images once a new search term is added 
8. create a function that will call the function that will clear images and then call the function that will get image results 
9. add an event listener to call the function you created on step 8
