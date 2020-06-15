+++
title = "고급 쿼리의 사용"
weight = 2
pre = "<b>3.2 </b>"
+++

* * *
 이번에는 AWS Config 가 활성화된 상태에서 AWS Config 가 제공하는 "고급 쿼리" 기능을 사용해보도록 하겠습니다.

### 고급 쿼리 실행

1. "고급 쿼리" 기능을 사용하기 위하여 AWS Config 메뉴에서 "고급 쿼리" 를 클릭합니다.
![Advanced Query](/images/advancedquery1.png)
2. "고급 쿼리" 메뉴에서 새로운 쿼리를 실행하기 위하여 "새 쿼리" 버튼을 클릭합니다.
![Advanced Query](/images/advancedquery2.png)

3. 새로운 쿼리를 입력하기 위하여 아래의 쿼리를 복사한 후 붙여넣습니다. 붙여넣기가 완료되면 하단의 "실행" 버튼을 클릭하여 고급 쿼리를 실행합니다.
 ```
  SELECT resourceId, resourceName, resourceType, configuration
WHERE resourceType = 'AWS::EC2::SecurityGroup'
  ```
![Advanced Query](/images/advancedquery3.png)

4. 쿼리가 성공하는 경우 아래와 같이 CloudFormation 을 통하여 생성한 Security Group 이 출력되는 것을 확인할 수 있습니다.
![Advanced Query](/images/advancedquery4.png)