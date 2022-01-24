데이터구조

* 메소드(method)

`s.v()` `list.append(10) ` `string.split()`



* 문자열 조회/탐색/검증 메소드

`s.find(x)` | x의 첫번째 위치 반환. 없으면 -1

`s.index(x)` | x의 첫번째 위치 반환. 없으면 error

`s.isalpha()` | 알파벳(유니코드상 글자인지) 문자 여부

`s.isupper()` | 대문자 여부

`s.islower() ` | 소문자 여부

`s.istitle()` | 타이틀 형식 여부  ->여부는 True/False(boolean)로 반환



* 문자열 변경 메소드

`s.replace(old, new[,count])` 

대상글자를 새로운 글자로 바꿔서 반환 

count를 실행하면 해당개수만큼(반드시 넣을 필요 없음.)

```python
wooowoo.replace(o,!,2)
#w!!oowoo
```



`s.strip([chars])` 

양쪽을 제거하거나 왼쪽(lstrip)을 제거하거나 오른쪽(rstrip)을 제거

문자열을 제거하지 않으면 공백을 제거

`s.split(sep = none, maxsplit=-1)`

문자열을 특정한 단위로 나눠 리스트로 반환

sep이 none이나 지정되지 않으면 연속된 공백문자를 단일한 공백문자로 간주.

선행/후행/ 공백은 빈 문자열에 포함 시키지 않음

maxsplit이 -1인 경우 제한이 없음

`seperatot'.join([iterable])`

반복가능한 컨테이너요소들을 구분자로 합쳐 문자열 반환

문자열이 아니면 type error

```
'!'.join('hello')
#'h!e!l!l!o'
```



* **세트 변경**

  1. `.discard()` 원소 제거/ 제거할 원소가 없더라고 key에러가 뜨지 않는다.

  2. `.pop()` 임의의 원소를 제거해 반환

  

* **딕셔너리 변경**
* `d.clear()` 모든 항목 제거

`d.copy()` 얕은 복사본

`d.get(key[default]) key error` 발생안함. 디폴트는 none

`.pop(key[default])` key가 딕셔너리에 있으면 제거하고 해당 값 반환 그렇지 앟으면 default 반환

default 값 없으면 key error 발생

`.update()` key, value로 덮어쓰기

