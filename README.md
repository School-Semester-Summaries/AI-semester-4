# Semester 4 - Artificial Intelligence
Here you see an image of a few products I worked on this semester. Going from left to right, Brawlhalla AI, Cart Pole Game, [Dadabase](https://github.com/Skyward-Brawlhalla/Dadabase), [Ranknir](https://github.com/Skyward-Brawlhalla/Ranknir), Brawlhalla Classification, Jugo Project

![image (1)](https://user-images.githubusercontent.com/74303221/214144301-e5bc05ce-9cef-476e-8499-7650b5c25861.png)

# Table Of Contents
- [Preface](#preface)
- [Semester structure](#semester-structure)
- [Individual Projects](#individual-projects)
  - [Brawlhalla AI]()
  - [Brawlhalla Legend Classification]()
- [Group Project](#group-project)
- [Open Program](#open-program)
- [Personal Developement Report](personal-developement-report)
- [Side Projects]
  - [Dadabase]()
  - [Ranknir] 
- [Epilogue](#epilogue)

# Preface
In this semester I got an introduction to AI. Everything that I have done this semester is explained in my [PDR]. Looking for the work itself, don't worry it will also be mentioned below.

# Semester structure
As you can see in the image below, the first 12 weeks is 4 days individual project, 1 day group project. After these weeks, we have 4 weeks group project. In the end we have 2 weeks Open Program. Open program isn't the same for everyone. If you hit every section inside Machine Learning, DAIA (idk what this stands for 😭) and Societal Impact sufficiently, you can do whatever you want in these 2 weeks. If not, you could choose between 2 exexrcises.

![image](https://user-images.githubusercontent.com/74303221/214136495-0e8257a7-9070-4faa-8144-96c2dd175921.png)

# Individual Projects
This semester I first wanted to create a RL agent that could play Brawlhalla. This didn't really work out, so I did something easier. Image classification but with Brawlhalla Legends.

## Brawlhalla AI
### Reinforcement Learning
The idea was to create an application that would be able to play the 2d platform fighting game Brawlhalla. I did research to figure out how I could create the AI and what resources were necessary. This brought me to Reinforcement Learning. Reinforcement learning is a training method that learns by itself how to act, when some kind of input is provided. For example, in my case, reinforcement learning would help my fighting-game-AI how to knock out its opponent, ìf I would give it some game-related-information. But the problem with reinforcement learning was that I had no game-related-information for it to base decisions off. There is of course the code of the game somewhere running in the background wherein all live game information is running, but it was nearly impossible to reach. So I had to find a way to obtain game-related-information in some way, so I have input for my AI. This is where the second part of the project came into play.

### Object Detection
After some more thinking and researching, I came up with the idea to generate my own game-related-information. This was possible using Object Detection. Object detection is a technique to scan for objects on your screen. You might have seen object detection in your life before. It’s the same technology China uses to identify humans and track them. So object detection looked like the way to go. Sadly after trying for 2 weeks straight. It just wasn’t working out. But while trying to get object detection working. I ended up finding something pretty useful by accident.

*Labelling images so later on we can train a model to detect the legends. This way we can get the locations of the legends on screen without entering the game's source code* 

https://user-images.githubusercontent.com/74303221/214147621-734b0c4e-afef-4f98-bee0-ff310f8e4edb.mp4

### Object Tracking
Whilst trying to find out how to get object detection working, I found a tutorial on object tracking. Object tracking is a technique that checks for moving pixels on your screen. You could also tune it, for example the minimum area of moving pixels. So doing some tuning, Everything I wanted to detect got detected: legends- moving, attacking, getting damage, giving damage and weapons spawning. All important factors were being tracked so it looked perfect. But the problem here was that there was almost no data involved in the project. And that would mean I had to do another project. So the thing I feared but already saw coming finally happened. I decided to drop the project.

*This is somewhat what I tried to reach with the Object Detection part, only now it just checks pixels on the entire screen. This program also outputted the locations of the green boxes so this was pretty much a succes*

https://user-images.githubusercontent.com/74303221/214147933-c544aa1b-a05d-4602-9e80-12a3b391bd0b.mp4

