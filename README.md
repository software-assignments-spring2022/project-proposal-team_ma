# Project Proposal

## Project Title: Forecaster

## What and Why?

There are many times where we can be caught without an umbrella or wear a couple layers too little. To solve this problem, Forecaster is here to remind you, and only when and if you need it.

The Forecaster would be a web based application where users can create an account and enter their geolocation information. Along, with this location information they can also set criteria for which they would like to be alerted. This can include the time of day, under which weather criteria (rain or hail), or how often they would want to recieve notifications.

Furthermore, notifcations could be recieved on email or sms platforms or both depending on their choice. They could possibly also enter messages or reminders on the web app to be sent alongside their weather info.

## For whom?

Forecaster is for anyone who has trouble remembering to check the weather or would want a more seamless reminder to bring an umbrella or put on some extra layers before leaving their house. Sometimes the best way to do this is by recieving a text or email as we are more likely to check our messages or emails than opening up the weather app.

## How?

Forecaster would first have user authentication which allows users to log in and change their settings. This information is protected as it can be personal phone numbers and emails. Next, their would be an asynchronous server running that would be pinged at whatever time that the user had put in for their preferences, this would get preform an api request to many of the weather api that are availble online. Finally, this info would be sent to a users phone/email via another api such as twilio.

## Scope?

The scope of this project requires around 3-5 programmers. The UX requires around 1 week while the front end devolpment would taken around 2 weeks. Backend development and data implementations takes around 4 to 5 weeks and testing will take 1 week.
