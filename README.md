# Node Problem Detector and DrainO 설치
Node-problem-detector와 draino 설치 방법

##Node-problem-detector 설치 방법
1. helm 설치
2. repository 추가
```
  helm repo add deliveryhero https://charts.deliveryhero.io/
```
3. 추가 설정파일을 이용하여 설치
```
  helm install -f npd-config.yaml node-problem-detector deliveryhero/node-problem-detector 
```
##DrainO 설치 방법
```
  kubectl apply -f draino.yaml
```
