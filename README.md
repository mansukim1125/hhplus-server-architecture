# API 명세서

상품 구매 및 결제 시스템을 위한 RESTful API 명세입니다. 상품 조회, 주문 생성, 포인트 충전, 선착순 쿠폰 발급 등의 기능을 제공합니다.

[./docs/openapi.yaml](./docs/openapi.yaml)

# ERD

Users, Products, Orders, Payments, Coupons 등 주요 엔티티 간의 관계를 정의한 데이터베이스 스키마입니다.

[./docs/erd.md](./docs/erd.md)

# 인프라 구성도

AWS 기반 고가용성 아키텍처 구성도입니다. Multi-AZ 구성으로 ELB, EC2, RDS, ElastiCache를 배포하여 안정적인 서비스를 제공하며, SQS와 Elastic Beanstalk Worker를 통해 외부 데이터 플랫폼으로 주문 정보를 비동기 전송합니다.

[./docs/infra.md](./docs/infra.md)