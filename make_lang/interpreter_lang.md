# 인터프리터언어
인터프리터언어는 컴파일러와 다르게 소스코드를 직접 실행해 줍니다.


예를 들어서 설명해 보면

다음은 인터프리터 언어인 루아를 이용해서 helloworld를 출력하는 것입니다.

```
$ lua
> print ("helloWorld")
helloWorld
>
```
첫줄에 있는 lua라는 명령어는 lua의 인터프리터를 실행하는 명령어 입니다.

2 번째 줄에 보면 >심볼이 나타나게 되는데 이것은 lua소스 코드를 입력을 받겠다는 것 입니다.

print는 루아에서 인자로 받아들인 것을 출력하는 함수 입니다.

인터프리터는 컴파일러와 다르게 소스코드를 변환하지않고 직접실행해 줍니다.
