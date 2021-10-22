# CERTH – Unity Coding Challenge

This is a small project that needs to be implemented using the Unity game engine (use the latest LTS version). Below you will find a detailed description of the tasks that need to be completed. Feel free to ask any questions that might arise.


<img src="https://ih1.redbubble.net/image.660179165.4706/flat,750x,075,f-pad,750x1000,f8f8f8.jpg" alt="SPKSZN" style="width:300px;text-align:center;"/>

## Project Description

Happy Halloween! It's #SpookySeason and you'll be creating a world were zombies are dominating. In this terrifying place zombies in multiple colors are spawning everywhere, and they're walking around unbothered.

There are three buttons: one for every zombie color (green, purple and red). Every time the user presses on one of the buttons, a zombie with the corresponding color will spawn in a random location on the `MainScene` and start walking around (make sure they don't fall over the edges of the ground).

## Implementation Instructions
- Create 3 different materials (one for each zombie color)
- Create 3 buttons and place them on the bottom of the screen
- Implement the C# scripts that handle the spawning of the zombies on every button click
- Implement the C# script that handle the movement of the zombies
    - This `MonoBehaviour` script will have a `public float` variable named `speed` which can be changed to affect the speed in which the zombies are walking.
- Attach the appropriate animation components to the zombies so that they start walking around

## Provided Assets
- `/Materials/Ground` - A ground material (you can use this as a base to create your zombie color materials)
- `/Avatars/Zombie` - This is the zombie 3D model you will use
- `/Animations/ZombieAnimator` - A component that can be used to animate your zombies
- ~~`/Animations/MixamoWalking`~~ - You will probably not use this for your solution

> Good luck! :D

## Submission Instructions
1. Fork this repository
2. Open the Unity project using your Unity Editor
3. Implement your solution
4. Push your solution to your repository
5. Send us a link to your repository accompanied with a short video illustrating your implementation