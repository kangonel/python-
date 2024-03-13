# python-
# Python-Tutorial
## Python Home
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
```언어
x = 112
y = "Hello, World!"
```
Comment
#을 이용해 주석을 달 수 있다
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
### 문자열 길이

#`len()`함수를 사용
```언어
a = "Hello, World!"
print(len(a))
```
=13
### Check String

`in`과 `not in`을 사용하여 텍스트에 원하는 단어가 있는지 확인 가능하다
```언어
txt = "안녕하세요, 반갑습니다"
print("고마워요" not in txt)
```
= True

`if` 명령문을 통해 활용 가능
```언어
txt = "안녕하세요, 반갑습니다"
if "고마워요" not in txt:
    print("No, '고마워요' is NOT present.")
```
= 
