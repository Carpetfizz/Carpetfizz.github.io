---
layout: post
title: "Recycled"
category: project
coverimage: recycled.jpg
technologies: [Python, Google App Engine,Bootstrap, Angular.js]
---

Determined to solve the lack of recycling at our high school, my friend and I decided to gamify the process. My friend was able to acquire recycling bins from the city of San Jose, and I taped QR codes to them. The idea was that students would throw something in the bin and scan the QR code on the bin. The code would make an API call to the Python server running on GAE, authenticate the Google account, and add a point to the student's score. The leaderboard was meant to encourage students to compete against eachother for the monthly prize.