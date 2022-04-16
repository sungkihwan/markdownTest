## 2주차 스터디
### 쿠버네티스를 활용한 배포 방법
- 쿠버네티스 클러스터, node, pod 개념
- pod에 컨테이너 띄우는 방법
- kubectl 명령어 사용방법
- auto scaling, graceful shutdown, rolling update
### service 오브젝트 사용방법
- 로드밸런서 타입으로 external ip를 통해서 ingress를 할 수 있음
- 클러스터 ip 타입으로 service name으로 internal ip를 통해서 통신
### 쿠버네티스에 로깅, 모니터링, configmap 사용방법
- helm 사용해서 elk stack, prometheus, grafana 메트릭 툴을 설치하여 사용 가능
- configmap 사용해서 환경변수 설정 가능
