# Open Program

## Brawlhalla AI
The initial plan of my Open Program was to make progress in the Brawlhalla AI project (trying to use Reinforcement Learning). This didn't really workout due to very stupid and less stupid error I ran into. Instead of using Reinforcement Learning for Brawlhalla, I tried using it for the Cart Pole Game. I ran into the same stupid errors so I stopped and just left it and decided to not deliver anything for my Open Project, untill...

## Cart Pole Game
I was so frustrated because I understood all the theory behind Reinforcement Learning, but the code just wouldn't work for me. (I later found out why it didn't work. I tried using an older version of tensorflow on a very new version of python, but that won't work. You will have to downgrade python in for example a virtual environment but I wasn't thinking this much at the time). So I decided to write my own self-learning algorithm. this was pretty much a succes.

### Notebooks
All 3 notebooks described shortly,
- [cart-pole-game-v2 (part 1)](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Open%20Program/notebooks/cart-pole-game-v2%20(part%201).ipynb): In this document I explore making models that learn by using the pole angle or pole speed or both of these variables at the same time. These gave pretty good results. This document is very messy, it used to be even more messy but I managed to clean it up a bit. The reason I didn't fully clean up my notebook is so that you can actually see the process and progress I made in steps.
- [cart-pole-game-v3 (part 2)](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Open%20Program/notebooks/cart-pole-game-v3%20(part%202).ipynb): In this notebook I tried to make models based purely on *Am i game over or not?*. I also looked multiple frames into the future but surprisingly it didn't work. I was actually so confused because everything went right and felt like it should work.
- - [cart-pole-game-presentation](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Open%20Program/notebooks/cart-pole-game-presentation.ipynb): The notebook I used for my presentation when I presentated my Open Program to my teachers. This uses the models created in [cart-pole-game-v2 (part 1)](https://github.com/School-Semester-Summaries/AI-semester-4/blob/main/Open%20Program/notebooks/cart-pole-game-v2%20(part%201).ipynb)
