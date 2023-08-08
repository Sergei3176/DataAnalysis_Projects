# PROJECT: Analyzing Data in a StackOverflow Database.

## DATA:
Database (five tables) containing information about user posts on StackOverflow (Russian segment) for 2008 and ratings of these posts, including those made after 2008. It contains information about users, about posts, and about votes for posts. About the labels that users give to posts and about the achievements of users on the service.

## THE GOAL OF THE PROJECT: analysis of user activity on StackOverflow in 2008.

**During the study, the following work was done:**

- Revealed the number of views for each month;
- Identified user activity in the first month after registering on the site;
- Calculated the number of posts for 2008 by months;
- Identified the dynamics of posts for each user, with accumulation;
- Calculated the average number of posts per user in August;
- Identified the history of each user's activity with the addition of information about the month of the penultimate publication of the user, relative to the current one;
- The retention of site users by months was calculated, a heatmap was built, and anomalies were analyzed;
- The dynamics of changes in the number of posts by months for the period from September 1 to December 31 was calculated, and a pie chart was built with the number of posts by months;
- Displayed activity data in October for the user who published the most posts of all time.

## Main acquired skills:
Database connection. Writing queries in PostgreSQL (subqueries, window functions), building a heatmap and pie-chart.

## Libraries used:
Pandas, sqlalchemy, Seaborn, Plotly.

## Status:
Completed