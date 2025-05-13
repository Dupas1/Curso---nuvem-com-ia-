# Curso---nuvem-com-ia-
READ.me  contendo resumos, anotações e dicas sobre o uso da Azure passado pelo curso da DIO

## O que é Cloud
Modelo de entrega de serviços de tecnologia (armazenamento, processamento, software, redes) pela internet, sob demanda e com pagamento pelo uso. Elimina a necessidade de infraestrutura física própria, oferecendo escala, flexibilidade, agilidade e acesso remoto. Tipos principais: pública, privada e híbrida.

## Infraestrutura
Conjunto de recursos físicos ou virtuais (servidores, redes, armazenamento) essenciais para sistemas de TI. Modelos principais:

### **On-Premise (Local):** Infraestrutura de TI instalada, gerenciada e mantida localmente nas instalações da empresa, com controle total sobre hardware e software.
* Vantagens: Controle total, personalização.
* Desvantagens: Maior custo de manutenção, necessidade de equipe especializada.
  - Exemplos: Servidores físicos e armazenamento local, rede interna com controle total, administração e manutenção interna.
  
### **Cloud (Nuvem):** Infraestrutura baseada em servidores remotos de provedores (AWS, Azure, GCP), com recursos escaláveis e pagamento por uso.
* Vantagens: Escalabilidade, flexibilidade, redução de custos operacionais.
* Desvantagens: Dependência de fornecedores, questões de segurança em dados sensíveis.
  - Exemplos: AWS, Azure, GCP, armazenamento e processamento de dados na nuvem.

### **Hybrid (Híbrido):** Combinação de recursos on-premise e em nuvem, permitindo flexibilidade e equilíbrio entre controle e escalabilidade.
* Vantagens: Flexibilidade, equilíbrio entre controle e escalabilidade.
* Desvantagens: Complexidade na gestão, integração entre ambientes locais e nuvem.
  - Exemplos: Serviços críticos locais e carga de trabalho escalável na nuvem, conexões seguras entre servidores locais e provedores de nuvem.

## Modelos de Serviço em Nuvem:
Definem o nível de controle da empresa sobre a infraestrutura e os serviços do provedor, auxiliando na escolha da solução mais adequada com base em controle, custo e escalabilidade.

### **Golden Rules**: Regras universais para escolher e implementar modelos de serviço.
  * Exemplo: "Escolha o modelo de serviço adequado conforme o nível de controle necessário."

### **House Rules:** Regras específicas para cada organização, baseadas em sua arquitetura e objetivos.
  *Exemplo: "Para aplicativos mais complexos, prefira PaaS para abstração e gerenciamento facilitado."
  
Tipos de Modelos de Serviço em Nuvem:

### **IaaS (Infrastructure as a Service):** Oferece infraestrutura de TI básica (servidores virtuais, armazenamento, redes) com cobrança por uso. Requer gestão de servidores e configurações.
* Vantagens: Controle total, escalabilidade e flexibilidade.
* Desvantagens: Requer gestão de servidores, maior responsabilidade.
  * Exemplos: Amazon EC2, Google Compute Engine, Microsoft Azure VMs, Amazon S3, Google Cloud Storage.
    
### **PaaS (Platform as a Service):** Oferece plataforma completa para desenvolvimento, teste e implementação de aplicativos, abstraindo a infraestrutura.
* Vantagens: Simplificação no desenvolvimento, abstração da infraestrutura, foco no aplicativo.
* Desvantagens: Menos controle sobre a infraestrutura, limitações na personalização.
  * Exemplos: Google App Engine, Microsoft Azure App Services, AWS Elastic Beanstalk, Amazon RDS, Google Cloud SQL.

### **SaaS (Software as a Service):** Entrega software e aplicações completas acessíveis via internet, sem necessidade de instalação ou manutenção local.
* Vantagens: Fácil implementação, sem gestão de infraestrutura, pagamento por uso.
* Desvantagens: Dependência de internet, menor controle sobre software e dados.
  * Exemplos: Google Workspace, Microsoft Office 365, Salesforce, Slack, Zoom.
    
### **BaaS (Backend as a Service):** Fornece soluções de backend prontas para aplicativos móveis e web (bancos de dados, autenticação, notificações).
* Vantagens: Rapidez no desenvolvimento, gerenciamento simplificado de backend.
* Desvantagens: Dependência do provedor, limitações na personalização.
  * Exemplos: Firebase, AWS Amplify, Backendless.
    
### **FaaS (Function as a Service):** Executa funções de código específicas sem gerenciar servidores ("serverless"), com cobrança por execução.
* Vantagens: Escalabilidade automática, pagamento por execução, menos gerenciamento de infraestrutura.
* Desvantagens: Limitações em tempo de execução e complexidade em funções pequenas.
  * Exemplos: AWS Lambda, Azure Functions, Google Cloud Functions.
    
### **DBaaS (Database as a Service):** Oferece bancos de dados gerenciados na nuvem, sem preocupações com a infraestrutura subjacente.
* Vantagens: Facilidade de escalabilidade, gerenciamento simplificado de backups e atualizações.
* Desvantagens: Menor controle sobre a configuração do banco de dados e personalização.
  * Exemplos: Amazon RDS, Azure SQL Database, Google Cloud SQL.
## Resumo dos Pilares da Nuvem:
* Escalabilidade: Aumentar/diminuir recursos de TI rapidamente conforme a demanda.
* Elasticidade: Escalabilidade automática e em tempo real em resposta à carga de trabalho.
* Governança: Políticas, processos e controles para uso eficiente, seguro e em conformidade da nuvem.
* Gerenciabilidade: Facilidade de administrar, monitorar e manter recursos e serviços de nuvem.
* Confiabilidade: Operação consistente e sem falhas, com alta disponibilidade e recuperação de desastres.
* Previsibilidade: Capacidade de estimar e controlar custos dos serviços de nuvem.
* Segurança: Medidas para proteger dados, aplicativos e infraestrutura contra ameaças.

## SLA (Service Level Agreement): Resumo

Em essência, um SLA é um contrato ou acordo entre um provedor de serviços (que pode ser um fornecedor externo ou até mesmo um departamento interno de uma empresa) e seus clientes ou usuários. Ele define claramente o nível de serviço que o cliente pode esperar, estabelecendo métricas específicas de desempenho e as responsabilidades de ambas as partes.

Uptime (%)	Downtime Anual Aproximado
99.0%	3 dias, 15 horas e 36 minutos
99.5%	1 dia, 19 horas e 49 minutos
99.9%	8 horas e 46 minutos
99.95%	4 horas e 23 minutos
99.99%	52 minutos e 36 segundos
99.999%	5 minutos e 15 segundos

Quanto mais "9" na disponibilidade (ex: 99.99% vs 99.9%), maior a garantia de serviço e, geralmente, mais caro o custo.

Em resumo, o SLA é um documento fundamental para estabelecer uma relação clara e confiável entre um provedor de serviços e seus clientes, definindo as expectativas e garantindo um certo nível de qualidade na entrega dos serviços.

