#### if문 응용

```python
#if문 쓰는 방법
a = 100

if a <= 100:
    print(a)
    
if a <=100 :
    print(a)
    
if a <= 100: print(a) #가넝
```

```python
#if...else 조건문
a = 110
if a > 120:
    print('a는 120보다 크다.')
else:
    prtin('a는 120보다 작다.')  #a는 120보다 작다.
    
```

```python
#if... elif... else 조건문
b = 20

if b > 30:
    print('청년입니다.') #출력
elif 30<=b<59:
    print('중년입니다.')
else:
    print('노년입니다.')
```



#### for 반복문

* range 함수

```python
for i in range(10): # 0부터 9까지! 총 10개
    print(i)
#출력결과
#0
#1
#2
#...
#9
```

```python
for i in range(10):
    print(i)         #들여쓰기 중요
for i in range(10): print(i) #가넝
```

* 0  1  2  3  4  5  6  7  8  9 처럼 출력되도록

```python
#end 옵션 사용! + '\t':tap키 사용 ok
for i in range(10):
    print(i, end = '  ') 
    

```

* 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 처럼 출력 (마지막 콤마 없애기)

```python
#n의 값이 변하면서 들어가게 됨
n = 0
for i in range(10):
    if n < 9:
        print(i, end = ',') 
    else:
        print(i)  
    n += 1
```



 