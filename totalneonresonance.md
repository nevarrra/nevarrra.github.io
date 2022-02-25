## Total Neon Resonance

Developed in cooperation with Pedro Nande.

### **About the project** 

#### **Specifications**

+ **Genre:** Racing & Rhythm;
+ **Single/Multiplayer:** Multiplayer, PvP, 2 to 6 players per session;
+ **Target Audience:** Teenagers and young adults;
+ **Target Platform:** Windows PC;
+ **Engine/Tools:** Unreal Engine 4.27, C++;
+ **Development Time (approx.)** 2 months.

*Thousands of years into the future, humanity is no longer on planet Earth. But the artificial intelligence they have created still persists. Able to command any machine on the planet, the weather and sustain itself, living on an empty planet, it develops feelings for its creators. Nostalgic of the past, when the planet was still lively and full of sound, the AI creates an environment where the two most powerful creations combine: machines and music.*

Total Neon Resonance (TNR) is a multiplayer rhythm racing prototype where players will race off against each other while trying to drive in the beat of the song and keeping others from doing the same.
TNR features custom car mechanics, procedurally generated racing tracks, music synchronization and generation of collectable beats in runtime. It is possible to play custom songs, however, this feature is currently off due to possible copyright issues.
For the multiplayer part, TNR runs on a UE4 dedicated server with an external Matchmaking server that searches for players based on their chosen music preferences. 

### **Media**

#### *Trailer*

[![Trailer Link](https://img.youtube.com/vi/Y68hBi5FOo/0.jpg)](https://youtu.be/-Y68hBi5FOo)

#### *Spec Sheet*

[TNR Spec Sheet](/pdf/Spec.pdf)


GDD is also available upon request.

### **My Input**

My work in this project was tightly connected to: 
+ Custom car mechanics
*I have developed an arcade-like car mechanics for the player's car, that involved physics manipulation for features such as suspension, torque and car's gravity.*
+ Music synchronization & generation of the collectable beats
*With the use of UE4's Synesthesia plugin to extract music's offset and corresponding timestamps, I have implemented a logic for the generation of the beats for every player in a runtime, with relation to their current position, direction, time left until the rhythmic event, and velocity to ensure that the players collect the beat at the right moment. I have also implemented a system to read several stems of the audio file and generate the beat collectibles based on which instrument in the song is most prominent.*
+ Server-side programming & Matchmaking
*I have been working with the replication of the sounds as well as the dedicated server setup and messages exchange. I have also fully developed the external Matchmaking server in .NET 5.*

