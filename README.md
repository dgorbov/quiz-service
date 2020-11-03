# quiz-service

## Motivation
* Check frameworks/tools for unit and integration tests in java world that are actual for 2020/2021 and useful at my work.
* I've picked QUIZ topic to use as service in my side project and keep it public for my portfolio.

## Business requirements v0.0.1

### Big picture user stories
* As a user I want to see list of the QUIZes available for me so that I can select
* As a user I want see grade for a QUIZ so that I can understand am I doing good or bad
* As a user I want QUIZ to have various question types so that I will not be bored with one type
* As a user I want some dialogs happening in a QUIZ so that I can see storytelling and not only questions/answers
* As a user I want QUIZes to be limited by time so that it will be harder for me to complete them
* As a user I want to save my progress so that I can return to QUIZ later
* As a user I want to have retries for answering single questions so that single mistake will not mark answer wrong
* ??
 
### More detailed spec
* Try auth0 instead of building
* QUIZ can be not just list of questions but more information blocks. So you can combine storytelling dialogs and questions. 
* QUIZ grade: 10 max, 0 min. When user makes error in a question his total grade slightly decreases. If he failed all 
question grade decreases more.
* Start with these question types: select option 1 of N; write your answer ans word, sentence, number; make correct order
* Keep a log of user answers 
* ??
