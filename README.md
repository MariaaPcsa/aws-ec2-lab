📖 Sobre o Projeto

Este repositório foi desenvolvido como parte do desafio prático da DIO (Digital Innovation One) com foco em gerenciamento de instâncias Amazon EC2 na AWS.

O laboratório permitiu aplicar conceitos fundamentais de computação em nuvem, segurança, monitoramento e gerenciamento de infraestrutura utilizando serviços da AWS.

🎯 Objetivos

✅ Criar instâncias EC2

✅ Configurar Security Groups

✅ Utilizar armazenamento EBS

✅ Monitorar recursos com CloudWatch

✅ Gerenciar ciclo de vida das instâncias

✅ Documentar a experiência utilizando GitHub

🏗️ Arquitetura Utilizada
flowchart LR

    User[👩‍💻 Usuário]

    SG[🔒 Security Group]

    EC2[🖥️ Amazon EC2]

    EBS[(💾 Amazon EBS)]

    CW[📊 CloudWatch]

    User --> SG
    SG --> EC2
    EC2 --> EBS
    EC2 --> CW
☁️ Serviços AWS Utilizados
Serviço	Finalidade
Amazon EC2	Criação da máquina virtual
Amazon EBS	Armazenamento persistente
IAM	Controle de acesso
CloudWatch	Monitoramento
Security Groups	Firewall virtual
EC2 Instance Connect	Conexão com a instância
🚀 Etapas Executadas
1️⃣ Criação da Instância

Configurações utilizadas:

Nome: Minha-Primeira-EC2
Tipo: t2.micro
Sistema Operacional: Amazon Linux 2023
Região: us-west-2
Volume: EBS padrão
2️⃣ Configuração de Segurança

Portas liberadas:

Porta	Protocolo	Finalidade
22	SSH	Acesso remoto
80	HTTP	Aplicações Web
443	HTTPS	Aplicações seguras
3️⃣ Conexão com a Instância

Exemplo:

ssh -i chave.pem ec2-user@IP_PUBLICO
4️⃣ Monitoramento

Monitoramento realizado através do Amazon CloudWatch:

CPU Utilization
Network In
Network Out
Status Checks
EBS Metrics
5️⃣ Gerenciamento do Ciclo de Vida

Estados observados:

Pending
 ↓
Running
 ↓
Stopping
 ↓
Stopped
 ↓
Terminated
📚 Conceitos Aprendidos
Amazon EC2

Serviço responsável pela criação de servidores virtuais sob demanda.

Security Group

Firewall virtual que controla o tráfego de entrada e saída.

Amazon EBS

Serviço de armazenamento persistente para instâncias EC2.

CloudWatch

Ferramenta de monitoramento e observabilidade da AWS.

IAM

Serviço utilizado para controle de identidade e permissões.

📷 Evidências

Estrutura sugerida:

images/
├── ec2-dashboard.png
├── ec2-running.png
├── security-group.png
├── cloudwatch-metrics.png
└── instance-connect.png
Exemplos










💡 Insights Obtidos

🔹 A EC2 permite escalar infraestrutura rapidamente.

🔹 Security Groups são essenciais para proteção dos recursos.

🔹 O monitoramento contínuo ajuda a prevenir falhas.

🔹 O gerenciamento correto dos recursos evita custos desnecessários.

🔹 O CloudWatch fornece métricas importantes para tomada de decisão.

🛠️ Tecnologias Utilizadas
Amazon EC2
Amazon EBS
AWS IAM
Amazon CloudWatch
Git
GitHub
Markdown
📈 Próximos Passos

Implementar Auto Scaling

Configurar Load Balancer

Utilizar Elastic IP

Integrar com S3

Automatizar implantação com AWS CLI

🔗 Referências
AWS Documentation
AWS Academy
DIO Bootcamp AWS
GitHub Docs
👩‍💻 Autora

Maria Correia

🎓 Estudante de Tecnologia da Informação - UNIVESP

☁️ AWS Cloud Practitioner (em formação)

💻 Java | Spring Boot | Banco de Dados | AWS

🔗 LinkedIn: SEU_LINKEDIN

🔗 GitHub: SEU_GITHUB
