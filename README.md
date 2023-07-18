TIL

230714
게더 사용법 익히기
vs code 실행

230717
swift 문법 특성

230718
주석, 변수, 메서드 익히기. 메서드가 너무 어렵게 느껴짐20230718

(https://github.com/aera11/-/blob/a9f050ad2cbdf6ea82b03a4aa1861f5dc91253b9/20230718)

](https://github.com/aera11/-/blob/a9f050ad2cbdf6ea82b03a4aa1861f5dc91253b9/20230718)
##20230718

20230718# 변수 선언
a = 10
b = 3.14
c = "Hello, World!"
d = [1, 2, 3]
e = (4, 5, 6)
f = {7, 8, 9}
g = {"apple":1 ,"banana":2, "orange":3}

# 데이터 타입 출력
print("a: ",type(a))
print("b: ",type(b))
print("c: ",type(c))
print("d: ",type(d))
print("e: ",type(e))
print("f: ",type(f))
print("g: ",type(g))

# 덧셈
a = 4
b = 2
total = a + b
print('totla = a+b = ', total)
# 뺄셈
total = a - b
print('totla = a-b = ', total)
# 곱셈
total = a * b
print('totla = a*b = ', total)
# 나눗셈
total = a / b
print('totla = a/b = ', total)
# 나머지
a = 5
b = 2
print('a%b :', a%b)
# 거듭제곱
print('a**b : ',a**b)
# 몫(양수)
print('a//b : ',a//b)
# 몫(음수)
a = -5
print('a//b : ',a//b)

# 비교연산자
a = 5
b = 2
print('a<b : ',a<b)
print('a<=b : ',a<=b)
print('a==b : ',a==b)
print('a!=b : ',a!=b)

# 논리연산자
a = 5
b = 2
c = 3
d = 200

print('a>b and a>c : ',a>b and a>c)
print('a>b and a<c : ',a>b and a<c)
print('a>b or a>c : ',a>b or a>c)
print('a>b or a<c : ',a>b or a<c)
print('a<b : ',a<b)
print('not(a<b) : ',not(a<b))

# 할당 연산자
a = 10
b = 20
m = 15
y = a+b
print(y)
m += 10
print('m += 10 : ',m)
m **= 2
print('m **= 2 : ',m)
m //= 10
print('m //= 10 : ',m)
