# COMP2150  - Level Design Document
### Name: Htet Yamin Ei
### Student number: 47743220

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:



## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery

The player learns about various game mechanics, including enemy behaviours, hazards, and interactive elements throughout the level. At the beginning of the game, the player discovers the movement speed and jumping height of the game character, Ellen. New mechanics and elements are progressively introduced to players so that they can learn and adapt to each new challenge at their own pace. Players are encouraged to explore and learn about the functionality of objects through encounters such as the gun and the staff, fostering a sense of agency and curiosity.

![Discovery of Checkpoint, PassThroughPlatform & Acid](DocImages/image1.png)

In the above picture, the player encounters a section where they discover the checkpoint, a platform which they can pass through, and the fact that acid pools trigger a respawn at the last checkpoint. 

![Discovery of Gun & Spitter](DocImages/image2.png)

As depicted in the picture, the player encounters a skeleton equipped with a gun and an enemy spitter. The player discovers that they can pick up the gun and learn how to shoot it to kill the spitter, which attacks from a distance. The first spitter is placed in a location where the player can observe its behavior without immediate danger. The player learns to time their movements to dodge the spitter's projectiles through trial and error.

![Discovery of HealthPickup, PressurePad & Moving Platform](DocImages/image3.png)

In this part, the player learns that health can be restored with a health pickup box, and the pressure pad can be used to move the platform by standing on top of it. The health pickup boxes are visually distinct, drawing the player's attention and signaling that they can be interacted with.

![Discovery of PushableBox, Spike, Switch & TriggerDoor](DocImages/image4.png)

In this section, the player is introduced to a big box that can be pushed, spikes that cause damage upon contact, and a switch that can be triggered with the bullet to open a door. The sound of a switch being triggered signals to the player that a door has opened. Such visual and audio cues provide feedback to players, reinforcing learning and guiding them through the discovery process.

![Discovery of FloatingBox](DocImages/image5.png)

As seen in the image, the player is exposed to the mechanics that pushable boxes can float on the acid.

![Discovery of Staff & Destructible Wall](DocImages/image6.png)

As shown in the picture, the player comes across a staff that can be taken from the skeleton and encounters a destructible wall, which forces the player to use the staff to destroy the obstacle in their path.

![Discovery of Chompers](DocImages/image7.png)

In this part, the player is introduced to chompers, which move towards the player to deal damage upon contact. The player learns that they can be destroyed by using the staff as a melee weapon.

### 1.2. Drama

![Intensity Curve](DocImages/image8.jpg)

The intensity curve is designed to gradually increase, providing players with moments of tension and relief throughout their journey. As players progress, more challenging hazards and enemies are introduced over time.

![Drama](DocImages/image9.png)

In the picture shown above, the player must navigate through a series of platforms suspended over spikes at the bottom while avoiding spitters and moving spikes. The cramped quarters and constant threat of falling create a sense of tension for players. Reaching the checkpoint afterward provides moments of relief and respite. The combination of moving platform challenges and spitters keeps players engaged and invested in the gameplay, while the occasional presence of stationary platforms ensures that the difficulty remains manageable, and players feel a sense of progression.

### 1.3. Challenge

The main challenges revolve around navigating hazards, defeating enemies, solving puzzles, and mastering platforming mechanics. The difficulty curve is carefully balanced to avoid frustration and keep players in the flow channel, with each new challenge building upon the skills learned in previous levels. Players must learn to anticipate movements and attacks of spitters and chompers, as well as develop strategies for defeating them efficiently while minimizing damage taken. Timing, precision, and spatial awareness for spikes and acid pools are crucial for avoiding damage and progressing through the level safely. Obstacles such as locked doors and large acid pools encourage problem-solving skills. Visual indicators of damage taken or the consequences of failing to navigate a hazard help the player understand the impact of their actions and adjust their strategies accordingly. This iterative process of learning and adaptation is essential for maintaining flow and preventing frustration.

![Challenge](DocImages/image10.png)

In the above picture, the player must trigger the switch to unlock the door to get the key. However, the switch and the door are guarded by two spitters. Combining enemy encounters with puzzle-solving elements provides a meaningful test of the player's abilities without feeling overly punishing or unfair.

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

### Tool Used: ChatGPT 3.5
**Nature of Use** Checking grammar mistakes and correcting punctuations.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to check grammar mistakes and to correct punctuations. I read through the suggestions and incorporated some of the phrasing into my writing.
