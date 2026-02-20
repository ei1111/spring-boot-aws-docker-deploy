🚀 Spring Boot AWS Docker Deployment

이 프로젝트는 Spring Boot 애플리케이션을 Docker로 컨테이너화하고, GitHub Actions를 사용하여 AWS에 자동 배포하는 CI/CD 예제입니다.

🧱 Tech Stack
- Java 21
- Spring Boot 4 
- Docker 
- GitHub Actions (CI/CD)
- AWS EC2

⚙️ Application Overview
- Spring Boot 기반 REST 애플리케이션
- Java 21 Toolchain 사용
- Gradle 기반 빌드

🐳 Deployment Architecture
- Spring Boot → Docker → GitHub Actions → AWS EC2

Flow
1. GitHub에 코드 Push
2. GitHub Actions 실행 
3. Docker 이미지 빌드 
4. AWS 서버로 이미지 배포 
5. 컨테이너 자동 실행


🎯 Purpose
이 프로젝트는 다음을 목표로 합니다:
- Spring Boot Docker 배포 경험 정리 
- GitHub Actions 기반 CI/CD 구축 
- AWS 인프라 배포 자동화 실습