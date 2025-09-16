---
layout: post
title: Mood & Running Task Tracker
---

A user can track their fitness along with their mental health.

- Gives users a to-do list for running and schedules it out for them
- Allows a user to enter mood/energy level each day whether they run or not
- Gives feedback however often (by the week or month) based on how the user feels each day over that time period
- Be able to show what times the user runs best and feels best (best times of day)
- Possibly track routes for runs based on gps and be able to leave reviews on the route
- Tracking mood and fitness trends over time

## Comparisons

### Running Aspect 

**Strava**
- I like the strava training calendar or training log, need to be able to plan and indicate some sort of mood score for that day.
- Don't want the social aspect
- Good graphs and charts for running stats

[Strava](https://www.strava.com/dashboard) One of the most popular running tracker apps out there. I personally use this and really like it.

### Mental Health and Wellness Aspect

**Daylio**
- Circles and things on the calendar. Take that and integrate with the Strava calendar.
- Doesn't integrate fitness into it at all
- Gives good overview with charts and graphs of mood but doesn't give high level insights

[Daylio](https://daylio.net/) This is a mobile app, but has good pictures to give ideas of what I could do with the mood tracker.

**Bearable**
  - Super complex and not user-friendly
  - I like the weekly and monthly overview screen

[Bearable](https://bearable.app/) This is the same as Daylio, it is a mobile app but provides good visualizations.

## Technologies

### Platform 
I will be targeting a web app platform. This appears to be the best thing to do with the time that I have. I am somewhat familiar with web apps so it won't be as much of a learning curve as attempting to do an android app where I believe I would have to learn a lot more which would take up a lot of time.

### Programming Languages
- **JavaScript**: Going to be using this in React for my UI stuff on the frontend. There really wasn't another option for the UI because I am doing a web app and you need to use Javascript for the web browers.
- **Python**: I chose to use python on the backend with Flask over the alternative of using Javascript as well for this because it allows me to use a language I am very familiar with in python and I can then focus my attention with javascript on solely the UI stuff.
- **SQL**
- **HTML + CSS**

### Frameworks/Libraries

**GUI**
- *React* is going to be my choice for the UI stuff because it allows me to build a dynamic web app and is something that seems to be very common in the real world. This will be good to learn because it allows me to focus on only react and not have to worry about juggling multiple libraries.
- *React Router* for navigating through different tabs or pages on the website. For example, if you wanted to change the view from your running calendar to see statistics about your mood, you would need to click somewhere to switch tabs.
- *Tailwind CSS* allows me to style my web app quicker than doing it from scratch. This will allow me to spend less time on how the app looks because of the ese of this process.
- *Recharts* over *charts.js* because recharts seems easier to use and will give me the necessary charts I need such as line charts and bar charts. I could potentially switch to charts.js depending on how much time I have if I want to add some more complex charts.

**Database**
- *PostgreSQL* will be the database I use because I have used it before in a past class so it will not be as much of a learning curve which will end up saving me time. This database selection is also very good for structered data like I will have in this app.
- *SQLAlchemy* allows me to define my SQL tables as python classes so that my code looks cleaner and I don't have to constantly see long SQL queries.

**Domain**
- I am going to use *Flask* because I already have experience with Python and using flask from a previous class. This also allows me to use REST APIs easily so that I can use the one from Strava as well.
- *Flask-CORS* allows my React frontend to be able to communicate with the Flask backend. Allows me to have Cross-Origin Resource Sharing.

### Package/ Dependency Manager

**For JavaScript:** Using Node.js and npm because it comes with Node.js already.

**For Python:** One of pip + virtualenv, pipenv, or poetry.

### Build Tools

**Backend Production Server**: gunicorn

**Frontend Build Tool**: vite

## Deployment / Distribution

### Frontend → React + Tailwind (UI)

I am choosing to use React because it allows me to use Javascript which is necessary to use for web browers. Tailwind allows me to customize my app in a simple way.

### Backend → Choosing Flask over Node.js + Express

I am going to use Flask over the alternative Node.js and Express because of my experience with python and it will allow me to limit my use of Javascript to strictly UI stuff. 


### Database → PostgreSQL (with Prisma ORM for developer happiness)

## Maybe
Need to show personal correlations which none of these apps do. Take user data and be able to give them actual insights into how they feel and what they should do instead of just presenting them with raw data.

## References
[1] Bearable. [Online]. Available: https://bearable.app/

[2] Daylio. [Online]. Available: https://daylio.net/

[3] Strava. [Online]. Available: https://www.strava.com/dashboard