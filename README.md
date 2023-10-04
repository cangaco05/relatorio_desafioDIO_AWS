# relatorio_desafioDIO_AWS
Relatorio do desafio empresa farmacêutica, onde propusemos melhorias migrando ambiente para nuvem utilizando AWS

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: [03/10/2023]
Empresa: Abstergo Industries 
Responsável: Amaury Prates

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Amaury Prates. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 (Elastic Compute Cloud) 
- O foco principal da ferramenta EC2 é fornecer instâncias de máquinas virtuais escaláveis e flexíveis na nuvem
- Amazon EC2 é uma escolha comum para muitas organizações que desejam aproveitar a flexibilidade e escalabilidade da computação em nuvem para suas necessidades de TI
  
1.Planejamento e Requisitos: Comece definindo claramente os requisitos do sistema, como o tamanho do banco de dados, os recursos de CPU e memória necessários, os sistemas operacionais e quaisquer outros componentes de software necessários.
2.Indico uma Instâncias EC2: Com base nos requisitos definidos, indicaremos os tipos de instâncias EC2 apropriados para executar o aplicativo e banco de dados da empresa analisada.
3.Instalação e Configuração do Banco de Dados: Configuraremos o banco de dados na instância EC2.
4.Segurança: Será configurado grupos de segurança e ACLs de rede para restringir o acesso à instância EC2 e ao banco de dados. Considerando a criptografia de dados em repouso e em trânsito para proteger informações confidenciais.

EC2 é amplamente utilizado para executar uma variedade de aplicativos, desde sites simples até aplicativos corporativos altamente escaláveis. Ele fornece os recursos de computação necessários para executar cargas de trabalho na nuvem de maneira eficiente e econômica.

Etapa 2: 
- Amazon RDS (Relational Database Service)
- Amazon RDS oferece uma camada de gerenciamento de banco de dados que simplifica muitas tarefas de administração, permitindo que você se concentre mais no desenvolvimento de aplicativos e menos na manutenção do banco de dados. Isso pode economizar tempo e recursos para sua empresa farmacêutica.
- RDS é uma escolha sólida para empresas farmacêuticas que desejam hospedar e gerenciar bancos de dados relacionais de maneira escalável e eficiente na infraestrutura da AWS.
  
1.Planejamento e Requisitos: Comece definindo claramente os requisitos do banco de dados, como o tamanho, a capacidade de armazenamento, a escalabilidade e os requisitos de desempenho. Considere também os aspectos de segurança e conformidade, que são especialmente importantes no setor farmacêutico.
2.Escolha do Banco de Dados: Selecionar o  banco de dados que atende às necessidades do aplicativo. O Amazon RDS suporta uma variedade de banco de dados, como MySQL, PostgreSQL, SQL Server, Oracle, MariaDB e Amazon Aurora.
3.Criação da Instância do RDS: No Console da AWS, crie uma instância do Amazon RDS com as configurações necessárias. Isso inclui especificar o tipo de instância, o tamanho do armazenamento, a senha do administrador e outras configurações relevantes.
4.Configuração de Segurança: Configurar grupos de segurança do Amazon RDS para controlar quem pode acessar o banco de dados. Certificando que apenas as instâncias EC2 ou outros serviços autorizados tenham acesso.
5.Backup e Recuperação: Utilize as opções de backup automático e snapshots do Amazon RDS para proteger os dados. Defina uma política de retenção de backup adequada.
6.Conformidade e Segurança: Certifique-se de que o banco de dados está em conformidade com os regulamentos e requisitos da indústria farmacêutica, como a ANVISA ou outros órgãos reguladores. Implemente a criptografia de dados em repouso e em trânsito, se necessário.
7.Manutenção e Patching: O Amazon RDS gerencia automaticamente a manutenção do sistema operacional e do banco de dados. No entanto, você ainda pode aplicar patches e atualizações do banco de dados de acordo com a necessidade da sua aplicação.
8.Replicação e Failover: Considere configurar replicação para alta disponibilidade e failover. O Amazon RDS suporta replicação multiAZ (disponibilidade em zonas de disponibilidade) para maior resiliência.
9.Backup Externo e Arquivamento de Dados: Se você precisar manter dados por um longo período para fins regulatórios ou de conformidade, planeje estratégias de backup externo e arquivamento de dados.

Etapa 3: 
- Amazon VPC (Amazon Virtual Private Cloud)
- Permite que você crie uma rede virtual isolada e personalizada na nuvem. A utilização do Amazon VPC para uma empresa farmacêutica pode ser uma maneira eficaz de garantir a segurança, conformidade e controle da infraestrutura de rede na nuvem.
- Amazon VPC é um serviço da Amazon Web Services (AWS) 

1.Planejamento: Defina objetivos e requisitos para a rede virtual.
2.Criação da VPC: Crie uma VPC personalizada no console AWS.
3.Segurança e Isolamento: Configure grupos de segurança e listas de controle de acesso para controlar o tráfego.
4.Gateway da Internet: Configure um Gateway da Internet para acesso à Internet, se necessário.
5.Implantação de Serviços: Coloque instâncias EC2, bancos de dados RDS e outros recursos na VPC.
6.Monitoramento: Use o Amazon CloudWatch para monitorar o desempenho e configure registros de tráfego e segurança.
7.Conformidade: Certifique-se de que a configuração da VPC atenda aos regulamentos da indústria farmacêutica.
8.Treinamento e Documentação: Treine a equipe e documente procedimentos e políticas de segurança.
9.Testes e Monitoramento Contínuo: Realize testes regulares e monitore a VPC constantemente para garantir a segurança e a conformidade.


O Amazon VPC ajuda a criar uma rede segura e personalizada na nuvem para atender às necessidades da empresa farmacêutica.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado, pode proporcionar maior flexibilidade, segurança, conformidade, economia de custos e eficiência operacional para uma empresa farmacêutica, ao mesmo tempo em que impulsiona a inovação e melhora a capacidade de resposta às necessidades do setor. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Responsavel pelo projeto:

Amaury Prates
