# Javascript로 만들어 보는 오목!-! v0.2

## 목표
주어진 오목판에 검은돌과 흰돌을 번갈아서 놓는 오목게임을 만들자!

* 'javascript'의 기초는 알고 시작해야 한다.

## Precise targets
1. 주어진 오목판에 검은색 돌과 흰색 돌을 번갈아 가며 둘 수 있다.
2. 주어진 오목판에 마우스를 가져다 놓으면 transparent 한 오목돌이 뜨도록 만든다.
3.

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

