# Telekinesis-2022


Telekinesis is a project I made during my Game Design studies.
The main purposes were learning Unreal Engine then implementing and polishing a game mechanic.

The mechanic I chose was the telekinesis we can experience in Control from Remedy Entertainment:
1) Grabbing an object		
2) Making it levitate		
3) Throwing or releasing it	

![telekinesis-example (1)](https://user-images.githubusercontent.com/96313983/187085531-8579e051-54da-4ced-afad-2f576afe5901.gif)



### Prototyping

The visual scripting helps a lot to prototype fast without creating script files. Fortunately, I could previously test it on Unity as they did an equivalent job as Unreal so I could find quickly the nodes I needed.

In my opinion, blueprint nodes are the best part of Unreal but the worst part is the Actor hierarchy management. I prefer the simplicity of Unity's GameObject for this point.

For example, I created a basic enemy which becomes a ragdoll when it's hit by a thrown object. 
The most difficult part was changing the enemy blueprint into an Actor that can be grabbed by the player.
Due to the differences between a simple mesh like a chair and a complex object like the ragdoll, I spent 2 days to make it work but I succeeded.

![telekinesis-blueprint (1)](https://user-images.githubusercontent.com/96313983/187086223-2fdbf699-9094-46bf-afb3-a7aae4514f16.jpg)

> The complexity of grabbing/releasing in visual scripting

<br>

<img width="400" src="https://user-images.githubusercontent.com/96313983/187086160-564fed8b-11d9-4fcc-9759-cec5d2aa90a8.jpg">

> The level blockout

<br>

<img width="400" src="https://user-images.githubusercontent.com/96313983/187086333-08583659-72ad-42b5-ae47-3694fbd5c135.jpg">

> Comparison with the original game



### Required skills

- Unreal Engine 4:
  - visual scripting (blueprints)
  - player controller
  - physics / collisions / ragdolls
  - input system (keyboard/mouse and gamepad)
  - UI (with dynamic switching depending on the controller)
  - navigation mesh (for ennemies)
  - audio management
  - optimisations / balancing
  

### How I made the prototype

https://sites.google.com/view/alubecki-lead-developer/my-portfolio/telekinesis
