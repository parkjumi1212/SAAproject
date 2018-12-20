**SAA REPORT**
오전반 2조 위풍당당조
ICT융합학부 2017012897 박주미


2018-2학기 스마트센서와 액츄에이터의 결과레포트입니다.

***

집에 혼자 남은 반려동물을 위한 자동 급식기
"나를 부탁해"

![mong](https://user-images.githubusercontent.com/33901515/50281887-4755ff80-0494-11e9-91aa-5e92524aaa0a.png)

* * *


1. 왜 구상하게 되었나 ? 

    집을 장시간 비울 경우 혼자 있을 반려동물이 제 시간에 밥과 물을 알아서 먹을 수 없다는 점이 가장 큰 이유였습니다. 밥을 한번에 많이 주고 가거나 물을 한번에 많이
  주고 외출할 경우 반려동물의 건강을 해칠 수 있기 때문에 적절한 시각에 밥을 먹고 , 반려동물이 원할 때 마다 물을 마실 수 있다면 편리하겠다는 생각이 들어 구상하게
  되었습니다. 또한 부가적인 기능으로 반려동물이 외로워 할 때나 천둥 등 놀랄 수 있는 상황에서 반려동물을 안심시키는 기능을 추가하고자 했습니다. 

* * *

2. 프로토타입

(1)초기 프로토타입 

![p1](https://user-images.githubusercontent.com/33901515/50281902-589f0c00-0494-11e9-888a-07c9b8f7aac4.png)
![p2](https://user-images.githubusercontent.com/33901515/50281911-60f74700-0494-11e9-900b-f05666427bf2.png)


(2)최종 프로토타입

![p3](https://user-images.githubusercontent.com/33901515/50281917-681e5500-0494-11e9-8581-5b6033e22095.png)
![p4](https://user-images.githubusercontent.com/33901515/50281919-6bb1dc00-0494-11e9-8926-f4311514455f.png)


* * *

3. 구현
  
  (1) 필요한 기능들
  
      - 밥먹을 시간이 되면 밥이 나오게 하는 것

      - 사료를 정해진 시간에 일정량 나오게 하는 것이 관건

      - 강아지가 버튼을 누르면 물이 일정량 나오게 하는 것

      - 주인 목소리를 녹음해서 특정 상황에 틀어주는 것

  (2)구현한 기능들

      - 밥   
        - 일정 시간 간격으로 밥이 나오게 함
        - 주인이 외출 시 버튼을 누르고 나가면 N시간에 한번 밥이 나오도록
        - 밥이 나올 때 마다 물도 같이 나옴
      - 물 
        - 터치 센서가 눌릴 때 마다 물이 나옴


  (3) 코드 
  
![code1](https://user-images.githubusercontent.com/33901515/50281875-40c78800-0494-11e9-8f2a-85570f20e0d6.png)
![code2](https://user-images.githubusercontent.com/33901515/50281876-41601e80-0494-11e9-9131-47fbae5df4ef.png)


==실행 동영상 링크 첨부합니다.==

[https://youtu.be/H97FaAIHPCA](http://https://youtu.be/H97FaAIHPCA)


***


4. 어떻게 동작 ?
![1](https://user-images.githubusercontent.com/33901515/50281869-3f965b00-0494-11e9-8100-e0cb99c38858.png)
![2](https://user-images.githubusercontent.com/33901515/50281870-402ef180-0494-11e9-88e9-ad9fd30d4c03.png)
![3](https://user-images.githubusercontent.com/33901515/50281871-402ef180-0494-11e9-95a6-815b22b9e900.png)


***

5. 어려웠던 점 & 아쉬웠던 점

___
  (1) 어려웠던 점
  
![4](https://user-images.githubusercontent.com/33901515/50281872-402ef180-0494-11e9-81cb-36b13b2fd631.png)
![5](https://user-images.githubusercontent.com/33901515/50281873-40c78800-0494-11e9-8c69-b81380c02c37.png)

___
  (2) 아쉬웠던 점
  
![6](https://user-images.githubusercontent.com/33901515/50281874-40c78800-0494-11e9-88cd-34233790be29.png)


