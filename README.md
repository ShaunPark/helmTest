# Node Problem Detector and DrainO 설치
Node-problem-detector와 draino 설치 방법

1. Node-problem-detector 설치 방법
아래 명령어를 실행

  helm install -f npd-config.yaml node-problem-detector deliveryhero/node-problem-detector 

2. DrainO 설치 방법

  kubectl apply -f draino.yaml
