# 0. 정리하는 이유

코테 문제를 풀다가 갑자기 순서가 헷갈렸다. 그래서 정리해놔야 겠다

# 1. For 문 작동 순서

![image-20250124204743516](../../../../../Documents/GitHub/dalcheonroadhead-github-blog/dalcheonroadhead.github.io/images/For문 작동 순서 정리/image-20250124204743516.png)

- 1️⃣: 지역 변수 선언 및 초기화 (해당 부분이 For문 밖에 있어도 된다. 다만 그렇게 하면, for 문이 끝난 뒤에도 i 값이 유지된다.)
- 2️⃣: 중앙의 조건 체크 (여기서 걸리면 for문 내용물에 들어가지 않고 바로 for 문이 끝난다.)
- 3️⃣: 내용물 처리
- 4️⃣: i 크기 올리기 
- 5️⃣: 다시 한 번 더 조건 체크