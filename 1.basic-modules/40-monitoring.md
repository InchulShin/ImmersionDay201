# 모니터링 - Amazon CloudWatch

![](./images/amazon-cloudwatch-overview.png)

[Amazon CloudWatch](https://aws.amazon.com/cloudwatch/?nc1=h_ls) 는 DevOps 엔지니어, 개발자, SRE(사이트 안정성 엔지니어) 및 IT 관리자를 위해 구축된 모니터링 및 관찰 기능 서비스입니다. CloudWatch는 애플리케이션을 모니터링하고, 시스템 전반의 성능 변경 사항에 대응하며, 리소스 사용률을 최적화하고, 운영 상태에 대한 통합된 보기를 확보하는 데 필요한 데이터와 실행 가능한 통찰력을 제공합니다. CloudWatch는 로그, 지표 및 이벤트 형태로 모니터링 및 운영 데이터를 수집하여 AWS와 온프레미스 서버에서 실행되는 AWS 리소스, 애플리케이션 및 서비스에 대한 통합된 보기를 제공합니다. CloudWatch를 사용하여 환경에서 이상 동작을 감지하며, 경보를 설정하고, 로그와 지표를 나란히 시각화하며, 자동화된 작업을 수행하고, 문제를 해결하며, 통찰력을 확보하여 애플리케이션을 원활하게 실행할 수 있습니다.

## 사용 사례
### 인프라 모니터링 및 문제 해결
주요 지표 및 로그를 모니터링하고, 애플리케이션 및 인프라 스택을 시각화하며, 경보를 생성합니다. 지표 및 로그를 상관시켜 AWS 리소스에서 성능 문제의 근본 원인을 이해하고 이를 해결합니다. 이때 Amazon ECS, AWS Fargate, Amazon EKS 및 Kubernetes에서 컨테이너 에코시스템 모니터링 기능도 포함됩니다.

### 애플리케이션 모니터링
AWS(Amazon EC2, 컨테이너 및 서버리스) 또는 온프레미스에서 실행되는 애플리케이션을 모니터링합니다. CloudWatch는 자동 대시보드의 지표 및 로그를 포함하여 성능 스택의 모든 계층에서 데이터를 수집합니다.

### 로그 분석
로그를 탐색, 분석 및 시각화하여 운영 문제를 해결하고 애플리케이션 성능을 향상시킵니다. 운영 문제에 빠르고 효과적으로 대처할 수 있도록 쿼리를 수행할 수 있습니다. 문제가 발생한 경우 특별히 구축된 쿼리 언어를 사용하여 즉시 쿼리를 시작해 잠재적인 원인을 빠르게 식별할 수 있습니다.

### 사전 리소스 최적화
CloudWatch 경보는 사용자가 지정하거나 이상 동작을 감지하기 위해 기계 학습 모델을 사용하여 CloudWatch에서 자동으로 생성하는 임계값을 기준으로 지표 값을 감시합니다. 경보가 트리거되면 CloudWatch는 Amazon EC2 Auto Scaling을 자동으로 활성화하거나 인스턴스를 중지하는 작업을 수행할 수 있습니다. 예를 들어, 용량 및 리소스 계획을 자동화할 수 있습니다.

[Previous](./30-iam/iam/5-iam.md) | [Next](./40-monitoring/monitoring.md)