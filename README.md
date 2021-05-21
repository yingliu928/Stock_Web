# Stock Web

## Web URL
- Visit https://ownstock.app/ now!

## How to run
- Go to server_code folder
```
npm i
npm start
```
- Then go to this root folder. Run on localhost:3000:
```

npm i
npm i --legacy-peer-deps
npm audit fix
npm start
```
- Or go to our deployed web: [ownstock.app](http://ownstock.app)

## Features
- User registration and log in
- Users can have overview charts of Nasdaq, NYSE, Dow Jones Index
- Users can search stock information and display this stock status.
- Users can save the stocks they are interested in 
- Users can read news about their concerning stocks or companies（Due to API limitation,only available on localhost）
- Ranking of most popular models 
- Notifications (emails) to the users when some event happens
## Three Technologies from CS554 Course
- Firebase Auth
- React
- Redis
## Two Independent Technologies
- Recharts
- Web deployment using Heroku 

## Tips:
- Due to API limitition -- 5 requests per second, we add delay time between each requests, which performs as loading data is a little bit slow.
- Please do not visit our web page for too many times due to the API restrictions.(Unless you are our professor.)
- Please try to avoid visiting our website on your Macbook, it will lead to a lot of bugs.
