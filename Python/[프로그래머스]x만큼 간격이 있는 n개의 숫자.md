

## [문제](https://school.programmers.co.kr/learn/courses/30/lessons/12954)
```
함수 solution은 정수 x와 자연수 n을 입력 받아, x부터 시작해 x씩 증가하는 숫자를 n개 지니는 리스트를 리턴해야 합니다. 다음 제한 조건을 보고, 조건을 만족하는 함수, solution을 완성해주세요.

제한사항
x는 -10000000 이상, 10000000 이하인 정수입니다.
n은 1000 이하인 자연수입니다.

```
<br>

## 마지막 코드

```py
def solution(x, n):
    return list(map(lambda i: i*x, range(1,n+1)))
    #단 한줄!
```
