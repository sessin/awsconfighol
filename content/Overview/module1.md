+++
title = "사전 지식"
weight = 1
pre = "<b>0-1. </b>"

+++

## **AWS Config**

AWS Config는 AWS 계정에 있는 AWS 리소스의 구성을 자세히 보여 줍니다. 이러한 보기에는 리소스 간에 어떤 관계가 있는지와 리소스가 과거에 어떻게 구성되었는지도 포함되므로, 시간이 지나면서 구성과 관계가 어떻게 변하는지 확인할 수 있습니다.

AWS 리소스는 Amazon Elastic Compute Cloud(EC2) 인스턴스, Amazon Elastic Block Store(EBS) 볼륨, 보안 그룹 또는 Amazon Virtual Private Cloud(VPC)와 같이 AWS에서 사용할 수 있는 개체입니다. AWS Config에서 지원되는 AWS 리소스의 전체 목록은 AWS 공식문서의 [AWS Config 지원 리소스 유형 및 리소스 관계 단원](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/resource-config-reference.html)을 참조하십시오.

{{% notice tip %}}
 AWS Config 에 대한 더 자세한 사항은 [AWS Document](https://docs.aws.amazon.com/ko_kr/config/latest/developerguide/WhatIsConfig.html) 를 참고해주시기 바랍니다. 
{{% /notice %}}



## **AWS CloudFormation**

AWS CloudFormation은 Amazon Web Services 리소스를 모델링하고 설정하여 리소스 관리 시간을 줄이고 AWS에서 실행되는 애플리케이션에 더 많은 시간을 사용하도록 해 주는 서비스입니다. 필요한 모든 AWS 리소스(예: Amazon EC2 인스턴스 또는 Amazon RDS DB 인스턴스)를 설명하는 템플릿을 생성하면 AWS CloudFormation이 해당 리소스의 프로비저닝과 구성을 담당합니다. AWS 리소스를 개별적으로 생성하고 구성할 필요가 없으며 어떤 것이 무엇에 의존하는지 파악할 필요도 없습니다. AWS CloudFormation에서 모든 것을 처리합니다. 다음 시나리오는 AWS CloudFormation이 얼마나 유용한지를 보여줍니다.

본 실습에서는 EC2 사용 환경을 구성하기 위해 CloudFormation 템플릿을 실행합니다. 

{{% notice tip %}}
 AWS CloudFormation에 대한 더 자세한 사항은 [AWS Document](https://docs.aws.amazon.com/ko_kr/AWSCloudFormation/latest/UserGuide/Welcome.html) 를 참고해주시기 바랍니다. 
{{% /notice %}}


