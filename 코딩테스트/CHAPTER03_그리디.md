## 그리디
현재 상황에서 가장 좋아 보이는 것만을 선택하는 알고리즘

### 당장 좋은 것만 선택하는 그리디
- 현재 순간에서 가장 좋아보이는 것 선택
- 현재의 선택이 나중에 미칠 영향에 대해서는 고려하지 않는다
- 알고리즘 문제에서 유형파악이 어렵다면 '그리디'문제일 가능성 높음
- 여러 문제를 풀어보며 익히는 것이 좋다.(외워서X)
  - 예외) 플로이드 워셜(Floyd-Warshall), 디익스트라(Dijkstra,최단 경로 빠르게 찾는 문제,그리디 알고리즘으로 분류 됨)

### 예시1) 거스름돈
거스름돈으로 사용할 500원, 100원, 50원, 10원짜리 동전이 무한히 존재한다고 가정. 거슬러줘야 할 돈이 N원일 때, 거슬러 줘야 할 동전의 최소 개수. 단, N은 항상 10의 배수
- 동전 500,100,50,10원은 항상 큰 단위가 작은 단위의 배수 관계
- 가장 큰 화폐 단위부터 거슬러 주면 좋음.
- (ex-sol)N=1260, 1260/500=2, 260/100=2, 60/50=1, 10/10=1 => 총6개
  ```python
    n=1260
    count=0

    coin_types=[500,100,50,10]
    for coin in coin_types:
        count+=n//coin
        n%=coin
    
    print(count)
  ```

### 큰 수의 법칙
- 입력값 중에서 가장 큰 수와 두 번째 큰 수 저장.
- 단순 풀이
```python
    n, m, k = map(int,input().split())
    data=list(map(int,input().split()))

    data.sort()
    first=data[n-1]
    second=data[n-2]

    result=0

    while True:
        for i in range(k):
            if m==0:
                break
            result+=first
            m-=1
        if m==0:
            break
        result+=second
        m-=1
    print(result)
```
- 가장 큰 수가 더해지는 횟수=int(M/(K+1))*K+M%(K+1)
```python
    data.sort()
    first=data[n-1]
    second=data[n-2]

    count=int(m/(k+1))*k
    count+=m%(k+1)

    result=0
    result+=(count)*first
    result+=(m-count)*second

    print(result)
```

### 숫자 카드 게임
- 여러 개의 숫자 카드 중에서 가장 높은 숫자가 쓰인 카드 한 장을 뽑는 게임.
- 각 행마다 가장 작은 수를 찾은 뒤 그 수 중에서 가장 큰 수
```python
    n,m=map(int,input().split())
    result=0
    for i in range(n):
        data=list(map(int,input().split()))

        min_value=min(data)
        result=max(result,min_value)
    print(result)
```

### 1이 될 때까지
- 어떠한 수 N이 1이 될 때까지 다음의 두 과정 중 하나를 반복적으로 선택하여 수행. 단, 두번째 연산은 N이 K로 나누어떨어질 때만 선택 가능
  1. N에서 1을 뺀다
  2. N을 K로 나눈다.

<개인적 풀이>
```python
    N,K = map(int,input().split())
    result=0
    while True:
        if N==1:
            break
        elif N%K==0:
            N=N//K
            result+=1
        else:
            N=N-1
            result+=1
    print(result)
```