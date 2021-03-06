﻿#  Introduction of Anaconda
## 아나콘다란

아나콘다(Anaconda)는 설치 소프트웨어 가운데 하나다. 레드햇에서 만들었으며 칼데라 오픈리눅스 설치 소프트웨어 이름이 리자드(도마뱀)인 것에서 도마뱀을 먹는 비단뱀을 뜻하는 아나콘다라는 이름이 지어졌다. 콘솔판과 GUI판을 함께 제공하기 때문에 컴퓨터 환경에 대해 유연하는 이점이 있다. 파이썬과 C로 만들어졌으며 GUI판에는 PyGTK가, 텍스트판에는 python-newt가 쓰였다. 킥스타트 파일은 자동으로 설치 설정을 해주며 사용자가 최소한의 설치중 감독을 할 수 있다
 - 개발자 : [레드햇](https://www.redhat.com/ko)
 - 프로그래밍 언어 : 파이썬, C
 - 운영체제 : [크로스 플랫폼](https://ko.wikipedia.org/wiki/%ED%81%AC%EB%A1%9C%EC%8A%A4_%ED%94%8C%EB%9E%AB%ED%8F%BC)
 - 종류 : 소프트웨어
 - 라이선스 : [GNU 일반 공중 사용 허가서](https://ko.wikipedia.org/wiki/GNU_%EC%9D%BC%EB%B0%98_%EA%B3%B5%EC%A4%91_%EC%82%AC%EC%9A%A9_%ED%97%88%EA%B0%80%EC%84%9C)
 
 ## 설치방법
 
 텐서플로를 사용하려면 파이썬 개발환경이 필요하다.
 파이썬 공식 사이트에서 인스톨파일을 다운받아 설치가 가능하다.
 운영체제 환경에 맞게 패키지들을 설치할 때 곤란한 경우가 생길 수 있다.
 
 1) 아나콘다 설치
 [여기](https://www.anaconda.com/download/)
 파이썬 2.7과 3.6 버전의 윈도우즈용 설치 파일이 있다.
 윈도우즈용 텐서플로 바이너리 패키지는 현재 파이썬 3.5 버전 이상만 지원하므로 아나콘다의 파이썬 3.6 버전을 설치해야 한다.
 텐서플로의 바이너리는 64비트용이므로 만약 사용하는 컴퓨터가 32비트라면 텐서플로 소스를 직접 컴파일하여 설치해야 한다.
 텐서플로는 공식적으로 윈도우즈에서 직접 소스를 컴파일하는 것을 지원하지 않는다.
 사용하는 윈도우즈 컴퓨터가 32비트인지 64비트인지 확인하려면 [여기](https://support.microsoft.com/ko-kr/help/13443/windows-which-operating-system)를 참고.

아나콘다 5.2 버전은 다음 주소에서 [다운로드](https://repo.anaconda.com/archive/Anaconda3-5.2.0-Windows-x86_64.exe)

2)콘다 및 파이썬 패키지 업데이트

Anaconda Prompt에 들어오면 conda 패키지 관리자를 사용할 수 있습니다. 먼저 conda 자체를 업데이트

```
>conda update -n base conda
```

 다음으로 설치된 파이썬 패키지를 모두 최신 버전으로 업데이트


```
>conda update --all
```

이제 아나콘다 설정을 끝냈다. 이제 텐서플로우를 다운로드
 
 ## 아나콘다가 포함된 운영체제
 
  - 레드햇 엔터프라이즈 리눅스
  - 페도라
  - Oz리눅스
  - CentOS
  
-------
signed by Leader
