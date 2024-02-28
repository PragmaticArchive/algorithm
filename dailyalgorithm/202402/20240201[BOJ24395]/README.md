# [Gold III] 명진이의 신년계획 - 24395 

[문제 링크](https://www.acmicpc.net/problem/24395) 

### 성능 요약

메모리: 69624 KB, 시간: 904 ms

### 분류

다이나믹 프로그래밍, 배낭 문제, 정렬

### 제출 일자

2024년 1월 31일 21:47:31

### 문제 설명

<p>카오스 동아리 사람들은 모두 코딩에 미쳐있기 때문에 주기적으로 약을 처방받는다. 동아리의 회장 명진이는 새해를 맞아 이들 모두를 치료하고자 한다.</p>

<p>그들이 걸린 질병은 총 <em>M</em>종류이며 각 질병은 0 이상, 100 이하의 위험도를 지닌다. 회원들은 걸린 질병에 따라 특정 개수의 빨강, 파랑 알약을 처방받는다.</p>

<ul>
	<li>처방받는 알약의 수와 위험도가 모두 같은 서로 다른 질병이 존재할 수 있다.</li>
	<li>하나의 질병에 대해 여러 번 처방받을 수 없다.</li>
	<li>처방받는 알약의 수는 종류별 50개 이하이며 2종류를 합해 최소 1개 이상이다.</li>
</ul>

<p>명진이는 신년계획에 따라 학생들의 위험군을 계산해 치료 순서 리스트를 작성하고자 한다.</p>

<ul>
	<li>위험군은 해당 학생이 지닐 수 있는 질병들의 위험도 합계의 최대치로 정해진다.</li>
	<li>리스트는 저위험군 학생부터 나열되며, 위험군이 같을 경우 번호가 앞선 학생이 먼저 나온다.</li>
	<li>만약 학생이 지닌 알약이 어떠한 처방으로도 만들 수 없는 경우, 해당 학생은 미친 척하는 정상인으로 위험군이 0이다.</li>
</ul>

<p><em>N</em>명의 학생이 처방받은 빨강, 파랑 알약의 수가 주어졌을 때, 명진이를 도와 치료 순서 리스트를 작성해보자.</p>

### 입력 

 <p>첫째 줄에 <em>N </em>(1 ≤ <em>N</em> ≤ 100,000), <em>M </em>(1 ≤ <em>M</em> ≤ 100)이 공백을 두고 주어진다.</p>

<p>둘째 줄부터 <em>M</em>개의 줄에 걸쳐 <em>M</em>개의 질병에 처방할 빨강, 파랑 알약의 수 <em>R<sub>i </sub></em>, <em>B<sub>i </sub></em>(0 ≤ <em>R<sub>i </sub></em>, <em>B<sub>i</sub></em> ≤ 50, <em>R<sub>i </sub></em>+ <em>B<sub>i</sub></em> ≥ 1)와 위험도 <em>D<sub>i </sub></em>(0 ≤ <em>D<sub>i</sub></em> ≤ 100)가 공백을 두고 주어진다.</p>

<p><em>M</em>+2번째 줄부터 <em>N </em>개의 줄에 걸쳐 <em>N </em>명의 학생이 처방받은 빨강, 파랑 알약의 수 <em>R'<sub>i </sub></em>, <em>B'<sub>i </sub></em>(0 ≤ <em>R'<sub>i </sub></em>, <em>B'<sub>i</sub></em> ≤ 50, <em>R'<sub>i </sub></em>+ <em>B'<sub>i</sub></em>  ≥ 1)가 공백을 두고 주어진다.</p>

### 출력 

 <p><em>N</em>개의 줄에 걸쳐 학생 번호와 위험군을 빈칸을 두고 리스트 순서대로 출력한다.</p>
