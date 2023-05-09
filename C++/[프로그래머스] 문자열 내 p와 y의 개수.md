## 문제 링크
https://school.programmers.co.kr/learn/courses/30/lessons/12916

```cpp
#include <string>
#include <iostream>
using namespace std;

bool solution(string s)
{
    bool answer = true;
    int p = 0;
    int y = 0;
    
    for(const char& c : s){
        if(c == 'p' || c == 'P') p++; 
        else if(c == 'y'|| c == 'Y') y++;
    }

    answer = p == y;
    return answer;
}
```

## 문제 풀이 
for문을 돌며 p,P   y,Y 수를 세 같으면 True 다르면 False를 반환 해줬습니다.
