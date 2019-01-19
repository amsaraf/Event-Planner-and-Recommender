# Project-Team-3

#### Project Collaborators:[Mugdha Wadikar](https://github.com/Mugdha001), [Amruta Saraf](https://github.com/amsaraf), [Jai Chhatre](https://github.com/c-jai), [Shivam Waghela](https://github.com/shivamwaghela)


## Project Ideas for CMPE 272 - approved idea

### Evento
Project Description:
Through Evento you can create, predict number of attendees, find and attend events that fuel your passion. What’s unique in Evento is that, apart from suggesting recommendations hand-picked for you, it also predicts how many users will be interested for the event you are thinking of hosting! Using our prediction, you are able to view the number of people even before you host it online, and hence you can plan your events and resources needed for them much efficiently.

### Solution:

+ Datataset: https://www.kaggle.com/c/event-recommendation-engine-challenge
+ Search operation: Show results for the keywords searched by users.
+ Event-hosting and Prediction count of interested persons: Host events by entering event-details. 
  For prediction: enter the details of events like name, description, venue details etc; Evento will predict the number of people interested in this event based on the number of people who attended similar events(similar in terms of description, proximity between the user's location and event's location) in the past. Thus, one can view prediction of number of users interested in an event even before it is hosted.
+ Event Recommendation: A logged-in user can view recommendations, which the application suggests based on the past events attended by user.

### Technology: 
+ MongoDB-Express-React-NodeJS stack, IBM Watson Studio for Data Refinery and Machine Learning

### Video link:
https://youtu.be/XSQ5L0YCakY

### Implemented changes suggested by Prof Ranjan, after the project presentation:
+ Calculated similarity between past events and upcoming events for both recommendation and prediction feature by using TFIDF vectorizer and cosine similarity. 
+ Login flow provided only for the recommendation feature. Removed the need for login for the prediction feature.




