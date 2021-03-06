$A$를 $1, 2, \cdots, 2N-1$의 순열로 둡시다. 모든 $i$ ($1 \le i \le N$)에 대해 $B[i]$가 $A[1], A[2], \cdots, A[2i-1]$의 중앙값일 때, 우리는 이러한 길이가 $N$인 배열 $B$를 $A$의 중앙값 배열이라고 합니다.

**참고**: $M$개의 수의 중앙값을 찾으려면 ($M$이 홀수일 때) 숫자들을 오름차순 정렬하여 가운데 있는 ($(M+1)/2$번째) 숫자를 택하면 됩니다.

### 해야 할 일

$N$과 배열 $B$의 각 원소의 값이 주어집니다. 중앙값 배열이 $B$가 되도록 하는 순열 $A$를 찾는 프로그램을 작성하세요.

### 입력 형식

입력은 두 줄로 주어집니다. 첫 번째 줄에는 $N$이 주어집니다. 두 번째 줄에는 배열 $B$의 각 원소가 공백을 사이로 두고 주어집니다.

### 출력 형식

첫 번째 줄에 순열 $A$의 각 원소들 ($2N-1$개)을 공백을 사이로 두고 출력합니다. 이러한 조건을 만족하는 순열 $A$가 여러 개 있다면 아무거나 출력하면 됩니다. 모든 입력 파일에서 적어도 하나 이상의 해가 존재함이 보장되어 있습니다.

### 제약 조건

* $1 \le A[i] \le 2N-1 \forall 1 \le i \le 2N-1$
* $1 \le B[i] \le 2N-1 \forall 1 \le i \le N$
* $1 \le N \le 100,000.$
* 60%에 해당하는 테스트 데이터에 대해서 $N \le 1,000.$

### 입력과 출력의 예


<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th>입력</th>
   <th>출력</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td style="width: 50%;" class="code-font">5<br/>
1 3 3 4 5</td>
   <td class="code-font">1 9 3 2 4 8 7 5 6</td>
  </tr>
 </tbody>
</table>