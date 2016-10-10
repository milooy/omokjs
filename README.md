# Javascript로 만들어 보는 오목!-! v0.2

## 목표
주어진 오목판에 검은돌과 흰돌을 번갈아서 놓는 오목게임을 만들자!

* 'javascript'의 기초는 알고 시작해야 한다.

## Precise targets
### 1차 목표
1. 주어진 오목판에 검은색 돌과 흰색 돌을 번갈아 가며 둘 수 있어야 한다.
2. 주어진 오목판에 마우스를 가져다 놓으면 transparent 한 오목돌이 뜨도록 만든다.
3. 각 차례에 맞는 transparent 한 색의 오목을 놓도록 한다.

### 2차 목표
* 가로로 같은 색의 돌이 5개가 연속되면 게임이 종료되면서 이긴 팀을 말해준다.

### 3차 목표
* 세로 및 각 대각선으로 같은 색의 돌이 5개가 연속되면 게임이 종료되면서 이긴 팀을 말해준다.

## Skeleton Code
* client/index.html 로 들어가서 script 와 html 을 적절히 조절하여 만든다.

* 이미 바둑판 배열은 <div> 로 짜여져 있다.

* 바둑돌은 하단 4개의 코드를 사용한다.
```{.html}
<button class="black stone"></button> <!-- 검은돌 -->
<button class="white stone"></button> <!-- 흰돌 -->
<button class="semi_black stone"></button> <!-- 투명한 검은돌 -->
<button class="semi_white stone"></button> <!-- 투명한 흰돌 -->
```

## 시작하는 방법
* 해당 repository를 clone한다.
* `npm install` // dependencies
* `node server.js` //서버를 시작한다.
* http://localhost:3000/ 입장
* Any questions to tost8295@gmail.com


### Copyrights
* This project is made for the education session for the Likelion Curruculum team
* Unauthorized copying of this file, via any medium is strictly prohibited
* Proprietary and confidential.
* Written by 남형걸, 진겸 <tost8295@gmail.com>, October 2016
* This source has referenced github user *@ucheol2*'s repository
* Copyright (C) 남형걸, 진겸 - All Rights Reserved
