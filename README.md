neotracker

an application that tracks and monitors guild activity. check out the live site here!

guest credentials
username: guest
password: password
porpoise 🐬
Maintaining a guild in Neopets is a legit job. You have to be quick to address faltering member activity and see what events work and what events don't.

A member's activeness in a guild is primarily determined by the number of posts they've over a period of time. Neopets has a dedicated page for every guild that lists the total number of posts a person has made in the guild at the moment you check this page. The picture below is a screenshot of how it appears.



The original way I took to keeping track members' activeness is have a google sheet and manually enter each member's post count. In the next month, I then look up the total number of posts they've made and subtract it from the previous amount. Besides the obvious issue of this task being super tedious, there are also other issue where if a user has left the guild and I no longer need to look it up or this information doesn't really show how active the guild is throughout the specific days in a month. Rather, it just tells me which members are most active.

To remedy this, I decided to create an application that visualizes and monitors member activity. It tracks how many members posted, and who are posting.

This will give me and other council members a better idea of how the guild is performing and when and allow us to make connections how the guild activity corresponds to how much effort we are putting in.

uml component diagram 📈
uml component diagram

er diagram
ER diagram

challenges
Parsing through Neopets was hard.
Figuring out how to display the data on the graph AND the neomail was difficult.
Setting up the database was also difficult.
mockup 🎨
    

to do
 fix monitor.js so that it accounts for when there is a poll, which means we have to look at the 15th table, not 14th)
 fix the neomail layout
 allow admins mark members inactive/active in the application
