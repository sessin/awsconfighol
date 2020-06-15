+++
title = "EC2 인스턴스 확인"
weight = 3
pre = "<b>1.2 </b>"
+++

### EC2 인스턴스 접속 확인
EC2 인스턴스 스택이 정상적으로 생성되었다면 이전 과정에서 생성한 Key Pair 를 통하여 EC2 에 접속이 가능할 것입니다. SSH 를 이용하여 EC2에 정상적으로 접속이 되는지 확인해보도록 하겠습니다.

- AWS Management Console 의 EC2 인스턴스에서 조금 전 CloudFormation 스택을 통해 생성된 WebServerInsatnce 를 선택한 후 화면 위쪽에 있는 "연결" 버튼을 클릭합니다.
![EC2 Access](/images/ec2instance_connect1.png)

- "연결" 버튼을 누르면 아래와 같은 "인스턴스 연결" 메뉴가 나타납니다. "연결 방법" 을 "EC2 인스턴스 연결(브라우저 기반 SSH 연결)" 로 선택하고 "사용자 이름" 을 "ec2-user" 로 입력한 후 하단의 "연결" 버튼을 클릭합니다.
![EC2 Access](/images/ec2instance_connect2.png)

- 아래와 같이 EC2 인스턴스에 정상적으로 로그인이 되는 것을 확인합니다.
![EC2 Access](/images/ec2instance_connect3.png)


