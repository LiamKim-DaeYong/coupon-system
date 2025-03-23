# Fastcampus coupon-system 실습
이 프로젝트는 Fastcampus [대용량 트래픽 백엔드 실습 강의](https://github.com/prod-j/coupon-version-management)를 기반으로 한 쿠폰 발급 시스템 실습입니다.  
강의 내용을 그대로 구현하였으며, 버전별 쿠폰 처리 방식과 동시에 성능 테스트, 모니터링까지 포함되어 있습니다.

---

## 📦 모듈 구성

- `coupon-api`: 쿠폰 발급 요청 처리 (Redis 저장)
- `consumer`: Redis 큐를 소비해 DB에 저장
- `core`: 공통 도메인/유틸 모듈
- `monitoring`: Prometheus & Grafana 설정
- `load-test`: 로터스를 활용한 부하 테스트

---

## 🧩 요구 사항

- Java 17+
- Docker / Docker Compose
- Redis, MySQL, Prometheus, Grafana 등

---
