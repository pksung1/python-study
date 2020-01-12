# 2. Using the Python Interpreter

## 2.1.1. 인자전달

인터프리터로 인자를 전달 할 때 문자열의 목록을 변환된다.
이 문자열은 sys모듈의 argv 변수에 저장된다.
import sys 후 sys.argv[0] .. 이런식으로 접근이 가능하다.

## 2.2.1. 소스코드 인코딩

기본적으로 <u>UTF-8</u>로 인코딩이 된다.

표준 라이브러리에선 오직 ASCII 문자만 식별자로 사용하고있는데 범용 코드에서는 이 관례를 따르는것이 좋다고 한다.

인코딩 값을 기본값 외의 것을 선언하려면 파이썬 첫줄에 특별한 주석문을 추가해야한다.

<pre><code># -*- coding: encoding -*-</code></pre>

encoding은 파이썬이 지원하는 코덱중 하나여야 한다.