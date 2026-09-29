# ch06-1 실습과제1

## 문제1
find 명령어로 .bashrc 파일의 위치를 검색하라.

## 답
<img width="529" height="102" alt="image" src="https://github.com/user-attachments/assets/0178de89-4a19-44fa-901d-010362257e9c" />


## 문제2
다음 2가지 명령어의 차이는 무엇인가? <br>
$ find . -name ‘*.txt’ <br>
$ find . -name *.txt

## 답
전자는 작은따옴표를 사용했기 때문에 쉘이 와일드카드를 확장하지 않고 find 명령어에 문자열 그대로 전달한다. <br>
반면 후자는 쉘이 와일드카드를 확장하여 의도한 텍스트파일을 못 찾고 오류가 날 수 있다.

## 문제3
--help 옵션을 사용하여 명령어의 사용법을 출력하는 예제를 만들어보라

## 답
cd /usr/lib/gcc/x86_64-linux-gnu 이다. 이때 자동완성 기능을 이용하려면 각 경로의 앞글자를 입력한 후 Tab키를 누르면 된다.<br>

## 문제4
man 명령어로 명령어의 사용법을 출력하는 예제를 만들어보라

## 답
cd ../../../usr/lib/gcc/x86_64-linux-gnu 이다. 마찬가지로 이대도 Tab 키를 이용하면 자동완성 기능을 활용할 수 있다. <br>

## 문제5
cd, ls, cp, rm, ifconfig 명령어의 실행파일이 존재하는 경로를 조사하라.

## 답
<img width="791" height="318" alt="image" src="https://github.com/user-attachments/assets/35701427-8e20-43de-baef-f5960653a0f4" />

