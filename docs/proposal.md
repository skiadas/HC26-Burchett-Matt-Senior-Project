---
---
# Proposal

Mood & Running Task Tracker

A user can track their fitness along with their mental health

- gives users a to-do list for running and schedules it out for them
- allows a user to enter mood/energy level each day whether they run or not
- gives feedback however often (by the week or month) based on how the user feels each day over that time period
- Be able to show what times the user runs best and feels best (best times of day)
- possibly track routes for runs based on gps and be able to leave reviews on the route
- tracking mood and fitness trends over time

Running aspect examples: 

**Strava**
- I like the strava training calendar or training log, need to be able to plan and indicate some sort of mood score for that day.
- Don't want the social aspect
- Good graphs and charts for running stats
[Strava](https://www.strava.com/dashboard)

Mental Health and Wellness:

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
I will be targeting a web app platform. This appears to be the best thing to do with the time that I have.

### Programming Languages
- JavaScript
- SQL
- HTML + CSS

### Frameworks/Libraries
- React Router (navigation between pages)
- Express.js (framework, handles routes & APIs)
- Cors (so your React app can talk to your backend)
- PostgreSQL (the database itself)
- pg (library for Node.js to connect to Postgres)
- Bcrypt (password hashing) **MAYBE**
- JSON Web Token (JWT) (auth system for login sessions) **MAYBE**
- Recharts / Chart.js → for mood vs run/task data visualization.

## Deployment

Frontend → React + Tailwind (UI)

Backend → Node.js + Express (API)

Database → PostgreSQL (with Prisma ORM for developer happiness)

## Maybe
Need to show personal correlations which none of these apps do. Take user data and be able to give them actual insights into how they feel and what they should do instead of just presenting them with raw data.
