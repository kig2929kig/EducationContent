
### @explicitHints true
### @hideIteration true

# 활동 1 - 동물 분류하기

```python
blocks.place()
mobs.spawn()
world(0, 0, 0)
```

## 1단계
마인크래프트 월드에 있는 동물들을 **왼쪽에서 오른쪽 순서**로 저장하는 **My_list**라는 이름의 리스트를 작성하세요.

이미 작성되어 있는 명령어 다음에 `||mobs:spawn mob at position||` 명령어를 **4개** 더 추가하세요.

각 동물 우리의 안내판에 표시된 정보를 참고하여 명령어를 완성하세요.

### ~ tutorialhint
리스트의 인덱스는 0부터 시작한다는 점을 기억하세요.

```template
location1 = world(-2, 40, -11)
location2 = world(-2, 40, -5)
location3 = world(-8, 40, -0)
location4 = world(-13, 40, -5)
location5 = world(-13, 40, -11)
//아래 줄을 여러분이 작성한 코드로 바꾸세요. #

//동물 리스트 작성

mobs.spawn(My_list[0], location1)
//리스트의 세 번째 동물을 location2 위치에 소환
//리스트의 다섯 번째 동물을 location3 위치에 소환
//리스트의 두 번째 동물을 location4 위치에 소환
//리스트의 네 번째 동물을 location5 위치에 소환
```
