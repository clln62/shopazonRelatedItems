# Welcome to Shopazon!

In a world where millions of consumer products exist, wouldn't life be better if products you are looking for were easier to find? Shopazon, much like Amazon, is your one stop shop items page that allows you to find the item you are looking for, see related items and sponsored items, as well as seeing all of the reviews and Q&A's. This particular Repo focuses on the Related Items component in the monolithic app that is Shopazon.

<!-- <img src="./images/IH1.png" height="45%" width="45%"></img>
<img src="./images/IH2.png" height="45%" width="45%"></img><br/>
<img src="./images/IH3.png" height="45%" width="45%"></img>
<img src="./images/IH4.png" height="45%" width="45%"></img><br/> -->




## User Stories

- As a user, I want to see items related to the item I have already selected.<br/>
- As a user, I want to scroll through many items to pick from.<br/>
- As a user, I want to see the ratings and prices before I click on an item.<br/>
- As a user, I want to click on a picture to reload the page with the items relevant information.<br/>



## Stack

| Front End     | Back End      | 
| ------------- | ------------- |  
| <img src="https://cdn.worldvectorlogo.com/logos/react.svg" height="125px" width="125px"></img>  | <img src="https://cdn.pixabay.com/photo/2015/04/23/17/41/node-js-736399_960_720.png" height="85px" width="125px"></img>  |
| <img src="https://raw.githubusercontent.com/webpack/media/master/logo/logo-on-white-bg.png" height="85px" width="125px"></img>  | <img src="https://buttercms.com/static/images/tech_banners/ExpressJS.png" height="85px" width="125px"></img>  |
| <img src="https://cdn.greenhouse.io/external_greenhouse_job_boards/logos/000/007/263/original/Axios_logo_-_RGB_-_clear_space.png?1580309119" height="85px" width="125px"></img> |  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/6/62/MySQL.svg/1200px-MySQL.svg.png" height="125px" width="125px"></img>  |



### Front-End

In order to build a single-page app, I utilized React to separate concerns within my component that loads quickly and efficiently and is easy to understand when uploading to a proxy server. 

### Back-End

Webpage items and relevant information was stored in a SQL database to keep things relational and match the needs of other team members' components that were build separately with their own servers.

### Deployment

In deploying the Shopazon Related Items server, I used RemoteMySQL for easy and secure access for each member of the team.


## Work Flow

**This project was managed using git workflow:**

We have one development branch that branches out specific features. When they are ready to be deployed, features are deployed as follows:
1. The branch is rebased to consolidate commit history and ensure only working code is pushed to the dev branch.<br/>
2. The branch is pushed.<br/>
3. A pull request is made.<br/>
4. Another member of the team is to perform a review before merging the branch into developer.<br/>
5. At the end of a sprint, the developer branch is merged into production.

#### In addition to git, we also used Trello to manage pending tasks, bugs and feedback.

**Trello Board: https://trello.com/b/AlzmSI6G/shopazon**

<img src="./images/ShopazonTrello.png"></img>



## Challenges & Learning

This project was created by a group of Army veterans that were passionate about developing and learning new technologies. This app was an opportunity for us to showcase our skills that developed as a team and culminated in this project.

### Challenges

- Communication wasn't as strong as it could have been throughout the team at the start, so some of the app components were not succinct the way they needed to be.<br/>
- Time was a big hinder on exploration into new ideas and technologies, and it became easy to lose track of what the priorities were.<br/>

### Learnings

- Working with the rest of the team became a huge growth for everyone while building better communication to wrap up a cohesive app.<br/>
- Understanding where the rest of the team was and where everyone needed to go helped me as a developer in pair-programming with others, but also as the SCRUM Master to get a better overall picture of the project.<br/>
- Tickets on Trello assisted the team in planning and production. Utilizing Trello kept us organized and accountable in creating and developing a production level application.

