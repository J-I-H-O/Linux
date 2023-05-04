# 02. Linux

### 개념

- IDC(Internet Data Center): 서버를 별도의 시설에 두고 관리하는 것
- IPMI(Intelligent Platform Management Interface): 메인보드에서 제공하는 원격 제어 프로토콜. 원격으로 모든 제어 수행 가능
- Shell: 사용자의 입력을 받아 운영체제에 전달해주는 프로그램
    - 명령을 입력하면 운영체제에 전달하여 실행되고, 그 결과를 출력
    - sh, Bash, Zsh 등
- SSH(Secure Shell)
    - 네트워크 상의 다른 컴퓨터에 로그인 하거나,
    - 원격 시스템에서 명령을 실행하고,
    - 다른 시스템으로 파일을 복사할 수 있도록 해주는 **프로토콜**
- SSH 클라이언트
    - SSH 프로토콜을 이용해 원격 서버에 접속하는 프로그램
    - PuTTY, Xshell 등
- 클라우드 컴퓨팅(cloud computing)
    - 사용자의 물리적인 관리 없이 컴퓨터 시스템 리소스를 필요시 바로 제공(on-demand availability) 하는 것
    - AWS(Amazon web service), Azure(Microsoft Azure), Google Cloud 등
- 포트 포워딩
    - 패킷을 라우터 등의 게이트웨이를 거치는 동안 하나의 IP 주소와 포트 번호 결합을 통해 다른 곳으로 넘겨주는 방식

### 명령어

- ps: 현재 동작중인 프로세스 목록
- help: 명령어 사용법 출력
- man: 명령어에 대한 매뉴얼 페이지 제공
- pwd: 현재 작업중인 디렉토리 명
- ls: 현재 작업 중인 디렉토리 내의 파일 목록
- lscpu: 시스템의 CPU 정보 출력
- free: 시스템의 메모리 정보 출력
- mkdir: 디렉토리 생성
- cd: 해당 디렉토리로 이동
- cat: 파일의 내용 출력