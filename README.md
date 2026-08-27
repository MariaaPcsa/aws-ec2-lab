☁️ AWS EC2 Lab - Gerenciamento de Instâncias Amazon EC2
AWS Nuvem DIO GitHub Status

📖 Descrição
Este repositório foi desenvolvido como parte do desafio prático da DIO (Digital Innovation One) com foco no gerenciamento de instâncias Amazon EC2 na AWS.

O laboratório ajudou na criação, configuração, monitoramento e gerenciamento de uma instância EC2, além da utilização de recursos como Security Groups, EBS e CloudWatch.

🎯 Objetivos de Aprendizagem
Aplicar conceitos de computação em nuvem.
Criar e gerenciar instâncias EC2.
Configure regras de acesso utilizando grupos de segurança.
Uso de armazenamento persistente com Amazon EBS.
Monitore recursos por meio do Amazon CloudWatch.
Documentar processos técnicos utilizando GitHub.
🏗️ Arquitetura do Laboratório

☁️ Serviços AWS Utilizados
se	Descrição
Amazon EC2	máquina virtual na
Amazon EBS	†A
AWS IAM	Gerenciamento de usuários e permissões
CloudWatch	Monitoramento e metodologia
Grupos de segurança	Controle de acesso à instância
🚀 Etapas Realizadas
1️⃣ Criação da Instância EC2
Configurações utilizadas:

Nome da instância: AWS-EC2-LAB
Sistema Operacional: Amazon Linux
Tipo da Instância: t2.micro
Região: us-west-2
Volume EBS
2️⃣ Criação do Par de Chaves
Configuração utilizada:

Tipo: RSA
Formato: .pem
O par de chaves permite acesso seguro à instância via SSH.

3️⃣ Configuração do Grupo de Segurança
Portas preparam:

Porta	Protocolo	‐
22	SSH	Acesso remoto
80	HTTP	Aplicações Web
443	HTTPS	Aplicações Seguras
4️⃣ Inicialização da Instância
Durante a seguinte criação da instância foram executadas as etapas:

✅ Inicializando interferências

✅ Criando grupos de segurança

✅ Criando regras do grupo de segurança

✅ Iniciando

5️⃣ Monitoramento
Foi realizado acompanhamento através do Amazon CloudWatch:

Utilização da CPU
Rede em
Saída de rede
Verificações de status
6️⃣ Gerenciamento da Instância
Operações executadas:

Começar
Parar
Reinício
Monitoramento
Encerramento
📷 Evidências
As capturas de tela utilizadas neste laboratório estão armazenadas na pasta:

images/
├── cloudwatch-metrics.png
├── EBS.PNG
├── ec2-running.png
├── instaciaInterropida.PNG
└── instance-connect.png
📁 Estrutura do Repositório
aws-ec2-lab/
│
├── README.md
│
└── images/
    ├── cloudwatch-metrics.png
    ├── EBS.PNG
    ├── ec2-running.png
    ├── instaciaInterropida.PNG
    └── instance-connect.png
📚 Conceitos Aprendidos
Amazon EC2
Serviço responsável pela criação de servidores virtuais sob demanda.

Amazon EBS
Serviço de armazenamento persistente associado às instâncias EC2.

Grupos de segurança
Firewall virtual utilizado para controlar o tráfego de entrada e saída.

Amazon CloudWatch
Serviço de monitoramento e observabilidade da AWS.

EU SOU
Serviço utilizado para gerenciamento de usuários, grupos e permissões.

💡 Insights Obtidos
A EC2 oferece flexibilidade para criação de ambientes sob demanda.
Grupos de Segurança são fundamentais para a segurança da infraestrutura.
O CloudWatch permite monitoramento detalhado dos recursos.
O armazenamento EBS garante persistência dos dados.
A documentação facilita futuras implementações e consultas.
🛠️ Tecnologias Utilizadas
Amazon EC2
Amazon EBS
AWS IAM
Amazon CloudWatch
Git
GitHub
Markdown
📈 Próximos Passos
IP Elástico
Dimensionamento automático do Utilizar
Integrar com Amazon S3
Automatizar tarefas com AWS CLI
Balanceadores de carga Explorar
👩‍💻 Autora
Maria Correia

🎓 Estudante de Tecnologia da Informação - UNIVESP

☁️ AWS Cloud Practitioner (em formação)

💻Java | Bota Primavera | Banco de Dados | AWS

🔗 GitHub: https://github.com/MariaaPcsa

📜 Licença
Projeto desenvolvido para fins educacionais durante o Bootcamp AWS da DIO.
