# 파이썬 문법정리
-*- coding: utf-8 -*- 쓰기

## 문자열 출력
a = “hello world”
* print(a)
* a.replace(“hello”, “Hi”) / print(b) : Hi world
* print(a.count(‘l’)) : 3
* print(a.find(“wor”) : 6
* print(a.upper()) : HELLO WORLD
* print(a.lower()) : hello world
* b=a.strip(“hello”) / print(b) : world
* b=a.split(“ ”) / print(b) : split함수의 인자로 전달되는 문자를 기준으로 문자열을 구분해주고 배열로 반환한다. @중요
* b=a.zfill(50) / print(b) : 전체 길이를 50으로 하고 앞쪽을 0으로 채움 (예를 들어 숫자를 표기할때 같은 단위로 표기하기 쉬움)

## 숫자 자료형
* a=10 / b=25.3 / print(a+b) : 35.3 정수+실수 = 실수
* a=10 / b=25.3 / c = “문자열” / print(a+b+c) : 오류
* a // b : a 나누기 b의 몫
* a % b : a 나누기 b의 나머지\
강의에서는 정수나누기 정수를 해도 소수점자리까지 표현한다고 되어있는데 내 경우에는 정수에서 끊긴다. 버전문제인가..?

