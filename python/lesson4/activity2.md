
### @explicitHints true

# 활동 2 - 식단에 맞는 사료 만들기

```python
blocks.place()
```

## 1단계
**첫 번째** 강아지에게 미리 정의된 리스트에 있는 모든 음식을 주세요.

처음 **4개**의 `||blocks:place block at position||` 명령어를 수정하여 리스트에 있는 각 항목이 순서대로 배치되도록 하세요.

그런 다음 상자에 있는 음식을 꺼내 첫 번째 강아지에게 주세요.

### ~ tutorialhint
빠른 실행 슬롯(핫바)에 있는 아이템을 떨어뜨리려면 키보드의 [**Q**] 키를 누르세요.

## 2단계
**두 번째** 강아지에게 기존 리스트에 있는 모든 음식과 추가 비타민을 주세요.

**append** 메서드를 사용하여 변수 **Vitamins**를 리스트의 마지막에 추가하세요.

마지막 `||blocks: place block at position||` 명령어를 수정하여 기계에 비타민이 배치되도록 하세요.

그런 다음 완성된 음식을 두 번째 강아지에게 주세요.

## 3단계
**세 번째** 강아지에게 기존 리스트에 있는 음식 중 **소고기(beef)**를 제외한 모든 음식을 주세요.

**pop** 메서드를 사용하여 리스트에서 변수 **Beef**에 해당하는 항목을 제거하세요.

그런 다음 완성된 음식을 세 번째 강아지에게 주세요.

### ~ tutorialhint
**pop** 메서드를 사용할 때는 항목의 이름이 **아닌** 리스트의 인덱스(위치 번호)를 사용해야 합니다.

```template
Bone = world(-21, 45, -31)
Beef = world(-21, 45, -29)
Chicken = world(-21, 45, -27)
Biscuit = world(-21, 45, -25)
Vitamins = world(-21, 45, -23)
// 아래 줄을 여러분이 작성한 코드로 바꾸세요. #
Dog_Food=[Bone, Beef, Chicken, Biscuit]
//append 메서드를 사용하여 리스트에 Vitamins 변수 추가 | 2단계
//pop 메서드를 사용하여 Beef 항목 제거 | 3단계

blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//아래 리스트의 인덱스 값 변경 | 1단계
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//아래 리스트의 인덱스 값 변경 | 1단계
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//아래 리스트의 인덱스 값 변경 | 1단계
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
//아래 리스트의 인덱스 값 변경 | 2단계
blocks.place(REDSTONE_BLOCK, Dog_Food[0])
```
