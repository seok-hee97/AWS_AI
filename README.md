## KOCW

클라우드 기반의 AI 서비스 개발

http://kocw.or.kr/home/cview.do?cid=d7218012387b3e62


### [TOC]
- ch01.  
OT, 클라우드와 인공지능 서비스
- ch02.  
AWS 설명

- ch03.  
EC2 :클라우드 가상서버

- ch04.  
EC2 :클라우드 스토리지

- ch05.  
EC2와S3을 이용한 AI 개발 

- ch06.  
SageMaker

- ch07.  
SageMaker Notebook instance

- ch09.  
SageMaker Studio I

- ch10.  
SageMaker Studio II

- ch11.  
SageMaker Autopilot

- ch12.  
SageMaker Studio I

- ch13.  
AWS AI service

- ch14.  
Various cloud platform usage  










## [aws-sagemaker-serverless]


- Amazon Sagemaker Serverless Interence
-서버리스 기계 학습 추론 기능
https://aws.amazon.com/ko/blogs/korea/amazon-sagemaker-serverless-inference-machine-learning-inference-without-worrying-about-servers/



완전관리형 ML 서비스인 Amazon Sagemaker는 이러한 모든 사용 사례를 지원하기 위해 다양한 모델 추론 옵션을 제공

- 밀리초 단위로 지연 시간이 짧은 워크로드를 위한 Sagemaker 실시간 추론
https://docs.aws.amazon.com/sagemaker/latest/dg/realtime-endpoints.html

- 페이로드 크기가 크거나 처리 시간이 긴 추론을 위한 Sagemaker 비동기식 추론
https://docs.aws.amazon.com/sagemaker/latest/dg/async-inference.html

- 데이터 배치에 대한 예측을 실행하기 위한 SageMaker 배치 변환
https://docs.aws.amazon.com/sagemaker/latest/dg/batch-transform.html

- 트래픽 패턴이 간혈적이거나 드문 워크로드를 위한 SageMaker Serverless Inference
https://docs.aws.amazon.com/sagemaker/latest/dg/serverless-endpoints.html



#### SageMaker Serverless Inference 
(https://docs.aws.amazon.com/sagemaker/latest/dg/serverless-endpoints.html)

- Register and Deploy Models with Model Registry
https://docs.aws.amazon.com/sagemaker/latest/dg/model-registry.html
- Create and Manage Sagemaker Pipeline
https://docs.aws.amazon.com/sagemaker/latest/dg/pipelines-build.html


- SageMaker Serverless Inference Python SDK 코드 라이브러리
https://sagemaker.readthedocs.io/en/stable/overview.html#sagemaker-serverless-inference
- _class_`sagemaker.serverless.serverless_inference_config.``ServerlessInferenceConfig`(_memory_size_in_mb=2048_, _max_concurrency=5_, _provisioned_concurrency=None_)
https://sagemaker.readthedocs.io/en/stable/api/inference/serverless.html

- Amazon SageMaker를 위한 서버리스 엔드포인트 만들기(X)(lambda,gateway)
https://aws.amazon.com/ko/blogs/korea/build-a-serverless-frontend-for-an-amazon-sagemaker-endpoint/


- Create a serverless endpoint 서버리스 앤드포인트 생성
https://docs.aws.amazon.com/sagemaker/latest/dg/serverless-endpoints-create.html





- Amazon Elastic Container Registry
어디서나 컨테이너 소프트웨어를 쉽게 저장, 공유 및 배포
https://aws.amazon.com/ko/ecr/




#### [github]

git clone 하지않고 github에 레포 만들고 로컬파일 추가하기


local 폴더에 추가하기
```
git init
```

```
git remote add origin <GitHub 레포지토리 주소>
```

```
git add .
```


```
git commit -m "init commit message
```


```
git push -u origin main
```

