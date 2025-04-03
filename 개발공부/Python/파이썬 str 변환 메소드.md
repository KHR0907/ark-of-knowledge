str 타입의 변수를 쉽게 변환해주는 메소드 종류

```
A='abcd'
print(A.upper()) #ABCD
print(A.capitalize()) #Abcd
print(A.title()) #Abcd

B='a2b3c4'
print(B.uppper()) #A2B3C4
print(B.capitalize()) #A2b3c4
print(B.title()) #A2B3C4

C="abc-def efg"
print(C.upper()) #ABC-DEF EFG
print(C.capitalize()) #Abc-def efg
print(C.title()) #Abc-Def Efg
```

- upper() : 모든 알파벳을 대문자로 변환
- capitalize() : 맨 첫글자만 대문자로 변환
- title() : 알파벳 외의 문자(숫자, 특수기호, 띄어쓰기 등)로 나누어져 있는 영단어들의 첫 글자를 모두 대문자로