+++
title = "규칙 준수 확인"
weight = 4
pre = "<b>3.4 </b>"
+++

* * *
  이번에는 Security Group 의 설정을 변경하여 이전 과정에서 생성된 AWS Config 규칙이 변경된 Security Group 의 설정을 잘 감시하는지 확인해보도록 하겠습니다.


1. Security Group 의 설정을 변경하기 위해 EC2 메뉴로 이동한 후 아래와 같이 EC2 인스턴스에 할당되어 있는 Security Group 을 선택한 후 "인바운드 규칙 편집" 버튼을 클릭합니다.
 ![SG Changing](/images/changesg1.png)
2. SSH 에 설정되어 있는 1.2.3.4/32 정책을 "삭제"버튼을 클릭하여 삭제합니다.
 ![SG Changing](/images/changesg2.png)
3. "규칙 추가" 버튼을 클릭한 후 아래 화면과 같이 SSH 에 대해 "위치 무관" 하게 접근할 수 있도록 정책을 추가한 후 "규칙 저장" 버튼을 클릭합니다.
 ![SG Changing](/images/changesg3.png)
4. Security Group 에 아래와 같이 SSH 에 대해 Public 접근이 모두 허용되도록 정책이 추가되었습니다.
 ![SG Changing](/images/changesg4.png)
5. Security Group 의 설정이 정상적으로 변경되었다면 이제 AWS Config 메뉴로 이동한 후 "restricted-ssh" 규칙의 상태를 확인하도록 합니다. 아래 화면과 같이 변경된 1개의 Security Group 에 대해 미준수 리소스가 발생된 것을 확인하실 수 있습니다.
 ![SG Changing](/images/changesg5.png)
6. "restricted-ssh" 규칙을 클릭하여 상세 정보를 확인합니다. 아래와 같이 "범위 내 리소스" 부분에 전체 대상 Security Group 중 하나의 Security Group 이 미준수인 것을 확인하실 수 있습니다.
 ![SG Changing](/images/changesg6.png)
7. 이번에는 화면 상단의 "리소스 타임라인" 을 클릭하여 타임라인별 상세 정보를 확인하도록 합니다. "리소스 타임라인" 클릭 시 별도의 탭이 열리게됩니다.
 ![SG Changing](/images/changesg7.png)
8. "리소스 타임라인" 창에서 제공되는 정보 중 "변경 사항" 항목을 펼치게 되면 아래와 같이 Secuirty Group 의 설정 변경 사항에 대한 상세 정보를 확인하실 수 있습니다.
 ![SG Changing](/images/changesg8.png)
9. 이번에는 "규칙 준수 타임라인" 탭을 클릭하시고 Security Group 의 시간 별 규칙 준수에 대한 상세 정보를 확인하시기 바랍니다.
 ![SG Changing](/images/changesg9.png)