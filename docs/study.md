# 정리
## 01. 설정하기
1. Container 위젯
   1. 컨테이너 박스처럼 컨테이너 안에 위젯들을 그냥 넣음
   2. 형태는 우리가 지정할 수 있지만 기본적으로 자식을 따라감.
2. SafeArea 위젯을 Scaffold 바디 안의 위젯들에게 적용하면 상태바에 안넘어가게 할 수 있다.
   1. Go To 로 선언부로 이동해서 필요한 인자들을 볼 수 있다. 
   2. top, bottom 등으로 부분마다 꽉 채울지 안 채울지 설정 가능하다는 걸 알 수 있었음


## 02. Column and Row MainAxisAlignment
1. Column
   1. MainAxisAlignment.start : 위젯 들이 맨 위로 정렬됨
   2. MainAxisAlignment.end : 위젯 들이 맨 아래로 정렬됨
   3. MainAxisAlignment.center : 위젯 들이 가운데로 정렬됨
   4. MainAxisAlignment.spaceBetween : 위젯과 위젯 사이가 동일하게 정렬됨 
   5. MainAxisAlignment.spaceEvenly : 위젯을 같은 간격으로 배치하지만, 시작과 끝이 빈 간격으로 둔다.
   6. MainAxisAlignment.spaceAround : spaceEvenly + 시작과 끝의 간격을 1/2
2. Row
   1. MainAxisAlignment.start : 위젯 들이 왼쪽으로 정렬됨
   2. MainAxisAlignment.end : 위젯 들이 오른쪽으로 정렬됨
   3. MainAxisAlignment.center : 위젯 들이 가운데로 정렬됨
   4. MainAxisAlignment.spaceBetween : 위젯과 위젯 사이가 동일하게 정렬됨
   5. MainAxisAlignment.spaceEvenly : 위젯을 같은 간격으로 배치하지만, 시작과 끝이 빈 간격으로 둔다.
   6. MainAxisAlignment.spaceAround : spaceEvenly + 시작과 끝의 간격을 1/2
