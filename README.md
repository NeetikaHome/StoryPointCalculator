# StoryPointCalculator
Algorithm to Calculate the story Points 

## What is a Story Point 
 -  Story points are a tool to determine the velocity of teams.
 -  Velocity is a relation of complexity and effort.
 -  Complexity is a feature of the story. Effort, on the other hand, points to a property of the DevTeam.
 -  Story points represent the complexity of a story in relation to its effort.


## Calculate the story points  
  
  **one** = (Similar Example Exists -> Yes = 0, Partially => 0.5 , No => 1)
 
  **two** = 0.25 * How many repos need to change
  
  **three** = 0.25 * no of interaction points(external dependencies)
  
  **four** = (How many devs know the source code => 100% = 0, More than 50% = 0.5, Less than 50% = 1, No one knows the code = 1.5)
  
  **five** = No of man days  development required  ( Decided by the developer who knows the best, else average of what the team thinks. The best case scenario)
 
  **six** = (Risk Level -> High = 1, Medium = 0.5 , Low = 0)
 
 ```
 Story Point =  one + two + three + four + five + six
 ```
