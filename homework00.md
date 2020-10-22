### 이번 homework의 주제
- 입출력
- 변수
- 제어문
- 반복문


## 이번 시간에 풀어드릴 문제들

#### 입출력
- Hello World - https://www.acmicpc.net/problem/2557
- A + B : https://www.acmicpc.net/problem/1000
#### if-else, switch
- 시험 성적 : https://www.acmicpc.net/problem/9498
- 2007년 : https://www.acmicpc.net/problem/1924

#### for, while
- 별찍기 : https://www.acmicpc.net/problem/2438
- A + B - 5 : https://www.acmicpc.net/problem/10952
- A + B - 6 : https://www.acmicpc.net/problem/10953


## 숙제로 풀어올 문제들
- A + B - 4 (Hint : EOF에 대해 알아봅시다.) : https://www.acmicpc.net/problem/10951
- A + B : https://www.acmicpc.net/problem/1000
- 최소, 최대 : https://www.acmicpc.net/problem/10818
- 합 : https://www.acmicpc.net/problem/8393
- 윤년 : https://www.acmicpc.net/problem/2753
- 별찍기 - 5 : https://www.acmicpc.net/problem/2442

## 보너스 문제들

## ex00
- topic : 변수, 제어문

사용자로부터 하나의 수(x)를 입력받아 그 수의 제곱(x*x)을 출력하는 프로그램을 만들어봅시다.<br>
단, 연산 시에 오버플로우가 발생할 경우 "overflow"를 출력해야 합니다. (변수 타입은 무엇을 사용해도 상관 없으나, 오버플로우를 방지해야 합니다.)<br>
입력 예시는 int를 사용한다고 생각하고 작성했습니다.

- 힌트 : 연산 전에 오버플로우를 방지(prevent)하는 방법과 연산 후에 오버플로우를 감지(detect)하는 방법이 있습니다.
- 보너스 : overflow, 변수의 크기가가 중요한 경우에는 int나 long long 보다 int32_t, int64_t와 같이 크기가 명확한 변수를 사용하는 것이 좋습니다.

#### 입력 예시 1
10

#### 출력 예시 1
100

#### 입력 예시 2
100000

#### 출력 예시 2
overflow

## ex01
- topic : 변수, 연산자

다음의 함수의 빈 부분을 채워봅시다.
```c
/* 비트 연산자 (>>, <<, &, |, ~)만을 사용해 어떤 변수가 양수인지, 음수인지 판별하는 함수
n이 음수라면 1을, n이 0 또는 음수라면 0을 리턴
비교 연산자는 사용 불가능 (<, >, ==, <=, >= 사용 불가)
*/
int is_negative(int n) {
  int ans;
  /* ans를 적절히 계산하여 반환 */
  return ans;
}
```
