# Optimized-Pathfinding-for-Safe-Navigation-in-Flooded-Urban-Environments-Using-Grid-Based-Scoring
### Problem Statement:
Assume you are in your office in Nellore, Andhra Pradesh. The city is facing heavy rains 
due to Cyclone Michaung. Most of the areas are inundated with water. You need to reach 
home safely. You have a navigation agent which you can use to find the safe routes without 
water. The agent is fed with the city map marked with flood areas. The agent must 
find the route that is the safest to take you home by choosing the next grid, considering 
different factors. 5 points to be added each time the agent passes adjacent (Up, Down, Left, 
Right) safe places and 5 points to be deducted while the agent passes near water bodies, 
and 3 points to be deducted if the roads in the area are flooded with water. The following figure 
gives the initial grid positions. The desired solution must have maximum points, but must have 
travelled through a smaller number of squares. The environment is fully observable. The 
agent travels on empty cells, and the water bodies and flooded areas are marked as 
blockades. You cannot travel through them, but can travel adjacent to these cells. No diagonal 
movements are allowed
![image](https://github.com/user-attachments/assets/50ea59d5-42d5-4d2c-aaf1-bf30147abcd8)
![image](https://github.com/user-attachments/assets/7f1bdca4-8847-4da1-b736-85822105c536)

### Algorithm Used
- GREEDY BEST FIRST SEARCH ALGORITHM
- GENETIC ALGORITHM
- 
### List the PEAS description of the problem here in this markdown block:

#### Performance Measure:
- The primary goal is to reach home safely with the maximum number of points while avoiding flooded areas.
- Performance can be measured in terms of the number of points accumulated and the number of grid squares traversed to reach home.
- Additional performance measures could include the time taken to reach home and the accuracy of the agent's navigation.

#### Environment:
- The environment is the city of Nellore in Andhra Pradesh during heavy rains caused by Cyclone Michaung.
- The environment consists of a grid layout representing different areas of the city, some of which are flooded while others are safe for traversal.
- Each grid cell can be in one of three states: safe, flooded, or road flooded.
- The environment may change dynamically as the cyclone progresses, affecting the flood levels in different areas.

#### Actuators:
- The agent can move in four directions: up, down, left, and right.
- The agent can also assess the safety of adjacent grid squares and make decisions based on this assessment.
- Actions could also involve evaluating the severity of flood conditions and deciding whether to wait for the water levels to decrease or to find an alternative route.

#### Sensors:
- The agent has sensors to perceive the grid layout and detect flooded areas and safe passages.
- The agent can also detect its current location on the grid and assess the safety of adjacent squares.
- Sensors may provide information about the depth of water in flooded areas and the likelihood of roads being impassable due to flooding.
- The agent's sensors may also provide real-time updates on weather conditions and flood warnings from meteorological sources.
