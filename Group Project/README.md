# Group Project

## Table of Contents
- [Preface](#preface)
- [JUGO Project](#jugo-project)

# Preface
What you will read below is a copy paste from my project description from my [Personal Developement Report (PDR)](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Personal%20Developement%20Report/PDR_v4.3.pdf). If this is not quite what you are looking for you can check the links below.
- More details about the JUGO Project -> [JUGO Project Document](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Group%20Project/documents/Project%20Plan%20Jugo.pdf)
- Our code -> [Notebooks](https://github.com/School-Semester-Summaries/AI-semester-4/tree/main/Group%20Project/notebooks)
- All data we have used -> [data](https://github.com/School-Semester-Summaries/AI-semester-4/tree/main/Group%20Project/data)

# JUGO Project
The JUGO project is the group project I worked on this semester. Inside this project, we
show the fastest route from point A to point B. For better visualisation you can compare it
to google maps. Next, we would also make predictions if there is a traffic jam on the roads
you pass. And if there was a traffic jam, it would also tell you till when. We accomplished
this by using a dataset containing traffic jam information, like when there is a traffic jam,
the cause of the traffic jam, and so on.

Predicting when there would be a traffic jam was kind of a problem. That is because our
dataset is full of when there ìs a traffic jam, not when there isn’t. To solve this we created a
script that would generate the data of when there isn’t a traffic jam. But this only solved
half the problem. The other problem was that we wanted to predict how long a traffic jam
would last, but we didn’t have the required data for it. To solve this we used a second
dataset. By combining the 2 datasets into one dataset, we solved the biggest problems of
our project.
