# 점프 투 플라스크

django나 flask를 이용한 웹개발에 대해서 알기 위해, 6/1 지방선거로 인한 휴일에 책 한 권을 따라가봤다.

https://wikidocs.net/book/4542

## Issues

Windows 10, Python 3.10, Visual Studio Code & Powershell을 사용했고, 대부분 환경 문제였다.

1. 파이썬 설치 : 귀찮은 꼴 보기 싫으면 설치할 때 custom을 누르고 환경 변수 추가를 하자.
2. 가상환경 : powershell에 Set-ExecutionPolicy Unrestricted를 쳐줘야 스크립트(~/Script/activate) 사용가능.
3. vscode : ctrl + shift + p를 누르고 >Python: Select Interpreter를 쳐서 인터프리터 선택(가상환경).
4. 환경변수 : 책에서는 set FLASK_APP=pybo면 충분하다고 나왔지만 vscode는 cmd가 아니라 powershell을 쓴다.
```
## cmd
set FLASK_APP=pybo

## powershell
$env:FLASK_APP = "pybo"
```

그 외에 생긴 문제는 거의 ctrl + c, v를 하면 될 걸 직접 쳐보다가 생긴 오타 문제였다.

## Concerns

역시 누군가에게 보여줄 웹 앱을 만들려면 html/css/javascript는 필수인거 같다.

여기서는 부트스트랩(https://getbootstrap.com/docs/5.1/getting-started/download/ )을 썼다.
