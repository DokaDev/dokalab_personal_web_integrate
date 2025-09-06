# dokalab_personal_web_integrate

```bash
docker network create dokalab_personal_web_network
docker compose up -d
```

> sync submodules
```bash
git submodule update --remote
```

### 프로젝트 별 Prisma 스키마 업데이트 시 관련 마이그 생성
```bash
npx prisma migrate dev
```
\* 이후 git에 마이그 함께 커밋 필요