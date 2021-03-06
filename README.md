# AWS Immersion Day

<p align="center"><img src="./immersion_days_logo.png"></p>

AWS Immersion Day 워크샵에서는 AWS가 주도하는 서비스 설명과 실습 랩을 혼합하여 AWS 기본 서비스와 AWS 보안 조치 및 아키텍처 모범 사례를 위한 주요 개념에 대해 알아봅니다.

실습은 크게 기초와 심화 모듈로 나누어져 있습니다.

기초 모듈에서는 각 AWS 기본 서비스의 다양한 기능을 학습할 수 있습니다. 심화 모듈에서는 각 서비스를 유기적으로 연결하여 3계층 웹 애플리케이션과 같은 아키텍처를 생성하는 방법을 배울 수 있습니다.

## 순서
<details>
<summary>워크샵 시작 전 준비 사항</summary>
<div markdown="1">

- [워크샵 시작 전 준비 사항](./0.preparation-guide/preparation-guide.md)
    - [AWS 계정으로 시작](./0.preparation-guide/10-aws-account.md)
    - [AWS EventEngine으로 시작](./0.preparation-guide/20-event-engine.md)
    - [추가 설정하기](./0.preparation-guide/30-addition-setting.md)
</div>
</details>

<details>
<summary>기초 모듈</summary>
<div markdown="1">

