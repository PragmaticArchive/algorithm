# [Gold III] 하늘에서 별똥별이 빗발친다 - 14658 

[문제 링크](https://www.acmicpc.net/problem/14658) 

### 성능 요약

메모리: 16044 KB, 시간: 156 ms

### 분류

브루트포스 알고리즘

### 제출 일자

2024년 1월 16일 07:55:00

### 문제 설명

<p>“오빠! 나 얼마만큼 사랑해?”</p>

<p>“널 위해서라면 저기 저 하늘의 별이라도 따다 줄 수 있어. 지금 따줄까?”</p>

<p>“에이, 거짓말!”</p>

<p>“정말이야. 한 번 봐봐!”</p>

<p>욱제는 하늘을 발로 차버렸다. 그랬더니 정말 별이 떨어졌다. 그런데, 정말로 별이 지구로 떨어지기 시작했다. 욱제는 지구를 지키는 정의의 용사가 되기로 결심했다.</p>

<p>“자기야, 나 세계를 지키고 올게. 꼭 돌아올 테니 조금만 기다려줘.”</p>

<p>지구의 파괴를 막기 위해서는 지표면에 떨어지는 별똥별의 수를 최소화해야 한다. 욱제는 커다란 네모난 L*L 크기의 트램펄린을 준비했다. 별똥별이 어디로 떨어질지는 이미 알고 있기 때문에, 욱제는 이 트램펄린으로 최대한 많은 별똥별을 우주로 튕겨낼 계획이다. 하지만 학교 예산으로 트램펄린을 구매하는 욱제는 이 긴급한 와중에도 예산 심의 통과를 기다리느라 바쁘다!</p>

<p>욱제를 도와 세계를 구하자. 최대한 많은 별똥별을 튕겨내도록 트램펄린을 배치했을 때, 지구에는 몇 개의 별똥별이 부딪히게 될까? (별똥별이 떨어지는 위치는 겹치지 않으며 별똥별은 트램펄린의 모서리에 부딪혀도 튕겨나간다!) 트램펄린은 비스듬하게 배치 할 수 없다.</p>

### 입력 

 <p>첫째 줄에 네 정수 N, M, L, K가 주어진다. (1 ≤ N, M ≤ 500,000, 1 ≤ L ≤ 100,000, 1 ≤ K ≤ 100) N은 별똥별이 떨어지는 구역의 가로길이, M은 세로길이, L은 트램펄린의 한 변의 길이, K는 별똥별의 수를 뜻한다. 이후 K개의 줄에 걸쳐 별똥별이 떨어지는 위치의 좌표 (x, y)가 주어진다. (0 ≤ x ≤ N, 0 ≤ y ≤ M)</p>

### 출력 

 <p>욱제가 트램펄린으로 최대한 많은 별똥별을 튕겨낼 때, 지구에 부딪히는 별똥별의 개수를 출력한다.</p>
