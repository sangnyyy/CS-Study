# AOP Proxy

![image](https://trello-attachments.s3.amazonaws.com/5af268949010e31ac06a7770/5b012653ae5cf77cd8a1b6ac/5f936ac130047cb1f5396d8b186a05e8/267BA1385510355B2E2375.png)

## 정의
프록시란 대리인이라는 의미를 내포하고 있으며 스프링 AOP에서의 프록시란 말그대로 대리하여 업무를 처리. 함수 호출자는 주요 업무가 아닌 보조 업무를 프록시에게 맡기고, 프록시는 내부적으로 이러한 보조 업무를 처리한다.

## 장점
이렇게, 보조업무가 필요한 경우 프록시만 추가하면되고, 필요없으면 제거하면 되므로 탈/부착이 쉬워지고 보조업무의 코드 변경으로 인해 발생하는 코드 수정작업이 필요없게됨!