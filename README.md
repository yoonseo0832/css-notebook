# 내가 잘모르는 css 보기 위해 정리노트
### 가로 세로 중앙정렬
```
  display: flex; 
  align-items: center; 
  justify-content: center;
```
- display: flex: 내부 아이콘을 flexbox로 정렬합니다.
- align-items: center: 수직 중앙 정렬합니다.
- justify-content: center: 수평 중앙 정렬합니다.

### 이미지 사이즈 조절하는 방법
```
  background-image: url(/src/assets/images/acc-list-page/sampleImg.png);
  background-size: cover;
```
- contain : 이미지의 가로세로 비율을 유지하면서, 이미지가 잘리지 않을 때까지만 채웁니다.
- cover : 이미지의 가로세로 비율을 유지하면서, 이미지가 잘리더라도 주어진 크기를 꽉 채웁니다.
- 사이즈 임의 지정 : 비율에 무관하게 입력한 값에 맞춰 사이즈를 조절
