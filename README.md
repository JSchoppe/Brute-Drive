# Brute Drive
The heist went according to plan, now it is up to you to get the team back to headquarters by evading the police at all costs. Drive along procedurally generated routes in real world locations while using your wits or simply brute force to escape the long arm of the law.

<details>
<summary>Long Description</summary>
<br>
 
Brute Drive will focus on a few key aspects of gameplay:
## 2D Driving Mechanics
Good driving should implement enjoyable acceleration, steering, and drift sliding.
Vehicles should collide in a way that is impactful bu not neccasarily realistic.
## Maps Driven Generation
Google Maps will be used to generate a route for the gameplay to take place on.
A good implementation of this generation should feature meaningful analysis of
streets to find a fun route, and addition/removal of elements to clean up the
areas that gameplay will occur in.
## Adversarial AI
AI should attempt to destroy the player's vehicle, and should pose a real threat
given a reasonable route generation. AI should spawn predictively to cut off the
player or give them an opportunity to smash through.

</details>

Genre: Arcade Racer | Smash'em Up
Platform: Android

# Development Logs

# Proposal Details
This section outlines the initial proposal for this project. Each milestone is estimated to be about 3 weeks in duration. With a total project duration of about 2 months.
## Proof of Concept
This milestone will feature modeling of the driver controller for the player and AI, such that vehicles can interact with each other and the world in a very basic way. An algorithm will be developed to randomly choose a non-intersecting route through the recieved graph from google maps. Basic modifications will be made to the map to add colliders around the chosen route.
## Vertical Slice
In this milestone the gameplay loop will be more fleshed out with basic vehicle damage implemented. Wrecks will be given a lightened weight so that they can be pushed out of the way by the player. Player will be able to complete a run from start to finish (on a prechosen map), and will also be able to fail a run if their vehicle recieves too much damage.
## First Build
Player will be able to choose the coordinates, or use current coordinates, to generate a stage. Generation should be tested against numerous different street layout archetypes to locate generation and behavioural bugs. AI will be fine tuned to be more reactive and predictive of the player's actions.
## Cleaned Up and Documented
Fix lingering bugs and improve the gameplay polish. Clean up technical debt as time permits.
