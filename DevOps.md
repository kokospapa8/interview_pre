MMT Infra question - https://docs.google.com/document/d/1H5rPVrPzNZ7e0dG_jsMGGUV140NN2CO4CfhlHyx7OQ0/edit

# CI/CD
- 시스템 모니터링을 위한 구성이 필요할 경우에 어떤식으로 구성해본 경험이 있는지?
- Explain deployment patterns
- build numbering 어떤 컨벤션으로해야하나?

# Docker
- ECS 또는 Docker Swarm 또는 Kubernetes 같은 Orchestration tool을 구축해본 경험은? 있다면 각가의 장단점은?
- Docker Orchestration tool(Swarm, Kubernetes)등을 이용해 MSA서비스를 제공해야 한다면 어떻게 구성하는게 좋을지?
- Docker Monitoring 및 Alarm 서비스 구성을 해본 경험이 있는지? 있다면 어떤 서비스를 이용해 구성했는지?
- Docker Repository


# AWS
- VPC를 직접 구성해본 경험이 있는지? 있다면 어떤식으로 구성했는지? Subnet, Network ACL, VCP CIDR Block, Bastion Host 등등
- AWS VPC Best architecture는?
- IAM을 이용한 사용자 등록 및 권한 관리를 해본 경험이 있는지? 만약 여러명(예를 들면 50명 이상)의 사용자를 등록하고 권한을 관리해야 할경우에 어떤식으로 구성하는게 좋을지?
- Cloudformation을 이용한 서비스 구성을 해본 경험이 있는지? 있다면 여러 Tier의 서비스(예를 들면 Application, Cache, DB)등을 구성할때 어떤식으로 생성하고 배포했는지?
- ALB를 사용해서 Path param을 이용한 Routing 경험이 있는지? 있다면 ALB를 어떤식으로 구성했는지와 ELB 또는 API Gateway를 이용했을때의 차이점은?
- Autoscaling을 생성해서 EC2를 관리해 본 경험이 있는지? 있다면 Auto scaling policy는 어떤식으로 구성했고 트래픽이 몰렸을 경우 어떤 이벤트(Cloud watch cpu, mem or other monitor)를 이용해서 처리했는지?
- Aurora RDS 와 Elastic cache를 사용해본 경험이 있는지?
- 용량 산정 및 서비스에 따른 instance type 결정이 필요하다면 어떤 방식으로 진행하는게 좋다고 생각하는지?
- 여러 VPC간의 VPC Peering을 이용해서 서비스를 제공해본 경험은?
- DR구성을 해야 한다면 가장 좋은 Architecture는?
- Multi region을 이용해 서비스를 제공해야 할경우에 권장할 만한 구성은?
