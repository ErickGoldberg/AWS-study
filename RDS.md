# Tudo sobre Amazon RDS:

## O que é RDS:
O Amazon Relational Database Service (Amazon RDS) é um serviço da Web que facilita a configuração, a operação e escalabilidade de um banco de dados relacional na Nuvem AWS. Ele fornece capacidade econômica e redimensionável para um banco de dados relacional padrão do setor e gerencia tarefas comuns de administração de banco de dados.

## Banco de dados on-premises:
O Amazon Elastic Compute Cloud (Amazon EC2) oferece uma capacidade de computação escalável na Nuvem AWS. O Amazon EC2 dispensa a necessidade de investir em hardware inicialmente e, portanto, você pode desenvolver e implantar aplicações com mais rapidez.

Quando você compra um servidor on-premises, recebe CPU, memória, armazenamento e IOPS, todos no mesmo pacote. Com o Amazon EC2, estes elementos se separaram, para que você possa escalá-los independentemente. Se você precisar de mais CPU, menos IOPS ou mais capacidade de armazenamento, poderá alocá-los facilmente.

Para um banco de dados relacional em um servidor on-premises, você assume total responsabilidade pelo servidor, sistema operacional e software. Para um banco de dados em uma instância do Amazon EC2, a AWS gerencia as camadas abaixo do sistema operacional. Dessa maneira, o Amazon EC2 elimina parte do peso de gerenciar um servidor de banco de dados on-premises.

Na tabela a seguir, é possível encontrar uma comparação dos modelos de gerenciamento para bancos de dados on-premises e o Amazon EC2.

## Vantagens da amazon RDS:
- Você pode usar os produtos de banco de dados que já conhece com: MariaDB, Microsoft SQL Server, MySQL, Oracle e PostgreSQL.

- O Amazon RDS gerencia backups, patches de software, detecção automática de falhas e recuperação.

- Você pode ativar backups automatizados ou pode criar manualmente seus próprios snapshots de backup. Você pode usar esses backups para restaurar um banco de dados. O processo de restauração do Amazon RDS funciona de maneira confiável e eficiente.

- Você pode obter alta disponibilidade com uma instância primária e uma instância secundária síncrona que pode ser usada para failover em caso de problemas. Também é possível usar réplicas de leitura para aumentar a escalabilidade de leitura.

- Além da segurança em seu pacote de banco de dados, você pode ajudar a controlar quem pode acessar seus bancos de dados do RDS. Para fazer isso, você pode usar o AWS Identity and Access Management (IAM) para definir usuários e permissões. Você também pode ajudar a proteger seus bancos de dados colocando-os em uma nuvem privada virtual (VPC).

## Instâncias de banco de dados:
Uma instância de banco de dados é um ambiente isolado de banco de dados na Nuvem AWS. O bloco de construção básico do Amazon RDS é a instância do banco de dados.

Sua instância de banco de dados pode conter um ou mais bancos de dados criados pelo usuário. É possível acessar a instância de banco de dados usando as mesmas ferramentas e os mesmos aplicativos usados com uma instância de banco de dados independente. Crie e modifique uma instância de banco de dados usando a AWS Command Line Interface (AWS CLI), a API do Amazon RDS ou o AWS Management Console.

##Classes da instância de banco de dados:
A classe de instância de banco de dados determina a capacidade de computação e de memória de uma instância de banco de dados. Uma classe de instância de banco de dados consiste no tipo e no tamanho de instância de banco de dados. Cada tipo de instância oferece diferentes capacidades de computação, memória e armazenamento. Por exemplo, db.m6g é uma classe de instância de banco de dados de uso geral com a tecnologia de processadores Graviton2 da AWS. No tipo de instância db.m6g, db.m6g.2xlarge é uma classe de instância de banco de dados.

## Mecanismos de banco de dados:
Um mecanismo de banco de dados é o software de banco de dados relacional específico que é executado na sua instância de banco de dados. Atualmente, o Amazon RDS oferece suporte aos seguintes mecanismos:

- MariaDB
- Microsoft SQL Server
- MySQL
- Oracle
- PostgreSQL

Cada mecanismo de banco de dados tem seus próprios recursos compatíveis, e cada versão de um mecanismo de banco de dados pode incluir recursos específicos. O suporte para recursos do Amazon RDS varia entre Regiões da AWS e versões específicas de cada mecanismo de banco de dados. Além disso, cada mecanismo de banco de dados tem um conjunto de parâmetros em um grupo de parâmetros de banco de dados que controlam o comportamento dos bancos de dados que ele gerencia.

Links úteis: https://aws.amazon.com/pt/rds/  &&  https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.html
