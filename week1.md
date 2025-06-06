### 위치 추정
**절사평균**
- 의미 : 정해진 개수의 극단값을 제외한 나머지 값들의 평균 -> 극단값이 통계에 반영 x
- 수식 : sum(극단값 제외한 모든 값)/n-극단값 개수

### 변이 추정
**중앙값의 중위절대편차(MAD)**
- 의미 : 중앙값과의 편차의 중앙값의 평균
**순서통계랑**
- 의미 : 최소에서 최대까지 정렬된 데이터 값에 따른 계량형(오름차순이라고 이해함)
**모집단과 표본의 자유도 차이**
- 모집단 -> 편향 추정(자유도=n)
- 표본 -> 비편향 추정(자유도=n-1)

### 상관관계
**상관행렬**
- 의미 : 행과 열이 변수들을 의미하는 표
- 시각화 툴 : 주로 히트맵으로

### 두 개 이상의 변수 탐색하기
**육각형구간 그래프**
- 의미 : 두 변수를 육각형 구간으로 나눈 그림
- 목적 : 산점도에서 점이 너무 많아 겹쳐보일 때 사용 => 표본 적을 땐 산점도, 많을 땐 육각형구간 그래프로 밀도 표현

**등고도표**
- 의미 : 지도상에 같은 높이의 지점을 등고선으로 나타내는 것처럼, 두 변수의 밀도를 등고선으로 표시한 도표
- 목적 : 데이터 밀도의 높낮이를 선으로 표현
- 변수 제한? 기본적으로 3개까지 시각화 가능(x, y, z축)

**바이올린 도표**
- 의미 : 박스플롯과 비슷하지만 밀도 추정을 함께 보여줌
- 목적 : 분포와 밀도 동시에 보기
