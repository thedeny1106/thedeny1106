# ☁️ 박재우 | Cloud & Infrastructure Engineer

> 백엔드 개발 경험을 바탕으로 시스템의 통신 흐름과 병목을 계층별로 추적하고, 안정적인 가상화·클라우드 환경을 설계·구축합니다.

---

### 🛠 Core Competencies (Infra & DevOps)
- **Virtualization & Private Cloud**: OpenStack (Kolla-Ansible), KVM/QEMU 기반 가상화 플랫폼 구축
- **Container & Orchestration**: Kubernetes, AWS EKS, Docker, kubeadm, etcd 클러스터 운영
- **Traffic & Mesh**: Istio, KEDA 기반 오토스케일링 및 트래픽 라우팅 제어
- **Networking & Security**: Linux Networking, Cloudflare Zero Trust Tunnel, VPC Peering, NAT/Firewall
- **IaC & Automation**: Ansible, Terraform, Shell Script
- **Observability**: Prometheus, PromQL, ELK Stack

---

### 📌 Key Projects & Infrastructure Labs

#### 1. OpenStack 사설 클라우드 구축 및 보안 터널링 인프라
- **기술 스택**: OpenStack, Kolla-Ansible, Cloudflare Tunnel, Linux Bridge / OVS
- **수행 내용**: 
  - Kolla-Ansible을 활용하여 가상 머신 환경 내 OpenStack 제어 노드 구축 및 플랫폼 구조 실습
  - 물리 네트워크 포트와 OpenStack Neutron 가상 브릿지(`br-ex`) 간 연결 및 트래픽 라우팅 구현
  - Cloudflare Tunneling을 적용하여 공인 IP 포트 노출 없이 외부 접근이 가능한 보안 인그레스 구성

#### 2. Kubernetes / EKS 클러스터 운영 및 트래픽 제어
- **기술 스택**: AWS EKS, Kubernetes, Istio, KEDA, Prometheus
- **수행 내용**:
  - 제한된 가상 머신 리소스 환경에서 kubeadm 기반 클러스터 컴포넌트(etcd 등) 호환성 및 관리 최적화
  - Istio 서비스 메시를 활용한 세부 트래픽 라우팅 및 KEDA 이벤트 기반 오토스케일링 환경 구성
  - AWS VPC Peering, 보안 그룹, 라우팅 테이블 및 서브넷 설계를 통한 클라우드 네트워크 격리 및 연동

---

### 🔗 Related Account & Contact
- **Backend & Archive Account**: [@some1mine](https://github.com/some1mine) (백엔드 실무 프로젝트, Java/Spring 및 CS 학습 저장소)
- **Email**: parkjw573@naver.com
