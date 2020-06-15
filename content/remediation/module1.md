+++
title = "문제 해결"
weight = 1
pre = "<b>5.1 </b>"
+++


### 문제 해결을 위한 등록
문제 해결 작업은 AWS Systems Manager Automation을 사용하여 실행됩니다. 일련의 AWS 권장 문제 해결 작업 또는 사용자 지정 문제 해결 작업 중에서 선택하십시오. 규칙 문제를 해결하려면 테이블에서 범위 내 모든 미준수 리소스를 선택하십시오.

### WAF 로그 발생 

- 문제해결에 사용할 SSM Document 를 위해 [AWS Systems Manager Document](https://ap-northeast-2.console.aws.amazon.com/systems-manager/documents/AWS-DisablePublicAccessForSecurityGroup/description?region=ap-northeast-2) 를 클릭한 뒤 "*mydvwa-*"로 시작하는 버킷을 찾은 뒤 가장 하위 경로로 내려가면 다음과 같이 로그가 쌓인 것을 확인할 수 있습니다. 

