---
layout: post
title: Reflection on the NHL API Vignette Project
---
[Github Pages Repo] (https://kaslemr.github.io/NHL-API-Vignette/)


• explaining what you did in the project and any findings you made
• You should also reflect on the process you went through for this project. Discuss things like:
– what would you do differently in approaching the project?
– what was the most difficult part of the logic and programming for you? – what are your big take-aways for future projects?

This project was a lot of fun to take part in. My process for this project began with exploring the NHL APIs in an R file. Once I understood the structure of the API, I began writing helper functions. I started with simple functions to return tibbles from an API call. Then, I started to build complexity. I wanted to utilize functions to split up responsibilites. The Records API was relatively simple but the Stats API had more complexity, especially when it came to expanding dataframe results that were nested within an initial return. 
<br />
<br />
Once I had my wrapper function coded, it was relatively easy to start the the data exploration.  I think this is a great way to go about data exploration in general - creating helper functions in the beginning can be an investment but save  time in the long run.

With so much data available, it was really difficult to decide what to focus on in my data analysis. I think this is an area where I could improve next time - I ended up wanting to explore a variety of tables but would rather dig in deeper to a subset next time.  Perhaps I would start with a few hypotheses and explore the data this way, ending up with a few conclusions about the data.


