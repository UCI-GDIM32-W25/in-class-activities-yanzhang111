# GDIM32 In Class Activities
## Devlogs
### W2
#### Activity 1
![7ec846826fdec83688c0ded4aec9c0e6](https://github.com/user-attachments/assets/bcc2dc30-c098-444c-a054-9bd39f066e75)

#### Activity 2
I've already set up the game's basic framework and the code structure. Now I just need to write according to these.
[MG2](https://github.com/yanzhang111/mg2-yanzhang111/commits/9ece3cce6565ddc4f0f9972493e40f632044a3cb/)


### W3
#### Activities 0-2
I work with Ruixuan Pan


### W4
#### Activities 0
I work with Ruixuan Pan


#### Activity 1
This code writes a method and then corresponds to all game objects. After running the game, all locators will be deleted and only one will be left.


#### Activity 2
![696aa75899c9f43472a4bdf894eb5627](https://github.com/user-attachments/assets/c0f91d47-18d6-45a7-ac71-34c2a8280b39)


#### Activities 3
I have built the basic framework, and the materials of water pipes and birds have been imported and cut.
[MG4](https://github.com/yanzhang111/HW4/commits/main/)


### W5
#### Activities 1
I think the design is pretty clear. Item handles using items, and IBreakable handles breaking, so the roles are easy to understand. It also makes sense that ElvenSword is not breakable. For a real project I might clean up the durability logic, but for this assignment the design works fine.

#### Activities 2
Model: Item.cs, Enemystats.cs
View: DialogueBubble.cs, Inventory.cs
Controller: Enemy.cs, Player.cs

#### Activities 3
Scenario 1


scriptableobjects: each button (sprites, _movespeed)
finite state machine: player whether missed button & different scores each button will give
model-view-controller:
    - model: list of buttons(buttons)
    - view: score UI, time count down
    - controller: response to player's finger, 
singleton: locator of player
inheritance: button move to a place, button disappear and add scores.


Scenario 2


Abstract Character base class for health and movement

Ability interfaces for unique skills

FSM with states like attacking and reloading

ScriptableObjects for skill data

Polymorphism for character behavior



Scenario 3

Base FarmObject abstract class

Interfaces for plant, harvest, break

ScriptableObjects for item data

MVC with events for interactions

Inheritance and composition for expansion


#### Activities 4
Attendance：Yuxin Ding, Tina Zhang, Yan Zhang


Proposl：https://docs.google.com/document/d/1oGQXyqTOWLLG3tDOO_RGtfLVnASe5ZuaAI4uGt-2Nhs/edit?usp=sharing


### W6
#### Activities 1
1.Gizmos can intuitively see some content that Ican't usually see in the Scene view, such as the interaction range, direction line or detection area. So I think in my Final Project, I should use Gizmos to show the range of interaction that players can interact with cats or items, so that I can quickly check whether the distance is appropriate.


2.The Profiling can show the usage of CPU and memory when the game is running, so if the game drops frames or runs slowly, I can use this tool to check whether some scripts or animations consume too many resources and optimize them.


3.The function of Breakpoints is to pause the program at a specific code line to facilitate the gradual check of the numerical and logical flow of variables. This will be more useful when debugging the task system. In I ours project when the task is not completed after feeding the cat, it can be detected through this tool!(maybe?)


4.Merging is talking about how to avoid merge conflict when saving codewith multiple people.


#### Activities 2
Attendance：Yuxin Ding, Tina Zhang, Yan Zhang


Proposl：https://docs.google.com/document/d/1oGQXyqTOWLLG3tDOO_RGtfLVnASe5ZuaAI4uGt-2Nhs/edit?usp=sharing


### W7
#### Activities 1
1.Finite state machine + Raycast + SphereCast control NPC behavior


2.In the Duck script, two states are defined with enum: Wandering and Pursuing. In Update, the status is first judged and then the corresponding logic is run. The core basis of state switching is whether you can see players with Raycast.


3.See the player → turn to the player and move/ Can't see the player → Walk randomly + use SphereCast to avoid obstacles



#### Activities 2
Attendance：Yuxin Ding, Tina Zhang, Yan Zhang


#### Activities 3
![c563dcaaffee7122c45c141ec13762d0](https://github.com/user-attachments/assets/66488fc7-fbb2-448c-b55f-b41e52075746)


#### Activities 4
[Trello board](https://trello.com/invite/b/69951b72679c6bfc86fd7473/ATTIe547f99dbf7fa8572d46a2e45aa571b50E2DB6C9/gdim-32-final)


#### Activities 5
[Final project](https://github.com/tinamengxq/GDIM32-Final/commits/main/)
schedule the plan for final project, create play.cs,start to work.


### W8
#### Activities 1
The common rendering pipeline development order in Unity is: Built-in → URP → HDRP


If a function shows "Not compatible", it means that the current rendering pipeline does not support it and cannot be used.


When downloading materials from Asset Store, be sure to check whether they are compatible with your own rendering pipeline, otherwise the material may not be displayed at all.


#### Activities 2
Attendance：Yuxin Ding, Tina Zhang, Yan Zhang


#### Activities 3
The Zoo team’s scene is relatively basic (only one platform), but the interaction is well‑designed. What is confusing is that the to‑do list provides no result or feedback whatsoever after a task is completed.


#### Activities 4
Add and improve the scene and fix minor bugs; Find sound effect for Cat Playing for this week. Today trying to find why UI not show on itch.


#### Activities 5
[Final project](https://github.com/tinamengxq/GDIM32-Final/commits/main/)
working on scene, found new material.

### W9
#### Activities 1
Use ScriptableObject (DialogueNode) to store dialogue data. Each node has NPC lines, player options and points to the next dialogue, so as to form a dialogue tree. I feel that this structure is more suitable for complex branching dialogue.


#### Activities 2
Attendance：Yuxin Ding, Tina Zhang, Yan Zhang


#### Activities 3
We found that the task instructions were not clear enough. Some players couldn't confirm that there were multiple quests. They also didn't understand the end state of the game. And our cat is a bit small, and it might not be easy for them to find immediately. Therefore, we might plan to create a start UI at the beginning to explain the background and adjust the UI content to ensure clear instructions.


#### Activities 4
- dialogue system (scriptable objects)
- more specific guidelines for players


Finished tasks: 
- All tasks listed last time
- Built scenes
Pending tasks:
- create transparent well around the terrain
- update dialogue system (scriptable objects)
- more specific guidelines for players
- create start game (inform players game background) and end game UI

- 
#### Activities 5
（https://github.com/tinamengxq/GDIM32-Final/commits/main/）the air wall has been added to solve the problem that the ground is too big.
