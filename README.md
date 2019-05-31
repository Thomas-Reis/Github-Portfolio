# Thomas Reis' Github Portfolio

# Table of Contents
[Machine Learning/AI](#ml-ai)  
* [Target Finding AI](#ai-final)  
* [Blackjack AI](#blackjack-ai)  
* [Number Recognizing Neural Network](#neural-net)

[Cloud Computing/Full Stack Items](#full-stack)  
* [Portfol.io](#cloud-computing-final)
* [Renofai](#renofai)

[Other Projects](#other-projects)  
* [Distributed K-Means Classification](#d-k-means)
* [DE VS PSO Benchmarking](#de-pso)

# Machine Learning/AI Items <a name="ml-ai"/>
## AI-Final <a name="ai-final">
A target finding game played entirely by AI with a variety of features and implementations made to ensure that the AI had some resemblance of a real scenario. Each AI has a goal to obtain their personal 5 targets within the game board, the only way to obtain them is to walk over them within a 20 tile radius. The AI are equipped with a radar-like device that can view all around them and they can find and remember the locations of their targets as well as their opponents targets.
* Features 3 Game Modes (Cooperative, Competitive, and Compassionate)
* In Cooperative the AI will share every target they find with their respective owners
* In Competitive the AI will trade with one another in an attempt to stay in the game. But will avoid trades that will cause them to lose the game
* In Competitive the AI will also lie if their happiness rating (see below) goes low enough
* In Compassionate the AI will give out targets to other AI who are losing (unhappy, see below)
* The Happiness rating is a measurement used to determine if an AI is finding their targets successfully. It is measured by the following: (# of targets collected)/((# of steps taken + 1)x(Maximum Happiness so far)). As such agents get unhappy if they wander a lot and fail to obtain any targets
* Using these measurements and game modes we did some data processing on the results of the different game modes and user happiness values and determined that they were most unhappy when competitive and lied the most in that game mode, and were most happy in the cooperative game mode
* uses the A* searching algorithm to determine an optimized path of where to head based on the locations the AI hasn't been

<a/>
The following is a GIF of one run of the game where the AI in competitive mode  

![AI GIF](https://i.imgur.com/2alhh68.gif)
* When one goes green that means it knows where one of its points are and is pathfinding its way to it (it could have traded)
* When one goes red that means it is in a collision with another AI and the 2 must attempt to get away from one another
* When one is white that means it is simply wandering
* The (number) symbols around are where the AI is headed next, it is a simple way to view how it thinks and moves
* The symbols around are the targets themselves labelled with: (AI #)-(Target#) (eg. 3-0 is AI 3's target 0, each agent has their own targets labelled 0 - 4)

## Blackjack-AI <a name="blackjack-ai"/>
A personal project created for the reverse career fair at UOIT in Fall 2018. A simple blackjack AI that used simple probability to determine what moves to make to avoid losing.
  
## Number Recognizing Neural Net <a name="neural-net"/>
A neural network created using tensorflow that enabled the identification of numbers based on set requirements for the project. Was able to recognize numbers that were corrupted or poorly drawn as well.

### VISUAL HERE
  
# Cloud Computing/Full Stack Items <a name="full-stack"/>
## Cloud-Computing-Final <a name="cloud-computing-final"/>
A lightweight website Designed to allow students to create portfolios of their projects, and for employers to easily search and discover potential new employees upon graduation or for internships/co-ops.

### VISUAL HERE

## Renofai (Not Listed) <a name="renofai"/>
Renofai is not listed on the repos due to the potential for monetization for the project, and the client does not wish to have the code publicly displayed at the moment.

### VISUAL HERE

# Other Projects
## Distributed K-Means++ (Data Mining/Distributed Computing) <a name="d-k-means"/>
The final project for distributed computing where we implemented the K-Means++ classification algorithm into a distributed environment using JeroMQ (ZeroMQ but for Java) using the MQTT protocol of pub/sub to distribute data to classify.

### VISUAL HERE?

## Comparative Study of PSO (Particle Swarm Optimization) and DE (Differential Evolution). (Not Listed) <a name="de-pso"/>
The repo for this project is unlisted as I did not create it, it was a group project, and it is currently private.
