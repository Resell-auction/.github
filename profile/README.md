# 🛍 C2C 경매 서비스

<p align="center">
  <img src="https://github.com/user-attachments/assets/6ff80ae8-5810-4b33-83de-b2aa207d46e3">
</p>
<br>

## 🙋‍♂️팀원 소개
<div align="center">
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/184fcc50-d6b3-4d9e-8b43-2bb0406f2f80" width="200" height="200"><br>
      <div><b>팀장</b></div>
      <div><a href="https://github.com/lh991117">이한빈</a></div>
      <div>경매</div>
      <div>Redis와 Caffeine 성능 비교</div>
      <div>검색 기능 강화</div>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/692bd79e-2d9b-4faa-824a-70547c8b48a6" width="200" height="200"><br>
      <div><b>부팀장</b></div>
      <div><a href="https://github.com/Seung-min-88">이승민</a></div>
      <div>결제</div>
      <div>WebSocket 실시간 경매</div>
      <div>스케줄링 서버</div>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b6d4c66c-17f3-403b-a7fe-367bb6c7140e" width="200" height="200"><br>
      <div><b>팀원</b></div>
      <div><a href="https://github.com/pathfinder357">최유준</a></div>
      <div>애플리케이션 준비 및 컨테이너화</div>
      <div> Terraform 코드 작성 (IaC)</div>
      <div>배포 환경 검증 및 트러블슈팅</div>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/5dddceb2-e3c2-451e-99fe-a8783e3ce9f9" width="200" height="200"><br>
      <div><b>팀원</b></div>
      <div><a href="https://github.com/uyr83157">정의용</a></div>
      <div>BigQuery + GA4 활용한 통계 API</div>
      <div>BigQuery ETL 파이프라인 구축</div>
      <div>ELK 스택 로깅 + WAF 도입</div>
      <div>메트릭 모니터링</div>
      <div>Docker image 최적화</div>
      <td align="center">
      <img src="https://github.com/user-attachments/assets/d7487536-590f-45f5-93e1-e26300690192" width="200" height="200"><br>
      <div><b>팀원</b></div>
      <div><a href="https://github.com/pathfinder357">송윤정</a></div>
      <div>쿠폰</div>
      <div>AWS EventBridge</div>
      <div>RestDocs API 자동화</div>
      <div>분산락을 이용한 쿠폰 대량 발급</div>
        <td align="center">
      <img src="https://github.com/user-attachments/assets/4bf16cb2-efd6-48fd-9d45-1d27a518fc85" width="200" height="200"><br>
      <div><b>팀원</b></div>
      <div><a href="https://github.com/pathfinder357">박현승</a></div>
      <div>물품</div>
      <div>물품 이미지 업로드</div>
      <div>AWS S3 기반 이미지 저장 구조 구현</div>
      <div>CloudFront 연동으로 로딩 속도 개선</div>
  </tr>
</table>
</div>

<br>

## 📄프로젝트 소개
**개발 기간**: 2025.04.01 ~ 2025.05.06

`C2C 경매 서비스`는 사용자가 물품을 경매에 올리고 사용자가 실시간으로 물품을 경매할 수 있는 C2C 경매 사이트입니다.
<br>

## 🛠 기술 스택
**라이브러리 & 프레임워크** <br>
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"> <br><br>
**데이터 베이스 & 캐싱** <br>
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/elasticsearch-%230377CC.svg?style=for-the-badge&logo=elasticsearch&logoColor=white"> <img src="https://img.shields.io/badge/opensearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white"> <br><br>
**클라우드 & 인프라** <br>
<img src="https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white"> <img src="https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white">
<img src="https://img.shields.io/badge/amazon%20ec2-FF9900.svg?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/amazon%20ecs-FF9900.svg?style=for-the-badge&logo=amazonecs&logoColor=white">
<img src="https://img.shields.io/badge/aws%20lambda-FF9900.svg?style=for-the-badge&logo=awslambda&logoColor=white"><br><br>
**데이터 트래킹** <br>
<img src="https://img.shields.io/badge/google%20analytics-E37400.svg?style=for-the-badge&logo=googleanalytics&logoColor=white"><br><br>
**스토리지** <br>
<img src="https://img.shields.io/badge/google%20cloud%20storage-AECBFA.svg?style=for-the-badge&logo=googlecloudstorage&logoColor=white"><br><br>
**테스트 & 모니터링** <br>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white">
<img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/kibana-005571.svg?style=for-the-badge&logo=kibana&logoColor=white"><br><br>
**협업 및 문서화 도구** <br>
<img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"> <br><br>
**컨테이너 & 배포** <br>
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"> <br><br>

## ⚙️ System Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/ef1e0408-423e-4962-9067-0ab77ee5460f">
</p>

