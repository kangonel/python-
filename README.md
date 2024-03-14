# Python-Tutorial
```언어
print("Hello, World!")
```
## Python Syntax 
Python Indentation
```언어
if 5 > 2:
  print("Five is greater than two!")
```
들여쓰기를 쓰지않고 넘어가면 Python에서 오류가 발생한다
  
```언어
  if 5 > 2:
 print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!") 
```
Python Variables
변수에 값을 할당하면 변수가 생성된다
변수 이름은 문자나 밑줄 문자로 시작해야 하며 숫지로 시작 할 수 없다
```언어
x = 112
y = "Hello, World!"
```
Comment
#을 이용해 주석을 표현한다다
#이것은 주석입니다
```언어
print("Hello, World!")
```
## 데이터 유형 가져오기
type()함수를 사용해서 데이터 유형을 가져올 수 있다
```언어
x = 5
print(type(x))
```
<class 'int'>

  ## Python Numbers
  
파이썬에는 세 가지 숫자 유형이 있다

 `int` 정수
 
 `float` 실수 
 
 `complex` 복소수
 
 ## 한 유형에서 다른 유형으로 변환 

 ```언어
x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```
## Python Strings

파이썬에서의 문자열은 작은따옴표나 큰따옴표로 묶인다

` 안녕하세요 `는 `` 안녕하세요 ``와 같다

#변수에 문자열 할당
```언어
a = "고마워"
print(a)
```
### Strings are Arrays

#위치 1의 문자을 가져온다.(첫 번째 문자의 위치는 0임을 기억할것)
```언어
a = "안녕, 반가워
print(a[1])
```
=녕

#`for` 루프를 사용하여 문자열의 문자를 반복할 수 있다
```언어
for x in "catia":
  print(x)
```
### Python While Loops
```언어
i = 1
while i < 6:
  print(i)
  if (i == 3):
    break
  i += 1
  
### Python For Loops

```언어

fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x) 
