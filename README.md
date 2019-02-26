# DevOps
Fastcampus DevOps study Log

# DevOps 강의 정리 

운영의 1순위 : 24/365 안정성
	ex) starbucks : 고가용성 사례?
	 - end user 입장에서 24/365

### AWS < DevOps
- Tools <<< Architecture
- ex) 로드밸런서를 왜/ 언제/ 쓰는지? AWS ELB는 단지 도구사용법

### IaC (Infrastructure as Code) 지향 
- n개 서버에 n*k개의 서버 관리 코드를 일일히 입력 x
- 해당 명렁어를 소스코드를 호출하여 실행 
    - ex) docker stack deploy -c elk_stack.yaml elk

————————————————————

## 1~4 주차 : 다양한 AWS 컴퓨팅 리소스 학습
- 어떻게? 어떤 방식으로?
- AWS WAS 구축 아키텍처의 흐름대로 실습 

## 5~8주차 : Docker Container Ochestration 기술
- k8s 는 수업 볼륨상 다루기 어려움 —> Docker swarm 으로 대체 
- AWS WAS 구축 아키텍처의 흐름대로 실습한 내용을 Docker를 기반으로 아키텍처 구축 
- Beats (경량화된 수집계)  - log 수집 : Filebeat / 서버 리소스 수집 : Metricbeat
- Logstash (무거운 수집계)
