# Thomas Reis' Github Portfolio
My Portfolio
# Machine Learning/AI Items
## AI-Final 
A target finding game played entirely by AI with a variety of features and implementations made to ensure that the AI had some resemblance of a real scenario. Each AI has a goal to obtain their personal 5 targets within the game board, the only way to obtain them is to walk over them within a 20 tile radius. The AI are equipped with a radar-like device that can view all around them and they can find and remember the locations of their targets as well as their opponents targets.
* Features 3 Game Modes (Cooperative, Competitive, and Compassionate)
* In Cooperative the AI will share every target they find with their respective owners
* In Competitive the AI will trade with one another in an attempt to stay in the game. But will avoid trades that will cause them to lose the game
* In Competitive the AI will also lie if their happiness rating (see below) goes low enough
* In Compassionate the AI will give out targets to other AI who are losing (unhappy, see below)
* The Happiness rating is a measurement used to determine if an AI is finding their targets successfully. It is measured by the following: (# of targets collected)/((# of steps taken + 1)x(Maximum Happiness so far)). As such agents get unhappy if they wander a lot and fail to obtain any targets
* Using these measurements and game modes we did some data processing on the results of the different game modes and user happiness values and determined that they were most unhappy when competitive and lied the most in that game mode, and were most happy in the cooperative game mode
The following is a GIF of one run of the game where the AI in competitive mode  
![Alt Text](https://i.imgur.com/2alhh68.gif)

## Blackjack-AI
A personal project created for the reverse career fair at UOIT in Fall 2018. A simple blackjack AI that used simple probability to determine what moves to make to avoid losing.
  
## Number Recognizing Neural Net
A neural network created using tensorflow that enabled the identification of numbers based on set requirements for the project. Was able to recognize numbers that were corrupted or poorly drawn as well.
  
# Cloud Computing/Full Stack Items
## Cloud-Computing-Final
A lightweight website Designed to allow students to create portfolios of their projects, and for employers to easily search and discover potential new employees upon graduation or for internships/co-ops.

## Renofai (Not Listed)
Renofai is not listed on the repos due to the potential for monetization for the project, and the client does not wish to have the code publicly displayed at the moment.

# Other Projects
## Distributed K-Means++ (Data Mining/Distributed Computing)
The final project for distributed computing where we implemented the K-Means++ classification algorithm into a distributed environment using JeroMQ (ZeroMQ but for Java) using the MQTT protocol of pub/sub to distribute data to classify.

## Comparative Study of PSO (Particle Swarm Optimization) and DE (Differential Evolution). (Not Listed)
The repo for this project is unlisted as I did not create it, it was a group project, and it is currently private.
