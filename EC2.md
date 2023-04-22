# Tudo sobre EC2:

## O que é o EC2:
  O Amazon Elastic Compute Cloud (Amazon EC2) oferece uma capacidade de computação escalável na Nuvem da Amazon Web Services (AWS). O uso do Amazon EC2 elimina a necessidade de investir em hardware inicialmente, portanto, você pode desenvolver e implantar aplicativos com mais rapidez. É possível usar o Amazon EC2 para executar quantos servidores virtuais forem necessários, configurar a segurança e as redes e gerenciar o armazenamento. O Amazon EC2 permite aumentar ou reduzir a escala para lidar com alterações nos requisitos ou com picos em popularidade, reduzindo sua necessidade de prever o tráfego.
  
## Recursos do Amazon EC2:
O Amazon EC2 fornece os seguintes recursos:

* Ambientes de computação virtual, conhecidos como instâncias*

* Os modelos pré-configurados para suas instâncias, conhecidos como Imagens de máquina da Amazon (AMIs), que empacotam os bits de que você precisa para seu servidor (incluindo o sistema operacional e software adicional)

* Várias configurações de capacidade de CPU, memória, armazenamento e redes para suas instâncias, conhecidas como tipos de instância

* Informações seguras de login para suas instâncias usando pares de chave (a AWS armazena a chave pública e você armazena a chave privada em um lugar seguro)

* Volumes de armazenamento para dados temporários que são excluídos quando você interrompe, hiberna ou encerra sua instância, conhecidos como volumes de armazenamento de instâncias

* Volumes de armazenamento persistentes para seus dados usando o Amazon Elastic Block Store (Amazon EBS), conhecidos como volumes do Amazon EBS

* Vários locais físicos para seus recursos, como instâncias e volumes do Amazon EBS, conhecidos como regiões e zonas de disponibilidade

* Um firewall que permite especificar os protocolos, portas e intervalos de IPs de origem que podem acessar suas instâncias usando grupos de segurança

* Os endereços IPv4 estáticos para computação em nuvem dinâmica, conhecidos como endereços IP elásticos

* Metadados, conhecidos como tags, que você pode criar e atribuir aos recursos do Amazon EC2

* Redes virtuais isoladas logicamente do restante da Nuvem AWS que você pode criar e, opcionalmente, conectar à sua própria rede, conhecida como nuvens virtuais privadas (VPCs)

## Acessar o Amazon EC2:
  O Amazon EC2 fornece uma interface de usuário na web, o console do Amazon EC2. Depois de cadastrar-se em uma conta da AWS, você pode acessar o console do Amazon EC2 fazendo login no AWS Management Console e selecionando EC2 na página inicial do console.

Se preferir usar uma interface de linha de comando, temos as seguintes opções:

AWSInterface da linha de comando (CLI) da
  Fornece comandos para um conjunto amplo de produtos da AWS e é compatível com Windows, Mac e Linux. Para começar a usar, consulte oAWS Command Line Interface User Guide (Guia do usuário da AWS Command Line Interface). Para obter mais informações sobre comandos para o Amazon EC2, consulte ec2 na Referência de comandos da AWS CLI).

AWS Tools for Windows PowerShell
  Fornece comandos para um conjunto amplo de produtos da AWS para os usuários que usam script no ambiente do PowerShell. Para começar a usar, consulte o Guia do usuário do AWS Tools for Windows PowerShell. Para obter mais informações sobre os cmdlets do Amazon EC2, consulte a Referência de cmdlets do AWS Tools for PowerShell.

  O Amazon EC2 permite a criação de recursos usando o AWS CloudFormation. Você cria um modelo, em JSON ou YAML, que descreve seus recursos da AWS e o AWS CloudFormation provisiona e configura esses recursos para você. Você pode reutilizar seus modelos do CloudFormation para provisionar os mesmos recursos várias vezes, seja na mesma região e conta ou em várias regiões e contas. Para obter mais informações sobre os tipos de recurso e as propriedades do Amazon EC2, consulte Referência de tipo de recurso do EC2 no Guia do usuário do AWS CloudFormation.

  A Amazon EC2 fornece uma API de consulta. Essas são solicitações HTTP ou HTTPS que usam verbos HTTP GET ou POST e um parâmetro de consulta chamado Action. Para obter mais informações sobre as ações de API para o Amazon EC2, consulte Ações no Amazon EC2 API Reference.

  Se você preferir criar aplicativos usando APIs específicas de uma linguagem em vez de enviar uma solicitação via HTTP ou HTTPS, a AWS fornece bibliotecas, código de exemplo, tutoriais e outros recursos para desenvolvedores de software. Essas bibliotecas fornecem funções básicas que automatizam tarefas, como assinatura criptografada de suas solicitações, novas tentativas de solicitações e tratamento das respostas de erro, facilitando para que você comece rapidamente.
