# tarot-ledger-api

Tarot + Ledger MVP용 Spring Boot REST API (Java 17, Gradle)  
Local 개발 환경에서 Docker로 PostgreSQL(pgvector 포함)을 띄워 연동합니다.

## Tech
- Java 17
- Spring Boot
- Gradle
- PostgreSQL (pgvector)
- Flyway
- JPA

---

## Prerequisites
- JDK 17 설치
- Docker Desktop 설치/실행

---

## Run (Local)

### 1) DB 실행 (Docker Compose)
프로젝트 루트에서:

```bash
docker compose up -d
docker ps
