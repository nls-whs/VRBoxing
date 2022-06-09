# VRBoxing

_Unreal Engine version_:  4.25.4 <br/>
_Device tested_:  Oculus Quest 1 and 2 <br/>
_Tested on platforms_:  UE4 Editor, Windows 64 bit, Android ASTC

# Introduction

This game or proof of concept has been developed as part of [Next level Sports](https://hci.w-hs.de/research/projects/nextlevelsports/) project. The main goal is to motivate users to do more movement through full-body sports such as Boxing. It has been developed for portable VR headset such as Oculus Quest that allows the user to move around freely.

# Gameplay

## Warm-up

This is a target based warm up exercise where the player can warm up boxing hits by hitting the targets in a certain sequence. The targets will be hit by grabbing the corresponding hand. If the targets are hit correctly, they are colored as green but if the wrong sequence is followed, the targets turn red. For this training, the player is given some points in the end and the total activity is 1.5 mins long.

![warmup](https://user-images.githubusercontent.com/104509917/167878637-3f596d33-afe9-4178-9ec5-1a764ba60f6b.JPG)

## Training

After the warm-up session is finished, the player can select training mode from the UI. In this mode, the player can interact with different virtual objects such as dumbbells, skipping rope and a punching bag. The dumbbells have no force feeback but it is only a virtual interaction. The skipping rope can be grabbed in right and left hand by pressing the grip button and the player can simply skip as he would do in real life. The punching bag has a virtual mass and moves slowly after punch which gives an illusion of virtual weight.

![training](https://user-images.githubusercontent.com/104509917/167878585-040c6678-546b-4c8d-b679-c97cf377beda.JPG)

## Fight 

In this mode, the player can play with computer-generated opponent. AI has 2 modes (Active and Passive)

- Active AI: This AI constantly runs around the player once it finds the player. 
- Passive AI: This AI provokes the player to come near to him and in this way, the player can walk in real world to move near to the AI. After that the player can fight with AI using different kinds of punches: jab, upper cut, lower cut and the AI will react to those punches by playing a corresponding hit animation. If the AI hits the player, the screen turns red and if the player hits AI, the health bar is reduced and once it is empty, AI is knocked out.

![Fight](https://user-images.githubusercontent.com/104509917/167878466-cc9a0e9a-6303-4804-a202-1c99051e4518.JPG)

## Cool-down

This is based on arm stretching exercise. After selecting cooldown from the UI menu, the player is teleported to a wall where he is shown some instructions regarding calibration. The player has to calibrate twice for this exercise. Firstly, by normally raising his arms and pressing a grip button. Secondly, by standing on toes and then stretching arms to calibrate again. Next, the virtual stones appear on stretched positions on the wall and the player has to grab these virtual stones by pressing a grip button. After grabbing the stones, the wall is animated down giving an illusion of wall climbing. This exercise would help the player to relax as part of cool-down.

![cool down](https://user-images.githubusercontent.com/104509917/167878678-913888c9-6131-4d2c-92f8-838354b1a1bc.JPG)

# Controls

- Teleport: Both hands (Button A or X)
- Show UI menu: Right Hand only (Button B)
- Grabbing: Both hands, Grip button (can be used to punch and grab objects)
- UI selection: It can be switched between hands by pressing a trigger button on the respective controller

# Future work

- Better UI design and integration 
- Localization in different languages (English and Deutsch)
- Creation of user profiles
- Show performance statistics

These are further developed in Virtual Boxing Simulator game

# Build configuration

This has been tested with Development and Shipping configuration. The Windows 64 build and Android build are available to download via the following link: <br/>

https://w-hs.sciebo.de/s/TN3RzFU0OryooLH 


# Credits

### Assets: <br/>
Sport Gym pack: https://www.unrealengine.com/marketplace/en-US/product/sport-gym-pack <br/>
Movement Animation set Pro: https://www.unrealengine.com/marketplace/en-US/product/movement-animset-pro <br/>
Fighting Animation set Pro: https://www.unrealengine.com/marketplace/en-US/product/fighting-animset-pro <br/>
Polygon assets pack from Syntystore (Fantasy Kingdom, Battle Royale, Dungeons, Farm, Gang Warfare, Office, Pirates, Samurai, War) : https://syntystore.com/collections/frontpage <br/>
3D Model creation (Dumbbell, Barbell, Skipping rope, Punching bag): Tobias Winter <br/>
For all asset related queries, contact Thomas Kollakowsky (thomas.kollakowsky@w-hs.de) <br/>

To compile the project successfully, download all assets mentioned above. All paid assets have been removed from this project for the purpose of copyright.

### Developers: <br/>
[Asma Rafi](https://github.com/asmarf6), [Christopher Bussick](https://github.com/cbussick), Julien Förderer <br/>
