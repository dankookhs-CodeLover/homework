### 재귀함수 문제 풀이
## ex00
- 1부터 N까지의 합을 재귀함수를 이용해서 구해봅시다.
```c
int sum(int n)
{
}
```

## ex01
- 숫자의 각 자리수의 곱을 리턴하는 함수를 만들어봅시다.
- 예를들어서 n = 12345라면 각 자리수의 곱은 1 * 2 * 3 * 4 * 5 = 120 입니다.

```c
int digit_multiply(int n)
{
}
```

## ex02
- putchar 함수만을 이용해서 숫자를 출력하는 함수를 만들어봅시다. (재귀)
- 편의를 위해 음이 아닌 정수만 생각합시다. (n은 unsigned int)
```c
int print_number(unsigned int n)
{

}
```

## ex03
- 이분탐색 알고리즘을 재귀함수를 사용하여 구현해봅시다.
- 이분탐색 알고리즘이란 - 정렬된 배열 안에서 숫자를 찾는 알고리즘.
- 단, 한 번에 범위를 절반으로 줄인다.

```c
/*
 * array : 숫자가 저장된 배열
 * start_idx : 탐색을 시작하는 인덱스
 * end_idx : 탐색이 끝나는 인덱스
 * target : 찾으려는 숫자
 * 리턴값 : target의 인덱스 (없으면 -1)
 */
int binary_search(int *array, int start_idx, int end_idx, int target)
{

}

// 호출 예시
int array[] = {1, 2, 8, 9, 12};
int idx = binary_search(array, 0, 4, 9);
if (idx == -1) {
  // not found
} else {
  // found
}
```

