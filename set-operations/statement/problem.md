# 문제

$0$ 이상의 정수 $N$개를 원소로 갖는 집합 $S$가 주어집니다.
여기서 집합이란, 중복되지 않는 원소의 모음을 말합니다.
원소들은 오름차순으로 $A_1, A_2, \dots, A_N$입니다.

$S$에 다음과 같은 연산을 여러 번 할 수 있습니다.
* $S$의 원소 개수가 $n$일 때, $S$의 원소로 $n$이 있다면 $n$을 제거하고, 없다면 $n$을 추가합니다.

여러분은 $Q$번의 질문에 답해야 합니다.
$i$번째 질문은 아래와 같습니다.

* 집합 $S$에 연산을 추가적으로 $K_i$번 하였을 때, $S$의 모든 원소의 합을 출력합니다. 연산은 질문이 진행됨에 따라 누적됨에 유의하십시오.

# 제한

*  $1 \le N,Q \le 100\ 000$
*  $0 \le A_1<A_2<\dots <A_N\le 1\ 000\ 000\ 000$
*  $1 \le K_j \le 1\ 000\ 000\ 000$
*  모든 $K_j$의 합은 $1\ 000\ 000\ 000$ 이하입니다.


# 서브태스크

| 번호 | 배점 | 제한 |
| ---- | ---- | --------- |
| 1    | 31   | $K_j = 1$, $A_i \le 100\ 000$ |
| 2    | 43   | $A_i \ge 10^8=100\ 000\ 000$ |
| 3    | 26  | 추가 제약 조건이 없습니다. |

# 입력

첫 번째 줄에 $S$의 원소의 개수 $N$이 주어집니다.

두 번째 줄에 $S$의 원소 $A_1,A_2,\dots,A_N$이 주어집니다.

세 번째 줄에 질문의 개수 $Q$가 주어집니다.

다음 $Q$개 줄에 걸쳐 질문이 주어집니다.
그중 $i$번째 줄에는 정수 $K_i$가 주어집니다.

# 출력

$Q$개의 줄에 걸쳐 각 $K_i$마다, 집합 $S$를 가지고 $K_i$번 작업한 후 $S$의 모든 원소의 합을 출력합니다.