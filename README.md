# Spring Boot · MSA 강의 실습 시작점

스파르타 MSA 학습을 위한 Spring Boot 프로젝트 초기 구성입니다. Java 21·Spring Boot 3.5.11을 기반으로 하며 OpenFeign, Redis, Flyway, QueryDSL, PostgreSQL 등의 의존성이 선언되어 있습니다.

현재 공개 코드는 애플리케이션 진입점과 기본 테스트 중심입니다. 의존성 목록이 각 기능의 구현 완료나 분산 서비스 운영 경험을 의미하지는 않습니다.

- [build.gradle](build.gradle): 빌드·의존성 설정
- [src](src): 애플리케이션과 기본 테스트

실행하려면 JDK 21과 필요한 DB 등 외부 설정을 준비해야 합니다. 서비스 간 통신이나 장애 대응까지 구현한 MSA 예제로 제시하는 저장소는 아닙니다.
