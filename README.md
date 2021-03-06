## Python을 활용한 알고리즘 문제 정리 Repo

**이것이 취업을 위한 코딩 테스트다** 책과 **프로그래머스**를 사용했습니다.
******
<h2>당장 좋은 것만 선택하는 그리디</h2>

**1. 현재 상황에서 지금 당장 좋은 것만 고르는 방법**

> **<h3>최소의 동전 개수로 거스름돈 주기</h3>**
> "가장 큰 화폐 단위부터" 돈을 거슬러 주는 것." <br>
> 단 문제에서 요구하는 거슬러 줘야 하는 돈 N은 항상 10의 배수.


**2. 주어진 수들을 M번 더하여 가장 큰 수를 만드는 법칙 연속 K번 초과 불가**

> **<h3>큰 수의 법칙</h3>**
> K = [3,4,3,4,3] 으로 이루어진 list에서 <br>
> K[0], K[2]와 같이 값은 같지만 idx가 다르면 서로 다른 것으로 간주한다.

**3. 각 행마다 가장 작은 수를 찾은 뒤에 그 수 중에서 가장 큰 수를 찾는 게임**

>**<h3>숫자 카드 게임</h3>**
> list에서 가장 작은 원소를 찾아주는 min(), 2중 반복문 구조를 이용할 수 있어야 함.

## 구현, 머릿속에 있는 알고리즘을 정확하고 빠르게 프로그램으로 작성하기.
> **완전탐색: 모든 경우의 수를 주저 없이 다 계산하는 해결 방법.**  
> **시뮬레이션: 문제에서 제시한 알고리즘을 한 단계씩 차례대로 직접 수행해야 하는 문제**

> ### **상하좌우**
> L,R,U,D 를 사용하여 도착할 지점의 좌표를 출력하는 프로그램.  
> 처음에 입력하는 N은 NxN 의 보드를 만들기 위한 입력이다.  
> 공간 밖의 action은 무시 한다.
> <br>
> ### **시각**
> 정수 N이 입력되면 00시00분00초부터 N시59분59초 까지  
> 모든 시각 중에서 3이 하나라도 포함되는 모든 경우의 수를 구하는 프로그램

## DFS/BFS
**그래프를 탐색하기 위한 대표적인 두 가지 알고리즘**
> 탐색(search): 많은 양의 데이터 중에서 원하는 데이터를 찾는 과정  
> 자료구조(DataStructure): 데이터를 표현하고 관리하고 처리하기 위한 구조

**자료구조의 기초 개념**
> ### 삽입(Push): 데이터를 삽입한다.
> ### 삭제(Pop): 데이터를 삭제한다.
> ### 오버플로우(overflow): 자료구조가 수용할 수 있는 범위를 이미 넘어 선 상태에서의 연산수행에서 발생
> ### 언더플로(underflow): 자료구조가 전혀 들어 있지 않은 상태에서 삭제 연산을 수행하면 발생

**스택과 큐**
> 스택(Stack): FILO(FirstInLastOut)선입후출, LIFO(LastInFirstOut)후입선출  
> 큐(Queue): FIFO(FirstInFirstOut)선입선출 