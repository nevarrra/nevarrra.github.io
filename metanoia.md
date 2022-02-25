## Metanoia

Cross-project between Games Development (Mariya Brovkina, Gabriel Vergari) and Global Design (Diana Silva, Daniela Diniz, Joana Bento, Camila Levin, Catarina Costa) courses. The team was named Merakkie Studios and participated in **Playstation Awards Portugal: 7th Edition**, becoming the 4th finalist in the competition.

### **About the project** 

#### **Specifications**

+ **Genre:** Horror;
+ **Single/Multiplayer:** Single player;
+ **Target Audience:** Young adults;
+ **Target Platform:** Windows PC & MacOS;
+ **Engine/Tools:** Unity, C#;
+ **Development Time (approx.)** 3 months.

*There once was an ordinary family with loving parents and a child. They lived happily, and the bond between the child and his mother has always been especially strong. Until one day, the mother has disappeared. The father would tell the child a fairy tale, where the mother has become a princess and went to rule over a magical castle, living happily ever after. The child, fascinated by the story, would ask his father to retell it again and again in slightest details every night. One night, the child, missing his mother so much, has decided to go and visit her in the castle. He grabbed his plushy and a backpack and headed outside. Navigating with the details from the fairy tale, he followed his mother’s favourite flowers and finally arrived at the  castle...*

Metanoia is a vertical slice of a short, horror game that evolves around the story of a child who needs to solve the riddles of the magical castle in order to find his mother. 
On his journey through the castle, he meets several Imaginary Friends with whom he can interact and try to assist, earning a flower as a gratitude. His task is to collect enough flowers to present to his mother when he finally meets her. The Imaginary Friends wear the masks of the animals, some of them are predators, some - prey. It defines their intentions and the way the Child needs to treat their requests. If angered, an Imaginary Friend will transform into a shadow, lurking in the castle halls and terrorizing the Child. 
The game features distinct AI per each shadow, making them hunt the player in different ways that would relate them to their animal mask. In total, there are seven shadows with their own unique behavioural patterns. 
One of the player's tasks is to keep the heartbeat rate of the Child at normal values as it acts as his health points. There are safe areas lit by the sunlight as well as mini-games made for lowering the risk of the hero dying from the panic attack.

### **Media**

#### *Playstation Awards*


#### *Trailer*

[![Trailer Link](https://img.youtube.com/vi/AFegcuIMJ3k/0.jpg)](https://youtu.be/AFegcuIMJ3k)

#### *Spec Sheet*

[TNR Spec Sheet](/pdf/Spec.pdf)


GDD is also available upon request.

### **My Input**

My input as a developer was focused around: 

+ Artificial Intelligence 

*I have implemented a Pluggable Finite State Machine for different kinds of NPCs and enemies; designed, programmed and maintained throughout every phase of the development the behaviours for most of the Shadows, Imaginary Friends and static NPCs. Part of my work was also connected to the implementation of the pathfinding algorithms and randomness in the characters' behaviour. I was responsible for the performance and scalability of the AI.*

+ Dialogue System

*I have developed a unique dialogue system that is responsible for audio and subtitles output for all the characters based on how far/close the player is and whether the quest-related interaction has begun.*

+ Custom Shaders (CG)

*As a part of the course requirements, I have programmed a custom directional dissolve shader in HLSL, applied whenever an Imaginary Friend's quest has ended and the character disappears by whether burning out (unsuccessful outcome) or teleporting softly (successful outcome).*

+ Mini-game

*Also called a "breathing mechanic", I have developed this mini-game that would trigger in a safe zone whenever the Child's heartbeat is dangerously high. The mini-game imitates the Child's breathing and requires the player to perform rhythm-like actions, pressing the button at the correct time when the running squares cross the line on the left side. By successfully pressing it for the required amount of times, the heartbeat rate will return to normal.*

