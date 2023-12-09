## 2023 KHU Game Engine Basics Team 4
<div align="center"> 
    
# The Last Job
![1233](https://github.com/haddol7/The-Last-Job/assets/80435250/6245d33d-d094-41f4-964d-d7fe1cc4fd89)

</div>

<div align="center"> 

***    
## Index

</div>

  #### 1. [About This Game](#1-about-this-game-1)
  #### 2. [How to download](#2-how-to-download-1)
  #### 3. [How to play](#3-how-to-play-1)
  #### 4. [Preview](#4-preview-1)
  #### 5. [ScreenShot](#5-screenshot-1)
  #### 6. [Credit](#6-credit-1)

***
<div align="center">

## 1. About this game

</div>

### Breif Game Story And System

<div align="center"> 

In World War III, a terrorist attack by an enemy nation detonated the central radioactive research complex.

Since the aftermath of the detonation might cause following consequencial explosions, the nation dispatched military robots applied with radiation-hardened techniques to remove unstable factors.

However, the radioactive fallout was much stronger than expectations. The communication with the robots has been lost, now they are out of control. 

You are one of the agents who has volunteered to solve this situation, as a researcher who once participated in the design of the complex.

Solve the given missions to retrieve safety, and escape with secure.

</div>
    
### Notes/Tips
* You don't belong to the army, the robots would not identify you as an ally. Avoid or neutralize them.
* You have access to most of core facilities of the complex. Try utilizing inner facilities if you find some.
* Radioactive fallout spreads throughout the sector. Check the geiger counter as the magnitude varies from area to area.

<div align="center"> 

## 2. How To download
</div>
<div align="center"> 
You can download it by clicking the link below. Download a version that meets your computer's specifications.
</div>

### Download High Quality Version

* [DOWNLOAD][externallink] (4.9GB)

 [externallink]: https://drive.google.com/file/d/1AQ9QKTvtI89i2wXvd2Ra6T2L7fDs3cAl/view?usp=sharing
***

### Download Middle Quality Version

* [DOWNLOAD][externallink] 

 [externallink]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
***

### Download Low Quality Version

* [DOWNLOAD][externallink] (4.7GB)

 [externallink]: https://drive.google.com/file/d/1Cppc_uRXHH__Mpj4B0pJKxufPw-Iw43d/view?usp=drive_link
***
<div align="center"> 
    
## 3. How To play

</div>

### Player Control
|Control|Video|Inscription|
| :---:  | :---:  | :---:  |
| Movement | ![Movement](https://github.com/haddol7/The-Last-Job/assets/64568235/0acacdae-8494-41bb-a905-3e9052f526d1) | You can control your player by 'WASD', SpaceBar, Shift, Ctrl, And Mouse movement.
| Giger Check | ![Giger Check](https://github.com/haddol7/The-Last-Job/assets/64568235/10a71239-5fad-48f7-9093-c31912c94fd0) | You can check the level of the radiation of the zone which you currently stand.
| Throwing Objects | ![Throwing Objects](https://github.com/haddol7/The-Last-Job/assets/64568235/c7a7c0d9-0db3-4260-8ac0-2afc61df460d) | You can thorw your Emp that you have to neutralize ememy or grab rock and throw to make some interruption.

### Player Sub System
|Parameters|Video|Inscription|
| :---:  | :---:  | :---:  |
| Radioactive Level | ![Radioactive Level](https://github.com/haddol7/The-Last-Job/assets/64568235/98b17a80-f956-4b78-9efa-a6485e3b5e77) | You can check your radiation level by pressing 'Tab'. It pops out the Giger Counter on your hand
| Anxiety | ![Anxiety](https://github.com/haddol7/The-Last-Job/assets/64568235/6533d701-d1d4-4af8-a96c-0de6c6b298ca) | If you check Your giger counter , it makes your anxiety higher according to the level of the radiation level which disturb your sight and movement  
| Stamina | ![stamina](https://github.com/haddol7/The-Last-Job/assets/64568235/ae777675-aeba-44d9-926f-bc313cb2d959) | If you press shift to run, the stamina will decrease that it shows to your UI Screen.
| Filter | ![Filter](https://github.com/haddol7/The-Last-Job/assets/64568235/876a1217-c4b9-4a00-8526-14ef10b34cb8) | It will Decrease the level dynamically of which you stay on the different radiation level. (Game over if you loss your filter entirly)

### Threating System
|State|Video|Inscription|
| :---:  | :---:  | :---:  |
| Suspicious | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the enemy has visualiation about player or hearing noise, it makes it suspecious about the situation and inspect to the area which the noise came from.
| Detected   (Chasing) | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the suspicious state maintained about certain time, it will change to Chasing mode and follows the player to eleminate.
|    Get Caught    | ![Get Caught](https://github.com/haddol7/The-Last-Job/assets/64568235/c7493192-e6a4-4dae-b464-7cf9e24a9362) | If you get caught, it will knock down and gameover.
|    Filter Death    |  ![Filter Death](https://github.com/haddol7/The-Last-Job/assets/64568235/7e40ff76-c5ff-442a-a105-1a561f682458) | If you exhausted your filter, you would be fall in death by few second.


### Target Object(Puzzle System)
|Puzzle|Video|Inscription|
| :---:  | :---:  | :---:  |
| Electric Room | ![Electric Room](https://github.com/haddol7/The-Last-Job/assets/64568235/dd27851b-8fc4-49ea-937c-4a027b43908b)| You have to restart the electricity to activate the system by connection about sender&receiver.
| Control Room | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can flush the water which sinked the storage.
| Mechanical Room | ![Mechanical Room](https://github.com/haddol7/The-Last-Job/assets/64568235/eab562cd-2b85-4cf6-9bd1-5f15d4ffa82a) | You can stablize the water pump pressure by combination of the lever  
| Storage | ![Storage](https://github.com/haddol7/The-Last-Job/assets/64568235/630da2a1-d230-45b6-b6a9-1e9f6e6b0b05) | Master Battery source is placed in the storage to shut down the nucelear facility. 
| Restarea | ![RestArea](https://github.com/haddol7/The-Last-Job/assets/64568235/a0ec9d11-b742-40c1-89c1-b8bf392ddad6) | You can get some items which you need for survive.

***
<div align="center"> 
    
## 4. Preview
    
</div>

<div align="center"> 
You can watch the preview by clicking the link below.

### [watch Preview][externallink]

</div>

 [externallink]: https://www.youtube.com/watch?v=dQw4w9WgXcQ


***
<div align="center"> 

## 5. ScreenShot

</div>

![HighresScreenshot00000](https://github.com/haddol7/The-Last-Job/assets/80435250/54ee48f5-2e81-41fe-a108-cd6324c01a6b)
![1](https://github.com/haddol7/The-Last-Job/assets/80435250/5165e4b7-49f1-4221-9eb3-55b4179c50a3)
![4](https://github.com/haddol7/The-Last-Job/assets/80435250/50122b0a-2b69-4941-b5b8-a75d9490480e)
![HighresScreenshot00006](https://github.com/haddol7/The-Last-Job/assets/80435250/f752e564-bed1-4756-b2fb-b7f0e42c97ff)
![HighresScreenshot00007](https://github.com/haddol7/The-Last-Job/assets/80435250/1c4e8680-ed28-4f5c-bfa4-5b9f30fea33a)
![5](https://github.com/haddol7/The-Last-Job/assets/80435250/6812568c-a23b-4097-8c58-6353faaa6e52)
![6](https://github.com/haddol7/The-Last-Job/assets/80435250/adca4072-76d8-4596-b380-d3373d135017)
![3](https://github.com/haddol7/The-Last-Job/assets/80435250/e8db924d-4cc8-41bb-ab0c-0ac056cc7876)



***
<div align="center"> 
    
## 6. Credit

</div>

<div align="center"> 
These are people who made our game project.
</div>

 * __Kunwoo Kim(김건우)__  - SFX, Map Edit, Detail Test ,Orchestrator
 * __Jihoo kim(김지후)__  - Game System, Map Edit, Puzzle editor
 * __Muhamad Adlan Bin Kamisan(محمد عدلن بن كاميسن)__ -  AI System, Map Edit, Puzzle editor
 * __Dagyeong Jeon(전다경)__ -  Game System, Sub System, UI, Core Developer
 * __Daejin Ha(하대진)__  - VFX, Map Edit, Graphics, Visualization editor


