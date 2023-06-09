## 제로베이스 프론트엔드 스쿨_WordPatternGame
### 문제 설명
상현이는 낱말 게임을 하고 있습니다. 패턴이 주어졌을 때, 이 패턴대로 낱말을 골라 순서에 맞게 연속해서 말하는 게임입니다.

패턴 p은 문자열로, 각 문자가 패턴의 심볼을 표현합니다. 예를 들어 주어진 패턴 p가 "가나나가"라면, 가 나 나 가에 맞는 낱말을 순서대로 말하면 됩니다.

각 패턴에는 아무 낱말이나 사용할 수 있습니다. 단, 다른 패턴에 사용한 낱말을 다시 사용할 수는 없습니다.

예를 들어, 가 패턴에는 드래곤이라는 낱말을 선택하고, 나 패턴에는 바나나라는 낱말을 선택했다면 상현이는 "드래곤 바나나 바나나 드래곤" 이라고 말했을 때 게임에서 승리합니다.

동일한 패턴일 때, 다른 낱말을 선택할 수도 있습니다. 예를 들어 "상현이 천재 천재 상현이"라고 말해도, "땡칠이 바보 바보 땡칠이" 라고 말해도 게임에서 승리합니다.

단, 같은 패턴인데 다른 낱말을 선택하여 "드래곤 바나나 바바나 드레곤"이라고 하거나, 다른 패턴인데 같은 낱말을 선택하여 "집에가고싶다 집에가고싶다 집에가고싶다 집에가고싶다"라고 할 경우에는 게임에서 패배합니다.

패턴 p와 상현이의 답안 s가 주어졌을 때, 게임에서 승리했는지 여부를 출력하는 프로그램을 구현하세요.

### 입력 형식
* p: 패턴 문자가 담긴 문자열
* s: 상현이의 답안이 공백으로 구분되어 담긴 문자열

### 출력 형식
* 정답 여부를 논리 형식으로 반환

### 제약 사항
* p.length = 4
* 0 < s.length <= 1000
### 입출력 예시
* 예시1
  * 입력
  * p = "가나다라"
  * s = "바나나 드래곤 스리랑카 오염"
  * 출력: true
  * 설명: 각 패턴마다 겹치지 않게 낱말을 선택하였으므로 정답이다.
* 예시2
  * 입력
  * p = "갸가갸가"
  * s = "금도끼 은도끼 철도끼 은도끼"
  * 출력: false
  * 설명: 갸 패턴에 금도끼와 철도끼 두 가지 낱말을 섞어 사용했기 때문에 오답이다.