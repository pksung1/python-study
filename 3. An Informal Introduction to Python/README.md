# 3. An Informal Introduction to Python

파이썬의 간략한 소개

파이썬의 한줄 주석은 #으로 시작합니다

<pre><code>text = 'Hello world' # 주석 ....</code></pre>

## 3.1. 파이썬을 계산기로 사용하기

1. 일반 사칙계산이 가능하고 괄호로 묶는것도 가능합니다.

<pre><code>
>>> 2+2
4
>>> (50- 5*6)/4
5.0
</code></pre>

나눗셈(**/**)은 항상 **float**을 돌려줍니다.
정수 나눗셈 결과(몫)을 얻으려면 **//** 연산자를 사용합니다.

2. 거듭제곱을 계산할 때는 **`**`\*\* 을 사용합니다.

<pre><code>
>>> 3 ** 2
9
</code></pre>

## 3.1.2 문자열

1. 문자열
   작은따옴표나 큰따옴표로 둘러쌀 수 있습니다.
   따옴표를 이스케이핑 할 떄에는 **`\`**를 사용할 수 있습니다.

<pre><code>>>>'hello world\'s'
"'hello wrold's"
</code></pre>

2. print 함수
   인터프리터에서 문자열을 입력하고 실행하면 양 끝에 따옴표를 포함한 텍스트가 나오게 됩니다.

특수문자를 이용해 좀더 읽기 쉬운 출력을 만들어 낼 수 있습니다.

<pre><code>\t : 탭 ..</code></pre>

\뒤에 나오는 문자가 특수 문자로 취급하기 싫다면 첫 따옴표 앞에 r을 붙여서 **날 문자열(raw string)** 로 만들 수 있습니다.

<pre><code>>>>print('C:\some **\n** ame')
C:\some
ame

>> print(r'C:\some\name')
C:\some\name
</code></pre>
