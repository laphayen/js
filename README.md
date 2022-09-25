
# JavaScript
* 코드 한 줄 식 실행.
* 스페이스, 

## JavaScript 준비
* js의 버전을 최적화가 잘 되어 있는 크롬으로 구동한다.
* editor는 VS code나 Atom 사용

## JS 문법
### JS 출력하기
* console.log(); 사용
<pre><code>console.log('hello JS');
</code></pre>

### (), {}, []
* () - parentheses
* {} - braces
* [] - brackets

### ; - 세미콜론
명령이 끝날 때 세미콜론을 붙인다.
<pre><code>console.log('hello JS');
</code></pre>
<pre><code>console.log('hello'); console.log('JS');
</code></pre>

### //, /**/ - 주석
<pre><code>// console.log('hello'); console.log('JS');
</code></pre>
<pre><code>/* 여러 줄 주석 사용
console.log('hello'); console.log('JS');
*/
</code></pre>

### 들여쓰기
<pre><code>
if (condition) {
    console.log('들여쓰기');
}
</code></pre>

### 자료형
* 자료형(data type)으로 값(value) 조절
* typeof _ -> 자료형 확인
<pre><code>
typeof 'Hello'
typeof 'hello' - 'js'; -> NoN // Not a Number
</code></pre>

#### 문자열
* 문자열 나열
<pre><code>
'hello js';
"hello js";
` 문자열 줄바꿈 가능(enter 포함)
hello\njs
`;
</code></pre>
* " " 공백도 문자열로 포함된다.
* "   " = '   ' -> true
* "how're you?"
* 'how\'re you?'
* 문자열 더하기 'hello' + 'JS' -> -, *, /, % 불가

#### 숫자
* 2진수, 8진수, 10진수, 16진수, 소수
<pre><code>
0x15
3.14
</code></pre>
* **거듭제곱 연산자
<pre><code>
2 ** 3
</code></pre>

* 문자열과 숫자를 더하면 문자열이 된다.
* float 형 계산 시는 int 형 변환 후 계산 -> 실수로 변경.

#### NaN
* parseInt('문자열');
* NaN - 0, '1234' - 1, Number('1234') - 0;

<pre><code>
typeof NaN
</code></pre>

#### -Infinity
<pre><code>
typeof -Infinity
</code></pre>

#### boolean
* 참과 거짓
<pre><code>
5 >= 5; // true
5 <= 4; // false
</code></pre>

<pre><code>
NaN == NaN // 유일 false
</code></pre>

#### Casting
parseInt('1234');
Number('1234') + 5
typeof parseInt('123')
typeof parseFloat('3.14');
Number('3.14');
parseInt('3월');
Number('3월'); -> NaN
'1234'.substr(0, 2)
'1234'.substring(0, 2);

typeof parseInt(prompt());

### 입력 받기
prompt();



### Error
* Uncaught SyntaxError: Invalid or unexpected token