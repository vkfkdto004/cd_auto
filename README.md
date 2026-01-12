# cd_auto
ArgoCD를 위한 레포지토리.

```
Github Webhook
|
Jenkins  ----------------
|                       |
image build & push      + -------> cd_auto ---> ArgoCD
|                       |
Dockerhub ---------------

```
와 같은 구조를 가지고 있다.
