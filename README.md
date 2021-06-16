#Newsaholics

Project members:
- [Marculescu Andrei](https://github.com/MarculescuAndrei "Marculescu Andrei")
- [Alexandru Oana](https://github.com/Alexandru-97 "Alexandru Oana")
- [Dobrica Denis ](https://github.com/intMachine "Dobrica Denis ")
- [Leonard Vlaicu](https://github.com/leonard-vlaicu "Leonard Vlaicu")

## Project description

Our project is an **Android** application where a user can create an account and login, he is then prompted with a welcome screen where the purpose of the app is briefly explained. When a user gets on the home page of the app, he is shown news articles fetched from [NewsAPI](https://newsapi.org "NewsAPI"), they are built on the screen with a preview image, a title and a subtitle. At the top of the home page a user is shown a couple of categories, as of this [version](https://github.com/MarculescuAndrei/Newsaholics/tree/V1.0 "version"), the categories are : **Entertainment, Business, Science** and **Sports**. When the user selects one of these categories he will then have articles shown to him from that specific topic. A user can tap on an article preview and open it within a browser window in the app. Whenever a user wants to logout of the application, he can do so by pressing the **Logout** button in the AppBar.

##  App demo

The full demo for our app is available on [YouTube ](https://www.youtube.com/watch?v=_3-12Zf0N6A "YouTube "), in Romanian.

## User stories

1. I want to make my own account for my personal news app and login with it. -> [User authentication with Firebase](https://github.com/MarculescuAndrei/Newsaholics/issues/15 "User authentication with Firebase")
2. My account information needs to be in a secure environment. -> [App connection with Firebase](https://github.com/MarculescuAndrei/Newsaholics/issues/4 "App connection with Firebase")
3. I want to see what Im doing wrong when I am not able to login or signup. -> [Authentication error messages](https://github.com/MarculescuAndrei/Newsaholics/issues/15 "Authentication error messages")
4. I would like to see news taken from a trusted platform. -> [Fetch data from NewsAPI, the most popular API for news articles](https://github.com/MarculescuAndrei/Newsaholics/issues/6 "Fetch data from NewsAPI, the most popular API for news articles")
5. It would be nice to be welcomed whenever you open the app. -> [Welcome page](https://github.com/MarculescuAndrei/Newsaholics/issues/9 "Welcome page")
6. The pages where the user is authenticating should be easy  to navigate and look nice. -> [Create & Style authentication pages](https://github.com/MarculescuAndrei/Newsaholics/issues/11 "Create & Style authentication pages")
7. I want to see a big picture preview for every article with a title and subtitle, just so its not cluttered. -> [Home screen and article preview creation](https://github.com/MarculescuAndrei/Newsaholics/issues/14 "Home screen and article preview creation")
8. The app should have a way of logging you out of it. -> [Add Logout button](https://github.com/MarculescuAndrei/Newsaholics/issues/18 "Add Logout button")
9. Looking at the main random articles gets boring, I want to see that there are some specific topics I could check out. -> [Add categories on the Home screen](https://github.com/MarculescuAndrei/Newsaholics/issues/3 "Add categories on the Home screen")
10. When I find a category I'd like to explore, when I click on it I want to see articles related to that category. -> [Category functionality](https://github.com/MarculescuAndrei/Newsaholics/issues/19 "Category functionality")



## UML
##### Use case diagram:
[![UML](https://i.imgur.com/kwGf3RQ.png "UML")](https://i.imgur.com/kwGf3RQ.png "UML")

##  Our Database

We use a database within the [Firebase](https://firebase.google.com "Firebase") platform to hold the accounts that users can create on our app. An account is composed of an email address and a password, Firebase lets us see when the account was created, when it had the last login and it offers as a unique ID to easily find and use a specific account instance.

[![Firebase](https://i.imgur.com/gtwi9mA.jpg "Firebase")](https://i.imgur.com/gtwi9mA.jpg "Firebase")
