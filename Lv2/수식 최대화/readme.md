#풀이

#맞은 부분
- +, -, + 의 우선순위를 두고 모든 경우를 계산해 봐야 한다
- DFS로 계산을 하거나 Split으로 피연산자와 연산자를 나누어 계산한다(queue를 이용)
- 구현 부분에 있어서 re.split()을 사용

#틀린 부분
- 많아봣자 3! 이므로 6가지의 경우를 간단하게 표기하는것이 더 빠름
- split으로 나누어 queue로 계산하는 것보다 DFS가 더 효율적
- split을 사용하지 못했을때 빠르게 DFS로 넘어갓어야 함
