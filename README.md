# spring-github-action-app
Spring Boot를 기반으로 한 간단한 웹 애플리케이션으로, GitHub Actions와의 연동(CI/CD)을 테스트

---

- `/` 경로로 접속 시, 애플리케이션 이름과 버전을 출력
- GitHub Actions를 통해 자동 빌드/테스트를 설정할 수 있음
- 간단한 health check 및 버전 확인용 애플리케이션으로도 사용 가능

---

| 기능            | 설명                                      |
|-----------------|-------------------------------------------|
| `/` GET 요청     | 앱 이름과 버전 반환 (`application.properties`에서 설정) |
| GitHub Actions | CI/CD 자동화 테스트용 예시 구성             |
