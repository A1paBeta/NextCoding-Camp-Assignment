### 본 문제는 캠프 4일차 과제입니다. 아래의 11문제를 Python으로 작성해서 alp69799@hanyang.ac.kr로 소스코드를 보내주세요.
---------------------------------------------------

#### * 문제를 풀때 참고하면 좋은 사이트 
###### 1. Python document : https://wikidocs.net/book/1553
---------------------------------------------------
#### 문제 1. 홍길동 씨의 과목별 점수는 다음과 같다. 홍길동 씨의 평균 점수를 구해 보자.

국어 : 80, 영어 : 75, 수학 : 55

* 이 문제는 딕셔너리 자료형을 사용하여 프로그램을 작성하셔야 합니다.
---------------------------------------------------
#### 문제 2. 홍길동 씨의 주민등록번호는 881120-1068234이다. 
#### 홍길동 씨의 주민등록번호를 연월일(YYYYMMDD) 부분과 그 뒤의 숫자 부분으로 나누어 출력해 보자.
---------------------------------------------------
#### 문제 3. 주민등록번호 뒷자리의 맨 첫 번째 숫자는 성별을 나타낸다. 주민등록번호에서 성별을 나타내는 숫자를 출력해 보자.
---------------------------------------------------
#### 문제 4. 다음과 같은 문자열 a@b@c@d가 있다. 문자열의 replace 함수를 사용하여 a#b#c#d로 바꿔서 출력해 보자.
---------------------------------------------------
#### 문제 5. [1, 3, 5, 4, 2] 리스트를 [5, 4, 3, 2, 1]로 만들어 출력해 보자.
---------------------------------------------------
#### 문제 6. ['Life', 'is', 'too', 'short'] 리스트를 Life is too short 문자열로 만들어 출력해 보자.
---------------------------------------------------
#### 문제 7. (1,2,3) 튜플에 값 4를 추가하여 (1,2,3,4)를 만들어 출력해 보자.
---------------------------------------------------
#### 문제 8. 다음과 같은 딕셔너리 a가 있다.

>>> a = dict()
>>> a
{}
다음 중 오류가 발생하는 경우를 고르고, 그 이유를 설명해 보자.

1. a['name'] = 'python'
2. a[('a',)] = 'python'
3. a[[1]] = 'python'
4. a[250] = 'python'
---------------------------------------------------
#### 문제 9. 딕셔너리 a에서 'B'에 해당되는 값을 추출해 보자.

>>> a = {'A':90, 'B':80, 'C':70}
---------------------------------------------------
#### 문제 10. a 리스트에서 중복 숫자를 제거해 보자.

>>> a = [1, 1, 1, 2, 2, 3, 3, 3, 4, 4, 5]
---------------------------------------------------
#### 문제 11. 파이썬은 다음처럼 동일한 값에 여러 개의 변수를 선언할 수 있다. 다음과 같이 a, b 변수를 선언한 후 a의 두 번째 요솟값을 변경하면 b 값은 어떻게 될까? 그리고 이런 결과가 오는 이유에 대해 설명해 보자.

>>> a = b = [1, 2, 3]
>>> a[1] = 4
>>> print(b)