- [기초 모듈](./1.basic-modules/basic-modules.md)
    - [1.컴퓨트 - Amazon EC2](./1.basic-modules/10-ec2.md)
        - [EC2 Linux 실습](./1.basic-modules/10-ec2/ec2-linux.md)
            - [키페어 생성하기](./1.basic-modules/10-ec2/ec2-linux/1-ec2.md)
            - [웹 서버 인스턴스 생성하기](./1.basic-modules/10-ec2/ec2-linux/2-ec2.md)
            - [(옵션) Session Manager를 사용하여 리눅스 인스턴스에 접근하기](./1.basic-modules/10-ec2/ec2-linux/3-ec2-1.md)
            - [리눅스 인스턴스에 접근하기](./1.basic-modules/10-ec2/ec2-linux/3-ec2.md)
            - [(옵션) PuTTy를 사용해서 리눅스 인스턴스에 접근하기](./1.basic-modules/10-ec2/ec2-linux/4-ec2.md)
            - [실습 자원 삭제하기](./1.basic-modules/10-ec2/ec2-linux/5-ec2.md)
        - [EC2 Windows 실습](./1.basic-modules/10-ec2/ec2-windows.md)
            - [키페어 생성하기](./1.basic-modules/10-ec2/ec2-windows/1-ec2.md)
            - [웹 서버 인스턴스 생성하기](./1.basic-modules/10-ec2/ec2-windows/2-ec2.md)
            - [윈도우 인스턴스에 접근하기](./1.basic-modules/10-ec2/ec2-windows/3-ec2.md)
            - [(옵션) 인스턴스 타입 변경하기](./1.basic-modules/10-ec2/ec2-windows/4-ec2.md)
            - [(옵션) Elastic IPs 사용하기](./1.basic-modules/10-ec2/ec2-windows/5-ec2.md)  
            - [실습 자원 삭제하기](./1.basic-modules/10-ec2/ec2-windows/99-ec2.md)
    - [2.스토리지 - Amazon S3](./1.basic-modules/60-s3.md)
        - [Amazon S3 실습](./1.basic-modules/60-s3/s3.md)
            - [S3 생성하기](./1.basic-modules/60-s3/s3/1-s3.md)
            - [S3 버킷에 객체 추가하기](./1.basic-modules/60-s3/s3/2-s3.md)
            - [S3 콘솔에서 객체 작업하기](./1.basic-modules/60-s3/s3/3-s3.md)
            - [S3 버킷에 저장되어 있는 객체 접근하기](./1.basic-modules/60-s3/s3/4-s3.md)
            - [버킷 versioning 활성화하기](./1.basic-modules/60-s3/s3/5-s3.md)
            - [수명 주기 설정하기](./1.basic-modules/60-s3/s3/6-s3.md)
            - [실습 자원 삭제하기](./1.basic-modules/60-s3/s3/7-s3.md)
    - [3.네트워크 - Amazon VPC](./1.basic-modules/20-vpc.md)
        - [VPC 실습](./1.basic-modules/20-vpc/vpc.md)
            - [VPC 생성하기](./1.basic-modules/20-vpc/1-vpc.md)
            - [추가 서브넷 생성하기](./1.basic-modules/20-vpc/2-vpc.md)
            - [라우팅 테이블 편집하기](./1.basic-modules/20-vpc/3-vpc.md)
            - [보안 그룹 생성하기](./1.basic-modules/20-vpc/4-vpc.md)
            - [실습 자원 삭제](./1.basic-modules/20-vpc/5-vpc.md)
    - [4.보안 - AWS IAM](./1.basic-modules/30-iam.md)
        - [IAM 실습](./1.basic-modules/30-iam/iam.md)
            - [태그를 명시한 EC2 인스턴스 생성](./1.basic-modules/30-iam/iam/1-iam.md)
            - [AWS IAM Identities 생성](./1.basic-modules/30-iam/iam/2-iam.md)
            - [리소스 접근 테스트](./1.basic-modules/30-iam/iam/3-iam.md)
            - [EC2 Instance에 IAM Role 부여 및 접근 테스트](./1.basic-modules/30-iam/iam/4-iam.md)
            - [실습 자원 삭제하기](./1.basic-modules/30-iam/iam/5-iam.md)
    - [5.데이터베이스 - Amazon RDS](./1.basic-modules/50-rds.md)
        - [Amazon RDS MySQL 실습](./1.basic-modules/50-rds/rds.md)
            - [VPC 보안 그룹 생성하기](./1.basic-modules/50-rds/rds/1-rds.md)
            - [RDS 인스턴스 시작하기](./1.basic-modules/50-rds/rds/2-rds.md)
            - [EC2 인스턴스에서 RDS 연결하기](./1.basic-modules/50-rds/rds/3-rds.md)
            - [RDS 스냅샷 생성하기(추가 실습)](./1.basic-modules/50-rds/rds/4-rds.md)
            - [RDS 인스턴스 크기 수정하기(추가 실습)](./1.basic-modules/50-rds/rds/5-rds.md)
            - [실습 자원 삭제하기](./1.basic-modules/50-rds/rds/6-rds.md)
    - [6.모니터링 - Amazon CloudWatch](./1.basic-modules/40-monitoring.md)
        - [Amazon CloudWatch 실습](./1.basic-modules/40-monitoring/monitoring.md)
            - [Simple Notification Service (SNS) 토픽 생성하기](./1.basic-modules/40-monitoring/monitoring/1-monitoring.md)
            - [Elastic Compute Cloud (EC2) 인스턴스 생성하기](./1.basic-modules/40-monitoring/monitoring/2-monitoring.md)
            - [CloudWatch Alarm 구성하기](./1.basic-modules/40-monitoring/monitoring/3-monitoring.md)
        - [오토스케일링](./1.basic-modules/10-ec2/ec2-auto-scaling.md)
            - [EC2 오토스케일링 실습](./1.basic-modules/10-ec2/ec2-auto-scaling/ec2-auto-scaling.md)
                - [실습 준비](./1.basic-modules/10-ec2/ec2-auto-scaling/1-ec2-as.md)
                - [시작 템플릿 생성하기](./1.basic-modules/10-ec2/ec2-auto-scaling/2-ec2-as.md)
                - [오토 스케일링 그룹 설치하기](./1.basic-modules/10-ec2/ec2-auto-scaling/3-ec2-as.md)
                - [보안 그룹 구성하기](./1.basic-modules/10-ec2/ec2-auto-scaling/4-ec2-as.md)
                - [오토 스케일링 그룹 테스트하기](./1.basic-modules/10-ec2/ec2-auto-scaling/5-ec2-as.md)
                - [실습 자원 삭제하기](./1.basic-modules/10-ec2/ec2-auto-scaling/6-ec2-as.md)
            - [실습 자원 삭제하기](./1.basic-modules/40-monitoring/monitoring/4-monitoring.md)
