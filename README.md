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
# The Last Job
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="2000" height="300">

***

### 목차

  1. [About This Game](#1-about-this-game)
  2. [How to download](#2-how-to-download)
  3. [How to play](#3-how-to-play)
  4. [Preview](#4-Preview)
  5. [Credit](#5-Credit)

***
<div align="center"> 

## 1. About this game

</div>

### Breif Game Story And System


In 2030, armed conflict between the two countries, 'Pamas' and 'Ergodo', eventually led to war.<br/> 
Pamas dispatched combat robots to the nuclear power plant, Ergodo's main energy development facility, triggering nuclear overuse to turn nuclear power plants into nuclear weapons. <br/> To prevent this, Ergodo will send key nuclear power plant general engineers. The player shall restore damaged power at the plant facility and stabilize the control system. <br/> 

    
### Purpose of the Game
* Avoid or neutralize Ergo's combat robots, which invaded the nuclear power plant's internal facilities, achieve their goals and escape safely.
* As nuclear power facilities have been damaged to some extent by the war, certain areas have dangerous spaces to access.
* Players must frequently check their own Geiger counter to be extra careful not to be exposed to danger and to control the limited number of filters and the player's anxiety index.

<div align="center"> 

## 2. How To download
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
| Movement | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can Control your player by WASD, SpaceBar, Shift, Ctrl, LMB, RMB 
| Giger Check | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can Check the level of the radiation of the zone which you currently stand
| Throwing Objects | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You can Thorw your Emp that you have to neutralize Ememy Or rock to make some interruption.

### Player Sub System
|Parameters|Video|Inscription|
| :---:  | :---:  | :---:  |
| Anxiety | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you Check Your Giger Counter Currently, it makes your anxiety higher which disturb your sight and movement  
| Radioactive Level | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | You Can Check your radiation level by pressing 'Tab'. It pops out the Giger Counter on your hand
| Stamina | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you press shift to run, the stamina will decrease that it shows to your UI Screen.
| Filter | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | It will Decrease the level dynamically of which you stay on the different radiation level. (Game over if you loss your filter entirly)

### Enemy System
|State|Video|Inscription|
| :---:  | :---:  | :---:  |
| Suspicious | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the enemy has visualiation about player or hearing noise, it makes it suspecious about the situation and inspect to the area which the noise came from.
| Detected(Chasing) | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If the suspicious state maintained about certain time, it will change to Chasing mode and follows the player to eleminate.
| Get Caught | <img src="https://i0.wp.com/www.printmag.com/wp-content/uploads/2021/02/4cbe8d_f1ed2800a49649848102c68fc5a66e53mv2.gif?fit=476%2C280&ssl=1" alt="TEST" width="300px" height="140px"></img> | If you get caught, it will knock down and gameover.

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

<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1200">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1200">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1200">
<img src="https://dropinblog.net/34244460/files/featured/42451850_disaster_cover_002_out.jpg" alt="대문짝만한로고" width="1000" height="1200">


***
<div align="center"> 
    
## 5. Credit

</div>

These are people who made our game project 

 * __Kunwoo Kim(김건우)__ SFX, Map Edit, Detail Test ,Orchestrator
 * __Jihoo kim(김지후)__ Game System, Map Edit, Puzzle editor
 * __BIN KAMISAN MUHAMAD ADLAN(아드란)__ AI System, Map Edit, Puzzle editor
 * __Dagyeong Jeon(전다경)__ Game System, Sub System, UI, Core Developer
 * __Daejin Ha(하대진)__, VFX, Map Edit, Graphics, Visualization editor


