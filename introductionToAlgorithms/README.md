
### Introduction to Algorithms - Fall 2011
> Youtube Play List : https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb
* 01. 개론 및 간단한 예제 Algorithmic Thinking, Peak Finding
* 04. Heaps and Heap Sort
* 13. BFS(Breadth-First Search)
* 14. DFS(Depth-First Search)
* 15. Signle-Source Shortest Paths Problem
* 16. Dijkstra
* 1922. DP(Dynamic Programming)


---

##### 01. 개론 및 간단한 예제 Algorithmic Thinking, Peak Finding
```
Big Theta (빅오) 

# 꼭대기 찾기 1D
# 리니어서치 (11초) -> 바이너리서치(0.001초)

# 꼭대기 찾기 2D 
# Greedy Ascent algorithm
특점 포인트에서 큰 곳으로 계속 이동 (worst case n*m if(n == m) it's gonna be n^2)

# 2d에서 했던 Binary 서치를 확장 -> 
가운데 컬럼에서 최댓값 찾고 그 컬럼을 기준으로 양옆 비교 
크거나 같으면 그 값이 극댓값 아니면 큰 col에서 다시 시작 
```
##### 04. Heaps and Heap Sort
```
HEAP ADT
insert(S, x) : insert element x into set S
max(S) : return element of S with the largest key
extract_max(S) : not only return the element of largest key but also removes it from S
increase key(S, x, k) : increase the value of x's key to the new value 'k' : like changing priority 

heap is implementation of priority queue (and this is nearly complete binary tree)

root of tree : first element ( i = 1) 
parent(i) = i / 2
left child = 2i
right child = 2i + 1


```
##### 13. BFS(Breadth-First Search)
##### 14. DFS(Depth-First Search)
##### 15. Signle-Source Shortest Paths Problem
##### 16. Dijkstra
##### 1922. DP(Dynamic Programming)
 