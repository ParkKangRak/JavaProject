# 제로베이스 스쿨_FoodBj

---

### 문제 설명
유명한 먹방 BJ 5명이 짜장면을 제한 시간 내에 다 먹을 시에 짜장면 무료 혜택과 상금 150만 원을 받게 되는 중국집을 방문했습니다.
첫 번째 짜장면을 다 먹은 BJ는 다음 짜장면도 먹을 수 있고, 혜택과 상금도 동일하게 제공됩니다.
짜장면 세 그릇을 먹은 1명의 BJ만이 우승을 거머쥐었습니다.
짜장면을 한 그릇도 다 먹지 못한 BJ는 없습니다.
참가자 5명의 이름을 BJ 문자열 배열에, 한 그릇씩 먹은 참가자들의 이름을 one 문자열 배열에, 두 그릇씩 먹은 참가자들의 이름을 two 문자열 배열에 담아 주어집니다.
짜장면의 상금으로 수여된 총금액과 우승자의 이름을 출력하는 프로그램을 구현하세요.
출력 문자열 형식은 아래와 같이 하세요.

금액이 1350만 원이고, 우승자 이름이 주책맨일 때, "1350만원(주책맨)"

### 입력 형식
BJ, one, two: 각 조건에 맞는 문자열 배열

### 출력 형식
총 상금과 우승자를 형식에 맞추어 문자열로 반환

### 입출력 예시

---

#### 입력
BJ = {"혁준", "하밥", "양상", "심심이", "소스왕"}

one = {"혁준", "양상"}

two = {"심심이", "소스왕"}
#### 출력
"1350만원(하밥)"
#### 설명
하밥을 제외한 나머지 BJ들은 짜장면을 1개 또는 2개 먹었으므로, 하밥이 짜장면 3개를 먹었다. 총상금은 다 먹은 짜장면 9개에 대한 1350만원이 된다.