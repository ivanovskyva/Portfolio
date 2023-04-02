# Dashboard for Yandex.Zen
## Data
Aggregating table with records of events in Yandex.Zen cards.
## Project description
The task of this project is to create a tool for weekly analysis of user interactions with Yandex.Zen cards.
I worked on this project on a remote machine in the Yandex.Cloud service. I
installed PostgreSQL and deployed the database. Then I wrote a pipelining script,
that allowed me to collect data for a certain time period, and I configured it
offline operation via crontab. To visualize the collected data, I wrote a
dashboard script with several filters and also ran it on a remote machine. 

On the results was prepared a presentation with the obtained graphs, the dashboard is published in Tableu.
