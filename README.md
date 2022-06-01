# 점프 투 플라스크

django나 flask를 이용한 웹개발에 대해서 알기 위해, 휴일을 맞아 책 한 권을 따라가봤다.

https://wikidocs.net/book/4542

## Issues

Windows 10, Python 3.10, Visual Studio Code & Powershell을 사용했고, 대부분 환경 문제였다.

1. 파이썬 설치 : 귀찮은 꼴 보기 싫으면 설치할 때 custom을 누르고 환경 변수 추가를 하자.
2. 가상환경 : 파워셀에 Set-ExecutionPolicy Unrestricted 를 쳐줘야 가상환경 스크립트가 사용가능하다.
3. 파워셀 환경변수 : 책에서는 set FLASK_APP=pybo면 충분하다고 나왔지만..
```
## cmd
set FLASK_APP=pybo

## powershell
$env:FLASK_APP = "pybo"
```
