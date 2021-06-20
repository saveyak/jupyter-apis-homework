# jupyter-apis-homework
 Practicing APIs for the Columbia Lede Program in Data Journalism

# What the assignment was about

For this assignment, I practiced using the API's for two different websites: Weather.com, and Last.FM. I practiced searching for information via an API and then looping through the data.

# Something I learned in the process

* How to look through an API documentation to get the information I need
* How to concatenate strings
* How to push notebooks to GitHub and then update them
* How to create a list of endpoints from an API and loop through them to get information on a large group of subjects
* How to test my code on just the first two or three results so that I don't waste time grabbing huge amounts of information with bad code

# Something you found challenging 

* I found it annoying that after I finished my Notebook, I had to go back and manually edit out all the times that I had put my API key in the endpoint. I realized later that I could create an object called api_key, then create all my endpoints by concatenating strings with api_key, instead of actually typing out the key. This meant that at the end I only had to change one object. 

* I found it difficult to understand Last.FM's documentation. I thought that I needed to get the tags for an artist using artist.getTags, but it was actually artist.getInfo, which was not at all intuitive.

* It was tricky to figure out how to categorize whether an artist was a rapper or not a rapper. At first, I created a list called "rappers" and then appended the artist's name to the list if they were tagged in the rap genre. But I realized this solution was clunky and could eat up a lot of memory if I was working with a very large dataset. I talked to Ed the TA and figured out that I could instead set either "rapper = True" or "rapper = False." 
