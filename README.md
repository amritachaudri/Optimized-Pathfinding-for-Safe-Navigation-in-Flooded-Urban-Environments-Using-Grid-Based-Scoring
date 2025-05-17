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
