### 컨테이너 기술이란 무엇입니까?

오늘날 알고 있는 컨테이너라고 말하면 화물 운송을 위해 배 위로 큰 상자를 쌓고 있는 모습을 연상할 수 있다. 이 컨테이너는(Container) 물품을 넣어 운송을 반복할 수 있는 내구성을 지녔으며 수송해주는 크레인이 있어야 운송해 줄 선박 따위에 컨테이너를 옮길 수 있다. 운송에는 선박, 항공선 등이 있다.

이런 컨테이너 특징은 클라우드 컴퓨팅에서의 컨테이너도 유사하다.

클라우드 컴퓨팅 기술이 크게 발전하기 전까진 하드웨어와 운영체제를 기준으로 가상화 했다면 현재는 미들웨어와 애플리케이션까지 가상화 할 수 있는 컴퓨팅 기술이 ‘컨테이너(Container)’인 셈이다.

### 도커란 무엇입니까?

미들웨어 또는 애플리케이션의 실행환경을 하나의 규격에 담은 것이 컨테이너이며 이 컨테이너를 만들 수 있는 대표적인 도구가 도커(Docker)이다.

### 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

도커 컨테이너가 MariaDB, Tomcat 등 하나의 애플리케이션이라면 애플리케이션이 구동하기 위한 환경설정과 의존 라이브러리 등을 패키징한 것이 도커 이미지이며, 이미지 안의 요소들이 어떻게 실행될 것인지 명세한 것이 도커 파일이다.

즉 도커 컨테이너는 도커 이미지에 의해 생성되고 도커 이미지는 도커 파일에 의해 생성된다.

### 도커 설치하기 (참조: [도커 공식 설치 페이지](https://docs.docker.com/engine/install/))