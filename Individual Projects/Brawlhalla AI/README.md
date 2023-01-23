# Brawlhalla AI

## Table of Contents
- [Preface](#preface)
- [Reinforcement Learning](#reinforcement-learning)
- [Object Detection](#object-detection)
- [Object Tracking](#object-tracking)

# Preface
What you will read below is a copy paste from my project description from my [PDR](). Is this not quite what you are looking for?
- More details about the project -> []()
- Object Tracking code -> [Object Tracking Notebook](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Individual%20Projects/Brawlhalla%20AI/object-tracking.ipynb)

### Reinforcement Learning
The idea was to create an application that would be able to play the 2d platform fighting game Brawlhalla. I did research to figure out how I could create the AI and what resources were necessary. This brought me to Reinforcement Learning. Reinforcement learning is a training method that learns by itself how to act, when some kind of input is provided. For example, in my case, reinforcement learning would help my fighting-game-AI how to knock out its opponent, ìf I would give it some game-related-information. But the problem with reinforcement learning was that I had no game-related-information for it to base decisions off. There is of course the code of the game somewhere running in the background wherein all live game information is running, but it was nearly impossible to reach. So I had to find a way to obtain game-related-information in some way, so I have input for my AI. This is where the second part of the project came into play.

### Object Detection
After some more thinking and researching, I came up with the idea to generate my own game-related-information. This was possible using Object Detection. Object detection is a technique to scan for objects on your screen. You might have seen object detection in your life before. It’s the same technology China uses to identify humans and track them. So object detection looked like the way to go. Sadly after trying for 2 weeks straight. It just wasn’t working out. But while trying to get object detection working. I ended up finding something pretty useful by accident.

https://user-images.githubusercontent.com/74303221/214147621-734b0c4e-afef-4f98-bee0-ff310f8e4edb.mp4

*Labelling images so later on we can train a model to detect the legends. This way we can get the locations of the legends on screen without entering the game's source code* 

### Object Tracking
Whilst trying to find out how to get object detection working, I found a tutorial on object tracking. Object tracking is a technique that checks for moving pixels on your screen. You could also tune it, for example the minimum area of moving pixels. So doing some tuning, Everything I wanted to detect got detected: legends- moving, attacking, getting damage, giving damage and weapons spawning. All important factors were being tracked so it looked perfect. But the problem here was that there was almost no data involved in the project. And that would mean I had to do another project. So the thing I feared but already saw coming finally happened. I decided to drop the project.

https://user-images.githubusercontent.com/74303221/214147933-c544aa1b-a05d-4602-9e80-12a3b391bd0b.mp4

*This is somewhat what I tried to reach with the Object Detection part, only now it just checks pixels on the entire screen. This program also outputted the locations of the green boxes so this was pretty much a succes*
