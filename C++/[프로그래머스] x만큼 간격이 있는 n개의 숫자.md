## 문제 링크
https://school.programmers.co.kr/learn/courses/30/lessons/12954

```cpp
#include <string>
#include <vector>

using namespace std;

vector<long long> solution(int x, int n) {
    vector<long long> answer;
    
    for(int i = 1; i <= n ; i++)
        answer.push_back(x * i);
    
    return answer;
}
```

## 문제 풀이
for문을 n만큼 돌아(1부터 시작) x * i 값을 넣어주었습니다.