<br>

## ⛓️ ERD

<p align="center">
  <img src="https://github.com/Resell-auction/AuctionMarket/blob/dev/img/erd2.png?raw=true">
</p>

<br>

## 🧱[와이어프레임](https://docs.google.com/presentation/d/1J85rLEqN8q-g5gu4F7oyU-kvXNy68qDt/edit#slide=id.p6)
<br>

## 📰[API 명세서](https://www.notion.so/API-1e73dcf2500780479a9dd06e715e0f33?pvs=4)
<br>

[RestDocs API](http://auction-market-restdocs-api-bucket.s3-website.ap-northeast-2.amazonaws.com/)

## 🎲 주요 기능
### 경매 생성 로직
![image](https://github.com/user-attachments/assets/41487f3f-648e-484f-9790-666bc563e031)

<br>

### 경매 입찰 로직
![image](https://github.com/user-attachments/assets/eabf19bd-c702-4627-bd78-892bce9a83b6)

<br>

## 🧭[기술적 의사결정](https://www.notion.so/1e83dcf250078033b6facf83fbd65b47?pvs=4)
<details>
<summary>💎 <strong>Terraform 도입 이유</strong></summary>

### 도입 배경

- VPC, Subnet, ALB, ECS Fargate, RDS, OpenSearch 등 복잡한 AWS 리소스 구성 필요
- AWS 콘솔이나 CLI로 수동 설정 시 다음과 같은 문제 발생
    - 사람의 실수(Human Error)
    - 반복 작업으로 인한 시간 낭비
    - 환경 간 인프라 일관성 유지 어려움
    - 변경 이력 관리 및 협업의 어려움

### 선택지 검토

- **AWS CloudFormation**
    - 유지보수성과 가독성이 낮고, 조건/반복문 구현이 어렵고 AWS 종속적이라 미채택

- **AWS CDK**
    - 추상화 계층으로 인해 예측과 디버깅이 어렵고, 선언형 IaC 방식 선호로 인해 미채택

- **Pulumi**
    - 멀티 클라우드 지원은 강력하나 Terraform 대비 커뮤니티와 안정성에서 부족

### 최종 결정

- **Terraform 채택**
    - HCL 기반 선언적 구성: 가독성, 유지보수 용이
    - 성숙한 생태계: 풍부한 문서와 검증된 모듈 활용 가능
    - 멀티 클라우드 확장성 확보

</details>

<details>
<summary>💎 <strong>ECS Fargate 도입 이유</strong></summary>

### 도입 배경

- Docker 기반 Spring Boot 앱을 배포하면서 EC2 기반 인프라의 높은 관리 부담 발생
- 탄력적인 트래픽 대응 및 고가용성 확보를 위해 서버리스 기반의 ECS Fargate 선택

### 선택지 검토

- **EKS**
    - 복잡한 운영 및 학습 난이도 문제로 미채택

- **AWS Lambda**
    - Spring Boot 앱과 호환성 떨어지고 콜드 스타트, 상태 관리 이슈로 부적합

### 도입 효과

- ECS Service Auto Scaling으로 트래픽 변화 대응
- 가용 영역에 걸친 Task 분산 → 고가용성 확보
- ALB 연동으로 헬스체크 및 트래픽 분산 가능

</details>

<details>
<summary>💎 <strong>AWS S3 + CloudFront 도입 이유</strong></summary>

### 도입 배경

- 고화질 이미지 포함 시 서버 저장/제공에 한계 발생
- 빠른 로딩과 안정적인 이미지 제공 필요

### 선택지 검토

- **로컬 저장소**: 저장 공간, 백업, 서버 부하 이슈로 미채택
- **S3 단독 사용**: 반복 요청 환경에서 응답 속도 최적화 한계
- **S3 + CloudFront 조합** 채택

### 최종 결정

- S3로 이미지 저장, CloudFront로 엣지 캐시 전달
- 빠르고 안정적인 사용자 이미지 로딩 제공

</details>

<details>
<summary>💎 <strong>증분 BigQuery ETL 파이프라인 도입 이유</strong></summary>

### 도입 배경

- 전체 데이터 매번 적재(Full Load) 시 시간/리소스 낭비 및 중복 발생
- 데이터 신뢰성 유지와 로딩 속도 향상을 위해 증분 방식 고려

### 데이터 분석

| 데이터셋 | 100 | 1,000 | 5,000 | 10,000 | 50,000 | 100,000 |
|----------|------|--------|--------|---------|----------|-----------|
| 처리시간 | 3743 | 4041   | 4649   | 6466    | 7213     | 8184      |
![Image](https://github.com/user-attachments/assets/230bc4db-c0e0-4f25-afc4-be3a97b2cfbf)

### 최종 결정

- **증분 적재 방식 채택**
    - 처리 시간 단축
    - 리소스 효율 증가
    - 데이터 중복 제거 및 신뢰성 향상

</details>

<details>
<summary>💎 <strong>AWS EventBridge 도입 이유 (쿠폰 만료)</strong></summary>

### 도입 배경

- 쿠폰 유효기간 만료 시 간편하고 확장 가능한 만료 처리 필요

### 선택지 검토

- **메시지 큐**: 유연하지만 직접 구현 필요, 운영 복잡
- **DB 스케줄러**: 단순하지만 대규모 처리에 부적합
- **Redis TTL**: 실시간 감지는 가능하나 유실 위험/효율성 낮음
- **AWS EventBridge** 채택

### 최종 결정

- EventBridge는 시간 기반 이벤트를 AWS가 관리
- 재시도/확장성 보장 + Lambda, SQS 등 연동 유리
- 자원 효율성 + 지연 최소화 + 모니터링/로깅까지 제공

</details>

<details>
<summary>💎 <strong>RestDocs API 도입 이유</strong></summary>

### 도입 배경

- 수동 문서 작성의 번거로움 및 API 변경 시 일관성 문제 발생

### 🔍 선택지 검토

- **Swagger**
    - 사용 편리하나 명세와 실제 코드 불일치 가능
    - 수동 관리 필요

- **RestDocs API** 채택
    - 테스트 기반 자동 문서 생성
    - 정확성, 자동화, 커스터마이징 가능

</details>

<details>
<summary>💎 <strong>실시간 경매 Redis 도입 이유</strong></summary>

### 도입 배경

- 실시간 경매에서 경매 자동 종료, 결제 트리거 등 이벤트 기반 설계 필요

### 선택지 검토

- **AWS EventBridge Scheduler**
    - 예약에 강점 있으나 실시간성 부족, 비용 발생, WebSocket 연동 복잡

- **Redis TTL + Pub/Sub** 채택
    - TTL 만료 → 실시간 감지 (`Keyspace Notification`)
    - 만료 이벤트 → Pub/Sub → 브로드캐스트 가능
    - 추가 비용 없이 내부 인프라에서 처리 가능

### 최종 결정

> 경매 종료를 TTL 기반으로 자동 처리하면서, **만료 감지와 동시에 실시간 브로드캐스트**가 가능한 구조

| 기능 요구사항                         | Redis TTL + Pub/Sub                          |
|--------------------------------------|----------------------------------------------|
| 경매 종료 감지                       | TTL 설정 + Keyspace Notification          |
| 실시간성 유지                        | Pub/Sub 수신 즉시 처리                    |
| 종료 이벤트 전체 사용자 브로드캐스트 | WebSocket 서버에서 실시간 전달            |
| 수평 확장 고려                       | 상태 공유 + 브로드캐스트 확장성 보장     |
</details>

## 🚨[트러블 슈팅](https://www.notion.so/1e83dcf2500780b5bfb6f714fdc30c23?pvs=4)
<details>
<summary>🔎 <strong>트랜잭션 커밋 전 실시간 경매방이 생성되는 문제</strong></summary>

### 문제 상황

- 경매 생성 과정에서 유효성 검증 실패 등으로 인해 **DB에 저장되지 않았음**
- 그러나 DB 트랜잭션 커밋 이전에 **WebSocket 서버에 경매방 생성 요청이 전달되어 방이 생성됨**
- 이후 재시도 시 `auctionId`가 달라지면서 **DB와 실시간 서버 간 auctionId 불일치 문제** 발생

---

### 원인 분석

- `@Transactional` 메서드 내에서 DB 커밋 이전에 실시간 서버로 **외부 요청(WebSocket 경매방 생성 요청)**이 전송됨
- 결과적으로 DB 트랜잭션이 실패하거나 롤백되는 경우에도 WebSocket 서버에는 **유령 경매방이 생성**되어 버림
- 이는 시스템 상태 불일치로 이어져 실시간 경매 기능에 오류를 유발

---

### 해결 방법

- **Spring의 `@TransactionalEventListener` 기능 활용**
    - 트랜잭션이 **정상적으로 커밋된 후에만** 이벤트 리스너가 실행되도록 구조 변경
- DB에 경매 정보가 **정상 저장 완료된 이후에만 WebSocket 서버에 방 생성 요청**을 보냄

</details>

<details>
<summary>🔎 <strong>Redis캐시를 통한 조회 시 직렬화 문제</strong></summary>
  
- 문제 상황
    
    Redis를 사용한 조회 기능에서 첫 시도에 redis키를 생성하고 조회가 정상적으로 진행했지만, 두 번째 시도에서 직렬화 에러가 나타났음
    
- 원인
    
    Redis에 객체를 캐시하거나 역직렬화할 때 `GenericJackson2JsonRedisSerializer`가 `AuctionResponse`를 인스턴스화하려고 시도하지만, 이 클래스에는
    - `@NoArgsConstructor`(기본 생성자 없음)
    - `@JsonCreator` 도 없음
    - 필드도 모두 `final`이어서 필드 기반 주입도 불가능
    
    즉, Jackson이 객체를 만들 수가 없었음
    
- 해결 방법
    1. 기본 생성자 추가 + @Setter 추가
    2. 생성자 기반 역직렬화 설정(@JsonCreator사용)
    
    여기서 첫 번째 방법을 사용하여 해결
</details>

<details>
<summary>🔎 <strong>AWS OpenSearch EC2 연결 실패</strong></summary>
  
- 배경
    AWS OpenSearch VPC 도메인을 구현하여 최종적으로 실행한 다음 날, 확인 차 한번 더 실행을 했었더니 OpenSearch가 막히는 에러가 발생하게 되었다.
    
- 원인
    Chat GPT를 통해 원인을 분석한 결과 AWS OpenSearch 도메인은 생성 직후에 인증을 느슨하게 하지만, 시간이 지나면 강제적으로 IAM 인증을 요구하게 된다고 한다.
    즉, 시간이 지나서 보안 인증이 강력해졌기 때문에 익명 접근을 차단하면서 접근이 불가해진 것이다.
    
- 과정
    그래서 이를 해결하기 위해서 여러 방법을 적용하게 되었다.
  
    1. IAM 인증을 위해서 보안 자격 증명
       IAM 인증을 위해서 AccessKey, SecretKey를 얻기 위해서 현 IAM유저의 보안 자격 증명을 진행하였고 이를 환경 변수로 넣어서 사용하게 되었다.
        
    2. AWS OpenSearch 권한 문제
       AccessKey와 SecretKey를 넣어서 서명 자체는 정확하게 진행됐지만 그 계정이 OpenSearch에 쓰기 권한이 없다는 것이다.
       이를 해결하기 위해서는 현재 사용하고 있는 OpenSearch Access Policies(액세스 정책)을 열어 현재 정책에 나의 IAM 유저를 추가해야한다고 한다.
        
- 해결?
    일단 진행해봤지만 시간 상으로 해결을 하지 못할 것 같기도 하고, merge 이후에 진행을 할 때에도 제대로 작동이 될지에 대한 불안함이 있었기 때문에 VPC 대신 Public으로 OpenSearch를 사용하기로 변경하여 작성하게 되었다.
    결국, 원인 규명까지는 했지만 해결 과정에 다소 시간을 걸릴 것을 감안하여 다른 기술로 우회하기로 결정하게 되었다.
  
</details>

<details>
<summary>🔎 <strong>AWS S3, AWS CloudFront 테스트 문제</strong></summary>
  
### **문제**

- AWS S3와 AWS CloudFront의 이미지 로딩 속도를 비교하기 위해 Postman를 사용하여 테스트를 진행함.
- 하지만 작은 용량 이미지를 업로드한 경우 S3와 CloudFront의 응답 속도 차이가 거의 없었음.
- 이에 따라 큰 용량 이미지를 업로드하여 테스트를 다시 수행하였고, 약 1초 정도의 차이가 발생.

- AWS S3만 사용 시 Postman 응답 [응답 시간: 9.59s]
![Image](https://github.com/user-attachments/assets/df3451e1-007e-4c69-b3da-8c2c0af5486d)

- AWS S3와 AWS CloudFront 사용 시 Postman 응답 [응답 시간: 8.40s]
![Image](https://github.com/user-attachments/assets/9216bdee-2c8f-4397-9f3f-90bd0fd85fc7)

---

### **원인 분석**

- 본래의 목적은 "이미지 로딩 속도" 비교였으나, 당시 수행한 테스트는 "이미지 업로드 속도"에 대한 테스트였음.
- 업로드 속도는 클라이언트의 인터넷 환경 등 외부 요인의 영향을 많이 받기 때문에 결과가 일관되지 않음.

---

### **해결 방법**

- AWS S3와 CloudFront의 역할과 개념을 재정리하며 성능 비교 대상이 정확히 무엇인지 재확인한 후 테스트 대상은업로드가 아닌 "다운로드(로딩)"임을 명확히 함.
- 또한 테스트하기 쉽게 이미지 업로드 성공 후 S3 URL과 CloudFront CDN URL 두 가지 모두 반환하도록 코드 수정.

---

### **테스트 결과**

- API 응답 구조  (S3 및 CloudFront URL 포함)
![Image](https://github.com/user-attachments/assets/50932cbe-117a-418b-9665-c0e36e9de527)
- S3 경로를 통한 이미지 로딩 응답 예시 [응답 시간: 7.4s]
![Image](https://github.com/user-attachments/assets/a66d15a7-8cff-447b-8e7e-1c70fda840c9)
- CloudFront 경로를 통한 응답 예시 [응답 시간: 6.22s]
![Image](https://github.com/user-attachments/assets/e616b116-f474-4fbc-82c2-cd82379aecdd)
- 성능 개선 요약
응답 시간: 7.4초 → 6.22초 (약 16% 개선)

</details>

<details>
<summary>🔎 <strong>분산 락(@DistributedLock) 적용 됐음에도 데이터 정합성이 깨지는 문제</strong></summary>

### 문제 현상

- 선착순 100개의 쿠폰을 발급하는 로직에서, 동시 사용자 요청이 몰릴 경우 실제 발급된 쿠폰 수가 100개를 초과하는 현상 발생.
- 이는 시스템의 핵심 제약 조건(쿠폰 총량 제한)을 위반하여 비즈니스 로직의 신뢰성을 저해함.

---

### 문제 정의

- 다중 클라이언트 환경에서 공유 자원(쿠폰 수량)에 대한 동시 접근 시, 데이터베이스 상태 업데이트의 원자성 및 격리성이 보장되지 않아 발생하는 **경쟁 상태(Race Condition)** 문제
- **문제 발생 시나리오 시각화**
![Image](https://github.com/user-attachments/assets/0b810774-cf6b-49c2-a8ad-3a60b2ea2b0a)

---

### 원인 분석

- 문제의 근본 원인은 **데이터베이스 잠금(Lock)의 생명주기와 트랜잭션(Transaction)의 범위가 일치하지 않았기 때문**.
- 구체적으로, 쿠폰 수량을 변경하는 비즈니스 로직 실행 후 데이터베이스 트랜잭션이 최종 완료(Commit)되기 전에 잠금이 해제됨.

---

### 문제 해결

- **트랜잭션 동기화 (Transaction Synchronization) 적용:** 데이터베이스 잠금의 유지 기간을 트랜잭션의 전체 생명주기와 동기화함
- **트랜잭션이 성공적으로 커밋(Commit)되거나 실패하여 롤백(Rollback)될 때까지 데이터베이스 잠금을 유지**하도록 로직을 수정.
- 이를 통해 특정 트랜잭션이 쿠폰 수량 데이터를 수정하는 동안에는 다른 트랜잭션이 해당 데이터에 접근하는 것을 완전히 차단하여 데이터 정합성을 보장.
- **문제 해결 시나리오 시각화**
![Image](https://github.com/user-attachments/assets/bd2ba52f-54d5-4f15-87cc-9fa56ebb53a3)

</details>

<details>
<summary>🔎 <strong>BigQuery JSON 파싱 오류</strong></summary>
  
### 문제 발생
- 배치 작업 로그에는 BigQuery 쓰기가 성공했다고 나왔지만(`Successfully wrote 1 items to BigQuery`), 실제 BigQuery 테이블에는 데이터가 들어오지 않음.
- Google Cloud Console의 BigQuery 작업 기록에서 다음과 같은 오류가 확인됨.
```bash 
Error while reading data, error message: JSON parsing error in row starting at position 0: No such field: lastModified.
```

---

### 문제 분석

- BigQuery 작업 기록의 오류는 전달받은 JSON 데이터에 `lastModified` 필드가 포함되어 있는데, 대상 테이블(`auctions_winning_bid`) 스키마에는 해당 컬럼이 없어서 파싱에 실패했음을 의미.
- 증분 처리 기준 시각을 관리하기 위해 `AuctionsWinningBidBQDTO` 클래스에 `lastModified` 필드를 추가 했는데, `BigQueryItemWriter`는 `ObjectMapper`를 사용하여 DTO 객체 전체를 JSON으로 변환하므로, 이 `lastModified` 필드도 JSON 데이터에 포함됨.
- 하지만 BigQuery 테이블 스키마에는 해당 컬럼이 없었기 때문에 스키마 불일치 오류가 발생함.
- Spring Batch 로그에서는 API 호출 자체는 성공했기 때문에 쓰기 성공으로 기록됨.

---

### 해결 방법

- BigQuery 테이블에 실제로 저장할 필요가 없는 `lastModified` 필드를 JSON 변환 과정에서 제외하기로 결정.
- **`AuctionsWinningBidBQDTO.java` 클래스의 `lastModified` 필드 위에 Jackson의 `@JsonIgnore` 어노테이션을 추가**

```bash
@JsonIgnore
private Instant lastModified;
```

- 이를 통해 DTO 객체 내에서는 `lastModified` 값을 사용하여 타임스탬프 갱신 로직을 처리하고, BigQuery로 전송되는 JSON 데이터에서는 해당 필드를 제외하여 스키마 불일치 문제를 해결함.
  
</details>

<details>
<summary>🔎 <strong>서비스 간 통신에러(CloudMap)</strong></summary>
  
### 문제 원인

애플리케이션이 AuctionMarket과 WebSocket으로 분리되면서, AuctionMarket 앱이 WebSocket 앱의 기능을 호출해야 할때, Fargate 환경에서는 Task의 IP 주소가 동적으로 할당되고 변경되었음. 기존에 고정된 IP나 DNS 이름을 설정 파일에 하드코딩하는 방식을 사용하였으나 현재 서비스에서 동적으로 변하는 주소로 인해 서비스 간 통신이 끊꼇음.

---

### 기술 도입 및 해결책

동적인 서비스의 네트워크 위치(IP, 포트)를 안정적으로 찾기 위해 AWS Cloud Map을 서비스 디스커버리 솔루션으로 도입.
Terraform([cloudmap.tf](http://cloudmap.tf/))으로 VPC 내에서만 접근 가능한 Private DNS 네임스페이스(예: my-spring-infra.local)를 생성하고, 그 안에 websocket-app이라는 이름의 서비스를 등록.

WebSocketApp을 실행하는 ECS Service([ecs.tf](http://ecs.tf/))가 시작하는 Task들을 이 Cloud Map 서비스(websocket-app.my-spring-infra.local)에 자동으로 등록하도록 service_registries 설정을 추가함.

이때 AuctionMarketApp은 실행 시 Spring WebClient와 AWS SDK를 사용하여 Cloud Map에 등록된 websocket-app.my-spring-infra.local 서비스의 최신 Task IP와 포트 정보를 동적으로 조회하여 HTTP 통신을 수행하고 이를 수행하기 위해 ECS Task Role([ecs.tf](http://ecs.tf/) IAM Policy)에 servicediscovery:DiscoverInstances 권한을 부여함으로써 서비스 디스커버리를 구현함.

---

### 도입 전/후 비교

Before: 서비스 간 통신 시 대상 서비스의 IP 주소를 수동으로 관리하거나, 복잡한 자체 로직 또는 외부 솔루션을 통해서만 해결 이에 따라 IP 변경 시 장애 발생 가능성이 있음.
![Image](https://github.com/user-attachments/assets/c69819b6-82d9-46d2-9f0f-7d05bcb9d724)
After: Cloud Map과 ECS 통합을 통해 서비스 등록 및 조회가 자동화. 각 서비스는 논리적인 서비스 이름만으로 통신 대상을 찾을 수 있어 코드의 유연성과 인프라의 탄력성이 크게 향상.
![Image](https://github.com/user-attachments/assets/7fdfa67f-8043-466e-bc90-3f6240ba09b2)

</details>

<details>
<summary>🔎 <strong>이미지 로딩 속도 테스트 한계</strong></summary>
  
### **문제**

- Postman을 통해 응답 시간을 측정했으나, 실제 사용자 환경과 같은 동시 접속 상황에서는 정확한 판단이 어려움

### **해결 방법**

- 이에 따라, 성능 테스트 도구인 JMeter를 활용해 다수의 사용자가 동시에 이미지를 요청하는 상황을 시뮬레이션 진행
- 그 결과 CloudFront 적용 시 응답 속도가 개선되었고, 고객 사용 환경에서도 안정적으로 작동함을 확인

### 테스트 결과

- 상황: 유저 1000명이 동시에 각각 3번씩 같은 제품 이미지 조회 요청.
- 성능 개선 
**평균 응답 시간**: 6262ms → 2903ms (약 54% 개선)
![Image](https://github.com/user-attachments/assets/064c5d02-6358-4d2a-ac8e-cc62ffeb3d1c)

</details>

## 🔑 [Key Summary](https://www.notion.so/teamsparta/2-ReSell-C2C-1e22dc3ef51480c8ae7cef082afa5911?pvs=4#1e72dc3ef51480e188a5d2021849e048)
### 1. 이미지 응답 속도 최적화
**1-1. 문제 원인** <br>
- 동시에 많은 사용자가 제품 이미지를 조회할 경우 지연이 발생
- AWS S3을 사용할 경우 사용자와 이미지가 저장되어 있는 서버의 물리적 거리 멀수록 지연 시간 증가

**1-2. 기술 도입** <br>
- AWS CloudFront를 도입하여 사용자와 가까운 엣지 서버에서 데이터를 가져옴으로써 응답 속도 개선

**1-3. 성능 비교** <br>
<table>
  <tr>
    <td align="center">
      <dev><b> </b></dev>
    </td>
    <td align="center">
      <dev><b>AWS S3</b></dev>
    </td>
    <td align="center">
      <dev><b>AWS CloudFront</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Samples</b></dev>
    </td>
    <td align="center">
      <dev><b>3000</b></dev>
    </td>
    <td align="center">
      <dev><b>3000</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Avg(ms)</b></dev>
    </td>
    <td align="center">
      <dev><b>6262</b></dev>
    </td>
    <td align="center">
      <dev><b>2903</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Min(ms)</b></dev>
    </td>
    <td align="center">
      <dev><b>119</b></dev>
    </td>
    <td align="center">
      <dev><b>98</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Max(ms)</b></dev>
    </td>
    <td align="center">
      <dev><b>32614</b></dev>
    </td>
    <td align="center">
      <dev><b>31935</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Error(%)</b></dev>
    </td>
    <td align="center">
      <dev><b>0</b></dev>
    </td>
    <td align="center">
      <dev><b>0</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Throughput(req/s)</b></dev>
    </td>
    <td align="center">
      <dev><b>72.2</b></dev>
    </td>
    <td align="center">
      <dev><b>76.5</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Received KB/s</b></dev>
    </td>
    <td align="center">
      <dev><b>36185.1</b></dev>
    </td>
    <td align="center">
      <dev><b>38330.6</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Sent KB/s</b></dev>
    </td>
    <td align="center">
      <dev><b>14.8</b></dev>
    </td>
    <td align="center">
      <dev><b>14.0</b></dev>
    </td>
  </tr>
</table>

<br>

<img src="https://github.com/user-attachments/assets/cda7905c-cb9b-4f76-ad55-fee47826dd0a" width="400" height="250"><br>

**1-4. 성능개선요약** <br>
- **평균 응답 시간**: 6262ms → 2903ms (약 54% 개선)
- **처리량**: 72.2 req/s -> 76.5 req/s (약 6% 개선)

<br>

### 2. 캐시별 조회 기능 개선
캐시가 미적용된 조회 기능과 Redis, Caffeine이 적용된 조회 기능을 테스트
- **테스트 주제**: 조회를 100번 시도 했을 때의 평균 응답 속도
- **테스트 결과**<br>
  <img src="https://github.com/user-attachments/assets/ee3f0b4d-4ad1-41b2-b61b-bc9ae1951f39" width="400" height="250"><br>
<table>
  <tr>
    <td align="center">
      <dev><b> </b></dev>
    </td>
    <td align="center">
      <dev><b>No Cache</b></dev>
    </td>
    <td align="center">
      <dev><b>Redis</b></dev>
    </td>
    <td align="center">
      <dev><b>Caffeine</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Avg(ms)</b></dev>
    </td>
    <td align="center">
      <dev><b>5.26</b></dev>
    </td>
    <td align="center">
      <dev><b>10.05</b></dev>
    </td>
    <td align="center">
      <dev><b>0.12</b></dev>
    </td>
  </tr>
</table>

Caffeine → No Cache → Redis 순으로 응답 속도가 빠름

- **의문점**
    1. 왜 Redis가 느린가?<br>
       Redis는 기본적으로 외부 서버와 TCP 통신을 하기 때문<br>
        1. Java 객체 → JSON 직렬화
        2. Redis로 네트워크 전송
        3. 다시 역질렬화해서 Java 객체로 복구
           반면 Caffeine은 직접 JVM 메모리에서 객체를 바로 꺼내기 때문에 Redis보다 훨씬 빠름

    2. 그럼 No Cache보다 느린가?
        - 데이터가 작고 DB가 로컬에 있으면 단순 쿼리 실행이 Redis 통신보다 빠를 수도 있음
        - Redis는 캐시할 때 Jackson 직렬화/역직렬화가 항상 개임하기 때문에 그만큼 시간이 더 걸리게 됨
        - 캐시 미스가 발생해서 Redis가 무의미하게 조회되고 있을 수도 있음

  즉, 속도만 비교하면 Redis보다 Caffeine이 좀 더 우위에 있음을 알 수 있음

<br>

### 3. 캐시별 조회 기능 개선
MySQL vs 로컬 Elasticsearch vs AWS OpenSearch(퍼블릭 도메인)
- **테스트 방식**: 10000건의 더미 경매 생성 후 경매 목록 검색 속도 비교
- **테스트 결과**<br>
  <img src="https://github.com/user-attachments/assets/2e353298-8c71-4b04-b677-313303d1cb1b" width="400" height="250"><br>
<table>
  <tr>
    <td align="center">
      <dev><b> </b></dev>
    </td>
    <td align="center">
      <dev><b>MySQL</b></dev>
    </td>
    <td align="center">
      <dev><b>Elasticsearch</b></dev>
    </td>
    <td align="center">
      <dev><b>OpenSearch</b></dev>
    </td>
  </tr>
  <tr>
    <td align="center">
      <dev><b>Avg(ms)</b></dev>
    </td>
    <td align="center">
      <dev><b>388</b></dev>
    </td>
    <td align="center">
      <dev><b>245</b></dev>
    </td>
    <td align="center">
      <dev><b>528</b></dev>
    </td>
  </tr>
</table>

- **의문점**
    - 어째서 OpenSearch의 소요 시간이 남들보다 훨씬 더 걸리는가?

    - 원인 분석
      원인은 AWS 외부와 통신이필요한 구조이기 때문임<br>
      로컬 Elasticsearch는 로컬이기 때문에 네트워크 지연이 없지만<br>
      AWS OpenSearch의 경우 AWS 외부와 통신을 하기 때문에 외부 호출로 인해서 시간 소요가 증가함

<br>

### 4. Docker 이미지 최적화를 통한 빌드 및 배포 효율성 증대

- **배경**
    - CI/CD 파이프라인의 효율성을 높이고 배포 시간을 단축하며, 저장 공간 및 네트워크 비용을 절감하는 것의 필요성을 확인.

- **적용된 최적화 기술**
    - 멀티 스테이지 빌드.
    - Docker 레이어 캐싱 활용.
    - 최소한의 런타임 이미지 사용 (jre).
    - 빌드 시 테스트 제외.
      → 빌드 단계는 이미지 생성에만 집중하고, 테스트는 다른 단계에서 처리하여 전체 과정을 효율적으로 만들기 위함.

-** 개선 결과 **
- 이미지 빌드 시간: 1분 12초 → 1분 1초 (약 15.3% 단축)
- 이미지 크기: 450.72 MB → 122.33 MB (약 73% 감소)

-** 최적화 도입 전 후의 결과 비교 **

| 항목             | 최적화 전 | 최적화 후 | 개선 효과       |
|----------------|---------|---------|---------------|
| 이미지 빌드 시간 | 1분 12초 | 1분 1초  | 11초 단축     |
| 이미지 크기       | 450.72 MB | 122.33 MB | 328.39 MB 감소 |

![image](https://github.com/user-attachments/assets/86bffb89-0143-4f63-9e65-fb889af4e8f1)


- **효과**
    - **CI/CD 파이프라인 효율성 증대:**
        - 이미지 빌드 시간이 **약 15.3% 단축**되어 (1분 12초 → 1분 1초) 개발 및 배포 사이클이 단축.
        - 빌드 단계에서 테스트를 분리하여 파이프라인의 각 단계를 명확히 하고 효율성을 높임.
    - **배포 속도 향상 및 비용 절감:**
        - 이미지 크기가 **약 73% 감소**하여 (450.72 MB → 122.33 MB), 컨테이너 레지스트리로의 이미지 푸시 및 배포 서버에서의 이미지 풀 속도 향상.
        - 이미지 크기 감소는 레지스트리 **저장 공간 비용** 및 이미지 전송에 따른 **네트워크 비용** 절감.
    - **리소스 사용 최적화:**
        - 최소한의 런타임 이미지 사용과 최적화된 빌드 과정은 최종 이미지의 크기를 줄여 서버 **디스크 공간 절약.**

- **개선 결과**
    - 이미지 빌드 시간: 1분 12초 → 1분 1초 (약 15.3% 단축)
    - 이미지 크기: 450.72 MB → 122.33 MB (약 73% 감소)


### 5. BigQuery+GA4를 활용한 인사이트 도출 & 데이터 시각화
- **목표**
    - Google Analytics 4 (GA4)에서 수집된 사용자 데이터와 애플리케이션의 경매 낙찰가 데이터를 Google BigQuery 환경에서 통합 분석.
    - 카테고리별 특성 파악, 시계열 트렌드 분석 등 비즈니스 의사결정에 기여할 수 있는 심층적인 인사이트 도출.

- **데이터 분석 접근 방식**
    - **데이터 통합**: GA4의 Raw 데이터를 BigQuery로 Export하고, 내부 경매 시스템의 데이터와 결합하여 사용자 세션부터 최종 구매(낙찰)까지 이어지는 통합 데이터셋 구축.
    - **데이터 분석**: BigQuery의 SQL 쿼리를 활용하여 대규모 데이터를 대상으로 사용자 행동 패턴, 구매 전환율, 카테고리별 선호도, 시간별 트렌드 등 다양한 지표 분석.
    - **인사이트 시각화**: 분석 결과를 직관적으로 이해하고 공유할 수 있도록 주요 지표들을 시각화하여 대시보드 형태로 구성.

- **데이터 시각화**

![image](https://github.com/user-attachments/assets/e84f3540-d32c-4c6b-b06d-802e0b01dacb)
