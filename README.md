<!--
    1. About this game
    2. How to download(zip or git clone) 방식 설명
    3. 대략적인 게임 방식 설명( we made 3d 잠입게임 어쩌고)
    4. 서사적 배경
    5. 플레이어 소개(설정)
    6. 적 소개 
    7. 조작키 설명(움직임, 투척 요소, 불안감 요소, 필터요소, 가이거 계수기 transition, 로봇 의심 요소, 로봇 발견 요소, gif로 올리기)
    8. 인 게임 사진 예쁜거 컷 몇 개 넣고
    9. 오른쪽 상단에 유튜브 영상 링크 올리기
-->

## 2023 KHU Game Engine Basics Team 4

***
<div align="center"> 
    
# The Last Job

</div>
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="2000" height="300">

***
<div align="center"> 
    
## Index

</div>



  #### 1. [About This Game](#1-about-this-game)
  #### 2. [How to download](#2-how-to-download)
  #### 3. [How to play](#3-how-to-play)
  #### 4. [Preview](#4-Preview)
  #### 5. [Cut Scene](#5-Cut-Scene)
  #### 6. [Credit](#6-Credit)

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

* [DOWNLOAD][externallink]

 [externallink]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
***

### Download Middle Quality Version

* [DOWNLOAD][externallink]

 [externallink]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
***

### Download Low Quality Version

* [DOWNLOAD][externallink]

 [externallink]: https://www.youtube.com/watch?v=dQw4w9WgXcQ

***
<div align="center"> 
    
## 3. How To play

</div>

### Player Control
|Control|Video|Inscription|
| :---:  | :---:  | :---:  |
| Movement | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can control your player by 'WASD', SpaceBar, Shift, Ctrl, And Mouse movement.
| Giger Check | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can check the level of the radiation of the zone which you currently stand.
| Throwing Objects | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can thorw your Emp that you have to neutralize ememy or grab rock and throw to make some interruption.

### Player Sub System
|Parameters|Video|Inscription|
| :---:  | :---:  | :---:  |
| Radioactive Level | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can check your radiation level by pressing 'Tab'. It pops out the Giger Counter on your hand
| Anxiety | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you check Your giger counter , it makes your anxiety higher according to the level of the radiation level which disturb your sight and movement  
| Stamina | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you press shift to run, the stamina will decrease that it shows to your UI Screen.
| Filter | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | It will Decrease the level dynamically of which you stay on the different radiation level. (Game over if you loss your filter entirly)

### Enemy System
|State|Video|Inscription|
| :---:  | :---:  | :---:  |
| Suspicious | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the enemy has visualiation about player or hearing noise, it makes it suspecious about the situation and inspect to the area which the noise came from.
| Detected   (Chasing) | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the suspicious state maintained about certain time, it will change to Chasing mode and follows the player to eleminate.
|    Get Caught    | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you get caught, it will knock down and gameover.

### Target Object(Puzzle System)
|Puzzle|Video|Inscription|
| :---:  | :---:  | :---:  |
| Electric Room | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You have to restart the electricity to activate the system by connection about sender&receiver.
| Control Room | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can flush the water which sinked the storage.
| Mechanical Room | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can stablize the water pump pressure by combination of the lever  
| Storage | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | Master Battery source is placed in the storage to shut down the nucelear facility. 

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

<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1000">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1000">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1000">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1000">


***
<div align="center"> 
    
## 6. Credit

</div>

<div align="center"> 
These are people who made our game project.
</div>

 * __Kunwoo Kim(김건우)__  - SFX, Map Edit, Detail Test ,Orchestrator
 * __Jihoo kim(김지후)__  - Game System, Map Edit, Puzzle editor
 * __BIN KAMISAN MUHAMAD ADLAN(محمد عدلن بن كاميسن)__ -  AI System, Map Edit, Puzzle editor
 * __Dagyeong Jeon(전다경)__ -  Game System, Sub System, UI, Core Developer
 * __Daejin Ha(하대진)__  - VFX, Map Edit, Graphics, Visualization editor


