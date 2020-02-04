# 엔진

<img src="https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/%EC%97%94%EC%A7%84.jpg">

```
엔진은 이렇게 생겼다. 되게 철덩어리처럼 생겼지만 일단은 넘어간다. 복잡한 것은 차차 다룬다.
```

---






>  # 엔진의 동작원리 
#### ~밥통의 원리~


앞 시간 엔진==밥통 이라는 것을 기억하자.
엔진은 어떻게 동작할까? (밥은 어떻게 지어질까?)

우리가 밥을 지을 때는 쌀만 넣지 않는다. 쌀과 물을 같이 넣는다.
마찬가지로 엔진에는 연료와 공기가 들어간다 **(쌀=연료 , 물=공기)**

가장 맛있게 밥을 짓는 방법은 **연료:공기=1:14.7** 이다. ~**백종원 레시피**~

![사이클 작동원리](https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/%EC%97%94%EC%A7%84%204%ED%96%89%EC%A0%95.jpg)
###### (※원본 사이트 : http://jwkang7.wo.to/pds01/106.htm)

| | |
 |--|--|
 |구조|  흡기(공기흡수) - 실린더(밥통) - 배기(공기배출) |
 |방향 |                 ->      ㅁ     -> |
 
 
```
이 그림을 쉽게 외우려면 먼저 여러분의 오른팔을 90도 각도로 세운다.
1. 그 상태로 팔을 아래로 내린다 (흡입)
2. 팔을 다시 올린다 (압축)
3. 팔을 다시 내린다 (불붙여서 폭발해서 폭발 힘으로 피스톤(주먹) 이 아래로 내려간다)
4. 팔을 다시 올린다 (폭발하고 만들어진 가스를 밖으로 빼내야 하니까)
```
---


>  # 연료에 따른 엔진 분류
#### ~쌀밥이냐 보리밥이냐~

![가솔린_디젤_엔진](https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/%EA%B0%80%EC%86%94%EB%A6%B0_%EB%94%94%EC%A0%A4_%EC%97%94%EC%A7%84.jpg)
#### 기억해야 할 것은 **구조가 다르다**


```
가솔린과 다르게 디젤에 **EGR**이 들어간다.
```

| | | |
|--|--|--|
|연료|가솔린(휘발유) | 디젤(경유) |
|점화|전기불꽃|자연발화(압축착화)|
|점화원| 有 | 無 |
|발화점|낮음|높음|
|배출가스| Co2 | NOx|
|연비| 나쁨 | 좋음 |



![GDI_MPI](https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/%EC%97%94%EC%A7%84%EB%B0%A9%EC%8B%9D-GDI-MPI.png)

```
GDI = Direct = 직접분사 = 유(油) 증기에 발화. 액체에 불 붙는거 아니다. / 불완전연소패턴이다 -> 배기가스 발생
MPI = Multiple = 나눠서 분사  / 찌꺼기가 씻겨 내려간다. 냉각성능이 좋다
```


~*공기조절, 연료조절 수정중*~

---





>  # 엔진 기통 수



![실린더종류](https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/%EC%8B%A4%EB%A6%B0%EB%8D%94%EB%B0%B0%EC%97%B4.png)
#### 실린더(밥통)구조 : L형(직렬) , V형

![4기통순서](https://github.com/lkeonwoo94/Automotive-Engineering/blob/master/%EC%9E%90%EB%8F%99%EC%B0%A8%20%EA%B5%AC%EC%A1%B0%20%EC%9D%B4%EB%A1%A0/%EC%83%A4%EC%8B%9C-%EC%97%94%EC%A7%84/img/4%EA%B8%B0%ED%86%B5%20%EC%88%9C%EC%84%9C.png)
#### 1342가 4기통 엔진 때리는 순서.
#### 5기통(무쏘)는 12453
###### (참조 : http://jwkang7.wo.to/pds04/EN-04%20%20%ED%81%AC%EB%9E%AD%ED%81%AC%EC%B6%95%EA%B3%BC%20%EC%A0%90%ED%99%94%EC%88%9C%EC%84%9C.swf )



```
배기량이나 기통수가 늘어나면 힘이 세진다

배기량 = 때리는 힘
기통수 = 때리는 횟수
```


~엔진 뜨거워짐 -> 냉각수 필요~




----





>  # 엔진 구조

플라이휠 : 처음에 돌릴때 (관성, 트랙터 제초기 생각하면 됨)
발전기
타이밍벨트 (휠, 피스톤, 발전기)
축 점화순서
냉각장치

유해가스


> # 엔진 전자제어
 
흡기 - 엔진 -배기 - 머플러