</div>
</details>

<details>
<summary>심화 모듈</summary>
<div markdown="1">

- [심화 모듈 - 웹 애플리케이션](./2.advanced-modules/advanced-modules.md)
    - [1.컴퓨트 – Amazon EC2](./2.advanced-modules/compute.md)
        - [웹 서버 인스턴스의 시작](./2.advanced-modules/compute/10-launching.md)
        - [오토 스케일링 웹 서비스 배포](./2.advanced-modules/compute/20-auto-scaling.md)
        - [웹 서비스 확인 및 테스트](./2.advanced-modules/advanced-modules/compute/30-test-service.md)
        - [부록 - 추가적인 EC2 개념들](./2.advanced-modules/compute/40-appendix.md)
    - [2.스토리지 – Amazon S3](./2.advanced-modules/storage.md)
        - [S3에 Bucket 생성](./2.advanced-modules/storage/create-bucket.md)
        - [버킷에 오브젝트 추가하기](./2.advanced-modules/storage/put-object.md)
        - [오브젝트 보기](./2.advanced-modules/storage/view-object.md)
        - [정적 웹 사이트 호스팅 사용](./2.advanced-modules/storage/static-web-hosting.md)
        - [오브젝트 이동](./2.advanced-modules/storage/move-object.md)
        - [버킷 버저닝 활성화](./2.advanced-modules/storage/enable-versioning.md)
        - [오브젝트 및 버킷 삭제](./2.advanced-modules/storage/delete-bucket.md)
    - [3.네트워크 – Amazon VPC](./2.advanced-modules//network.md)
        - [VPC 생성](./2.advanced-modules/network/10-index.md)
        - [(옵션) VPC 엔드포인트](./2.advanced-modules/network/20-index.md)
        - [부록 - 추가적인 VPC 개념들](./2.advanced-modules/network/30-index.md)
        - [Amazon API Gateway](./1.basic-modules/20-vpc/api-gateway.md)
            - [전제 조건 및 Lambda 배포](./1.basic-modules/20-vpc/api-gateway/1-apigateway.md)
            - [첫 번째 API 만들기](./1.basic-modules/20-vpc/api-gateway/2-apigateway.md)
            - [메시지 변환](./1.basic-modules/20-vpc/api-gateway/3-apigateway.md)
            - [검증 요청](./1.basic-modules/20-vpc/api-gateway/4-apigateway.md)
            - [인증 및 권한 부여](./1.basic-modules/20-vpc/api-gateway/5-apigateway.md)
            - [API 배포](./1.basic-modules/20-vpc/api-gateway/6-apigateway.md)
            - [메시지 캐싱(선택 사항)](./1.basic-modules/20-vpc/api-gateway/7-apigateway.md)
            - [사용 계획 및 메시지 조절(선택 사항)](./1.basic-modules/20-vpc/api-gateway/8-apigateway.md)
            - [리소스 정리](./1.basic-modules/20-vpc/api-gateway/9-apigateway.md)
    - [4.데이터베이스 – Amazon Aurora](./2.advanced-modules/database.md)
        - [데이터베이스 – Amazon Aurora](./2.advanced-modules/database.md)
        - [VPC 보안 그룹 생성](./2.advanced-modules/database/create-sg.md)
        - [RDS 인스턴스 생성](./2.advanced-modules/database/create-rds.md)
        - [RDS 크레덴셜 저장하기](./2.advanced-modules/database/connect-app.md)
        - [웹앱 서버와 RDS 연결](./2.advanced-modules/database/update-asg.md)
        - [(옵션) RDS 관리 기능](./2.advanced-modules/database/manage-rds.md)
        - [도전 과제 - RDS Aurora 연결](./2.advanced-modules/database/challenge-aurora.md)
    - [5.실습 리소스 정리](./2.advanced-modules/cleanup.md)
</div>
</details>