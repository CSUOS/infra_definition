# infra_definition

CSUOS 인프라를 정의하는 repo



## Change Log

### 2020년 08월 22일

1. Kubernetes와 Docker, 두가지 환경으로 나눠서 구성함
2. Kubernetes
   1. CSUOS에서 개발한 앱 Deploy용
3. Docker
   1. 앱에서 사용할 Persistent한 백엔드 서비스들
   2. Elasticsearch, Mysql, MongoDB, Minio, etc......

### 2020년 08월 13일

1. ArgoCD를 사용한 연동
2. Longhorn을 활용한 Persistent Volume 구현
3. Traefik을 통한 라우팅

### 2020년 08월 09일

첫 커밋