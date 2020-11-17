![WhatsApp Image 2020-11-17 at 01 43 19](https://user-images.githubusercontent.com/58064644/99323555-257d7700-287b-11eb-81b1-cad4ac28935a.jpeg)
##### Submit: Shahar Glikman & Salome Nizard & Shira Zadok

## Question_1_2

# spaceship game

In this project we worked on a game called "spaceship game".
In the game the player confronts enemies coming down from space.
The player shoots with a laser in order to kill the enemies (In a scene - 4 level1_1).
In the begin of the game the player gets 3 lives and every time the player collides with the enemy the amount of life decreases.
The code responsible for the player's life is called "Destroy _player".
In addition, there is a feature that allows the player to pass a stage only if the points tax he has accumulated is greater than 5 points.

This can be seen in the code 'GotoNextLevel'.

For this feature called:
The code use  the static variable that counts the points.

https://shahar-shira-salome.itch.io/spaceshipques1 - itch.io
![ques1](https://user-images.githubusercontent.com/58064644/99323561-2910fe00-287b-11eb-8344-58b5651e6d71.png)


### Scene - level_4_wall:
In this scene we created 4 walls that restrict the movement of the player.
When the player hits in the walls, he will not be able to get through them.
That when the player detects a collision in one of the walls, he is restricted by them.

This can be seen in the code 'on_Trigger_wall_block'.

https://shahar-shira-salome.itch.io/spaceshipques2   - itch.io
![queswall](https://user-images.githubusercontent.com/58064644/99323563-29a99480-287b-11eb-9bdc-066bd05cc39d.png)

### Scene - expose_on_trigger:
We created invisible borders so when the enemies and the laser try to cross the border they were destroyed.
In the code it can be seen that when there is a collision with the border, they are destroyed.

This can be seen in the code 'Enemy_Trigger_wall'.
![expose](https://user-images.githubusercontent.com/58064644/99323529-1d253c00-287b-11eb-9d78-cd2abcaf9e87.png)

### Scene - circle_world:
We created a round world when a player exits one border he returns from the other border.
For example: if the player exits the right side of the screen he will return from the left side and the same to the other sides.

This can be seen in the code 'Trigger_world_circle'.
![circle](https://user-images.githubusercontent.com/58064644/99323558-26160d80-287b-11eb-9ae8-8d4c79194594.png)

## Question_3

![JumperFrog](https://user-images.githubusercontent.com/58064644/99383112-17a90f80-28d6-11eb-8a9b-c8bdcfe3f806.png)


# Jumper Frog
In this game we created a core process where the frog should reach the finish line without being hit by cars and without exiting the road boundaries.
![playerFrog](https://user-images.githubusercontent.com/58064644/99383130-1ed01d80-28d6-11eb-998b-29c041838da3.jpeg)

https://shahar-shira-salome.itch.io/frog
### Frog Loose
When the frog goes beyond the game limits, the frog will be moved to a scene 'FrogLoose'.

The player will have to start the game again.

This can be seen in the code 'GoNextLevelFrog'.
![looseFrog jpeg](https://user-images.githubusercontent.com/58064644/99385009-031a4680-28d9-11eb-97a3-e48f9450ac03.png)

### Frog Win
If the frog manages to reach the finish line, he moves on to the scene 'Frog Win'.

This code responsible for moving it to the next scene.

This can be seen in the code 'GoNextLevelFrog'.
![winFrog](https://user-images.githubusercontent.com/58064644/99383140-2263a480-28d6-11eb-825e-552e52b79c1b.jpeg)

In the scene there is a car object which moves towards the frog.

In addition, the car has a code responsible for duplicating the car.

This can be seen in the code 'TimespawneCar'.
