# 문제

한국정보기술진흥원에서는 매 여름과 겨울 학술대회가 개최된다.

2024 하계 학술대회에서는 "디지털인문학" 트랙과 "공공빅데이터" 트랙으로 2개의 트랙이 개설되었다.

진흥이는 이번 학술대회에 참가하고자 하는데 어느 트랙으로 참가해야 할지 몰라 여러분 들의 도움을 받고자 한다.

진흥이의 논문 주제가 주어질 때 어느 트랙으로 참가해야 할지 알려주자.

트랙의 판단 기준은 논문의 주제가 주어졌을 때 특정 단어가 포함되어 있다면 해당 트랙으로 참가하면 된다.

무조건 한 트랙으로만 결정될 수 있는 입력만 주어진다.

| 트랙명 | 판단 단어 |
| ---- | ---- |
| 디지털인문학 | `social`, `history`, `language`, `literacy` |
| 공공빅데이터 | `bigdata`, `public`, `society` |

# 입력

입력 첫 줄에 100자 이하의 영어 대소문자와 공백으로 이루어진 논문 주제가 주어진다.

# 출력

판단 결과, 디지털인문학에 속하면 `digital humanities`를, 공공빅데이터에 속하면 `public bigdata`를 출력한다.

# 서브태스크

| 번호 | 배점 | 제한 |
| ---- | ---- | --------- |
| 1    | 5   | 주제가 공백이 없는 한 단어로만 주어진다. |
| 2    | 95  | 추가 제약 조건이 없다. |