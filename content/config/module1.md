+++
title = "AWS Config 활성화"
weight = 1
pre = "<b>3.1 </b>"
+++

* * *

 AWS Config 를 이용하여 AWS 자원에 대한 구성 변경 추적 및 규정 준수 여부에 대한 확인을 위해서는 먼저 AWS Config 가 활성화되어야 합니다. 아래의 절차에 따라 AWS Config 를 활성화하시기 바랍니다.

### AWS Config 활성화

1. AWS Config 를 활성화하기 위하여 AWS 메뉴 중 Config 서비스 메뉴로 이동합니다. AWS Config 가 활성화되어 있지 않은 경우 아래와 같이 AWS Config 화면 접속 시 "시작하기" 버튼이 있는 것을 확인할 수 있습니다. AWS Config 활성화를 위하여 "시작하기" 버튼을 클릭합니다.
 ![Config Enabling](/images/enableconfig.png)
2. AWS Config 설정 화면에서 아래와 같이 "모든 리소스" 항목에서 "전역 리소스" 를 체크하고 "버킷 이름" 에는 기본값으로 적용된 S3 버킷에 "awsconfighol" 을 프리픽스로 추가합니다. "Amazon SNS 주제" 항목에서는 "구성 변경 사항과 알림을 Amazon SNS 주제에 스트리밍합니다." 를 선택합니다. 다른 설정은 기본값으로 두고 "다음" 버튼을 클릭합니다.
 ![Config Enabling](/images/enableconfig1.png)
3. AWS Config 규칙 화면에서는 모두 기본값으로 두고 "다음" 버튼을 클릭합니다.
 ![Config Enabling](/images/enableconfig2.png)
4. 검토 화면에서 AWS Config 설정 사항을 확인한 후 "확인" 버튼을 클릭하여 AWS Config 를 활성화합니다.
 ![Config Enabling](/images/enableconfig3.png)

 
