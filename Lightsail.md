#  **Tudo sobre Lighsail:**

## O que é o Lightsail:
  O Amazon Lightsail é um provedor de servidor privado virtual (VPS). O Lightsail oferece aos desenvolvedores funcionalidades e capacidade de computação, armazenamento e redes para implantar e gerenciar sites e aplicações Web na nuvem. O Lightsail inclui tudo de que você precisa para iniciar rapidamente o seu projeto – máquinas virtuais, contêineres, bancos de dados, CDN, balanceadores de carga, gerenciamento de DNS etc. Tudo isso por um preço mensal baixo e previsível.


## Sobre VPS:
  Um servidor privado virtual, também chamado de “instância”, permite que os usuários executem sites e aplicações Web em um ambiente altamente seguro e disponível, que se mantém econômico. Há muitos benefícios para o uso de um servidor privado virtual, incluindo preços acessíveis, escalabilidade, segurança e recursos personalizáveis.


## O que posso fazer no Lightsail:
  Você pode escolher entre diversos planos de VPS pré-configurados que incluem tudo que você precisa para implantar e gerenciar facilmente a sua aplicação. O Lightsail é mais adequado a projetos que exigem alguns servidores privados virtuais e para usuários que preferem uma interface de gerenciamento simples. Entre os casos de uso comuns do Lightsail, estão execução de sites, aplicações Web, blogs, sites de comércio eletrônico, software simples e muito mais.
  
  
##  Quais softwares posso executar no Lightsail:
  O Lightsail oferece diversos modelos de sistemas operacionais e aplicativos, instalados automaticamente na criação de uma nova instância do Lightsail. Os modelos de aplicativos incluem WordPress, Drupal, Joomla!, Ghost, Magento, Redmine, LAMP, Nginx (LEMP), MEAN, Node.js, Django, entre outros. Você pode instalar software adicional nas instâncias usando o SSH do navegador ou o seu próprio cliente SSH.
  
  
##  Recursos do Lightsail:
- Como as instâncias do Lightsail são executadas?

  A AWS projetou as instâncias do Lightsail especificamente para servidores web, ambientes de desenvolvimento e casos de uso de banco de dados de pequeno porte. Essas  cargas de trabalho não usam toda a CPU de forma frequente ou uniforme, mas precisam ocasionalmente de um pico de desempenho. O Lightsail usa instâncias de desempenho intermitente que oferecem um nível básico de desempenho de CPU com capacidade de intermitência acima da linha de base. Este design permite que você tenha o desempenho de que precisa, quando precisa, e a proteção da variação de desempenho ou outros efeitos colaterais comuns que geralmente podem ocorrer quando há excesso de assinaturas em outros ambientes. Veja aqui mais informações sobre performance intermitente.

Se você precisa de ambientes e instâncias altamente configuráveis, com alto desempenho uniforme de CPU para aplicativos como codificação de vídeo ou HPC, é recomendado o Amazon EC2.

- Como faço para estabelecer uma conexão a uma instância do Lightsail?

  O Lightsail oferece conexão segura ao terminal de uma instância diretamente do navegador com apenas um clique. Além disso, oferece suporte ao acesso via SSH para instâncias baseadas em Linux/Unix e ao acesso via RDP para instâncias baseadas em Windows. Para usar conexões de 1 clique, inicie suas telas de gerenciamento de instâncias, clique em Conectar usando SSH ou Conectar-se usando RDP, e uma nova janela do navegador será aberta, conectando-se automaticamente à sua instância.

Se você preferir usar seu próprio cliente para estabelecer uma conexão à instância baseada em Linux/Unix, o Lightsail fará o trabalho de gerenciamento e armazenamento da chave de SSH para você, fornecendo uma chave segura para ser usada no cliente SSH.

- Como uso IPs no Lightsail?

  Cada instância do Lightsail obtém automaticamente um endereço IP privado e um endereço IP público. Você pode usar o IP privado para transmitir dados entre instâncias Lightsail e recursos da AWS de forma privada e gratuita. Você pode usar o IP público para estabelecer conexão com sua instância pela Internet, como por meio de um nome de domínio registrado ou por meio de uma conexão SSH ou RDP de seu computador local. Também é possível associar um IP estático à instância, que substitui o IP público por um endereço IP que não mudará mesmo que a instância seja interrompida e iniciada.
  
- O que é um IP estático?

  Um IP estático é um IP público fixo e dedicado à sua conta do Lightsail. Você pode atribuir um IP estático a uma instância, substituindo seu IP público. Se você decidir substituir a instância por outra, poderá reatribuir o IP estático para a nova instância. Dessa forma, não será necessário reconfigurar nenhum sistema externo (como registro de DNS) para apontar para um novo IP sempre que a instância for substituída.
  
- O que são registros de DNS?

  O DNS é um serviço distribuído globalmente que converte nomes legíveis por humanos, como www.exemplo.com, em endereços IP numéricos, como 192.0.2.1, usados pelos computadores para conexões entre si. Com o Lightsail, você pode mapear facilmente nomes de domínio registrados, como fotos.exemplo.com, para os IPs públicos de instâncias Lightsail. Assim, quando os usuários digitarem em um navegador nomes legíveis por humanos, como exemplo.com, o Lightsail converterá automaticamente o endereço no IP da instância para a qual você quer direcionar os usuários. Cada uma dessas conversões é denominada como consulta de DNS.

É importante saber que, para usar um domínio no Lightsail, é preciso antes registrá-lo. Você pode registrar novos domínios usando recursos de suporte a domínio no Lightsail , Amazon Route 53 ou o registro de DNS de sua preferência.

- Posso gerenciar as configurações de firewall para minha instância?

Sim. É possível controlar o tráfego de dados para as instâncias usando o firewall do Lightsail. No console do Lightsail, você pode definir regras sobre as portas da sua instância que podem ser acessadas publicamente para diferentes tipos de tráfego.

- O que são snapshots?

  Snapshots são formas de backup point-in-time de instâncias, bancos de dados ou discos de armazenamento de blocos. Você pode criar um snapshot de um de seus recursos a qualquer momento ou habilitar snapshots automáticos em instâncias de discos, de forma que um Lighsail crie snapshots para você. Você pode usar os snapshots como linhas de base para criar novos recursos ou para fazer backup de seus dados. Um snapshot reúne todos os dados necessários para restaurar o seu recurso (desde o momento em que é acionado). Ao restaurar um recurso a partir de um snapshot, o novo recurso inicia uma réplica exata do recurso original que foi usado para criar o snapshot.

Você pode tirar snapshots de suas instâncias, discos e bancos de dados do Lightsail manualmente, ou você pode usar snapshots automáticos para instruir o Lightsail a tirar snapshots de suas instâncias e discos todos os dias automaticamente. Para obter mais informações, consulte os Snapshots no Amazon Lightsail.

- O que são os snapshots automáticos?

  Eles constituem uma forma de programar snapshots diários em suas instâncias do Linux/Unix no Amazon Lightsail. Você pode escolher uma hora do dia e o Lighsail irá automaticamente tirar snapshots para você todos os dias no momento que você definiu e sempre manterá os sete snapshots automáticos mais recentes. Habilitá-los é grátis – você só terá que pagar pelo armazenamento efetivo dos seus snapshots.

- Quais as diferenças entre snapshots manuais e automáticos?

  Os snapshots automáticos não podem ser rastreados ou exportados diretamente ao Amazon EC2. No entanto, podem ser copiados e convertidos em snapshots manuais. Para copiar um snapshot automático transformando-o em um manual, escolha a opção Manter no menu de contexto dos snapshots automáticos para copiá-lo como um snapshot manual.

- Como faço backup de minhas instâncias?

  Se você quiser fazer backup dos dados, poderá usar o console ou a API do Lightsail para obter um snapshot da instância. Em caso de falha ou erro de implantação de código, você poderá usar o snapshot da instância para criar uma instância totalmente nova. Recomendamos interromper temporariamente a instância para obter o snapshot. Dessa forma, você garante que os dados estejam completos e sem qualquer tipo de corrupção.
  
- Qual é a diferença entre interromper e excluir instâncias?

  Quando você interrompe a instância, ela é desligada em seu estado atual e estará disponível para ser iniciada novamente a qualquer momento. A interrupção da instância libera o IP público dela, portanto, é recomendável usar IPs estáticos para instâncias que devem reter o mesmo IP após a interrupção.

Ao excluir a instância, você estará executando uma ação destrutiva. A menos que você tenha obtido um snapshot da instância, todos os dados dela serão perdidos e não poderão ser recuperados novamente. Os endereços IPs públicos e privados da instância também serão liberados. Se você estava usando um IP estático nessa instância, ele será desconectado, mas permanecerá na sua conta.

- Como atualizo meu plano?

  Sim. Você pode obter um snapshot da instância e usar a API para iniciar uma nova instância com tamanho maior. É possível iniciar novas instâncias de um snapshot usando o console ou a CLI do Lightsail. Veja as instruções de uso da CLI aqui.

- Como conecto instâncias do Lightsail a outros recursos da minha conta da AWS?

  Você pode conectar instâncias do Lightsail a recursos de VPCs em sua conta da AWS de forma privada usando o emparelhamento de VPCs. Basta escolher Enable VPC peering na página da sua conta do Lightsail. O Lightsail fará todo o trabalho por você. Após a habilitação do emparelhamento de VPCs, será possível endereçar outros recursos da AWS na VPC padrão da AWS usando seus IPs privados. Encontre as instruções aqui.

Você precisa ter uma VPC padrão configurada na sua conta da AWS para que o emparelhamento de VPCs com o Lightsail funcione. As contas da AWS criadas antes de dezembro de 2013 não têm uma VPC padrão. Para essas contas, será necessário configurar a VPC padrão. Saiba mais sobre a configuração da VPC padrão aqui.

- Em quais regiões o Lightsail está disponível?

  No momento, o Lightsail está disponível em todas as zonas de disponibilidade das seguintes regiões da AWS:

Leste dos EUA (Norte da Virgínia)
Leste dos EUA (Ohio)
Oeste dos EUA (Oregon)
Canadá (Central)
Europa (Frankfurt)
Europa (Irlanda)
Europa (Londres)
Europa (Paris)
Europa (Estocolmo)
Ásia-Pacífico (Mumbai)
Ásia-Pacífico (Singapura)
Ásia-Pacífico (Sydney)
Ásia-Pacífico (Tóquio)
Ásia-Pacífico (Seul)

- O que são zonas de disponibilidade?

  As zonas de disponibilidade são coleções de datacenters operados em infraestrutura fisicamente distinta e independente, projetadas para oferecer alta confiabilidade. Os pontos comuns de falhas, como geradores e equipamentos de refrigeração, não são compartilhados entre as zonas de disponibilidade. Além disso, as zonas de disponibilidade são fisicamente separadas, de tal modo que até mesmo desastres extremamente incomuns, como incêndios, tornados ou enchentes, afetem somente uma única zona de disponibilidade.

- Quais são as cotas de serviço do Lightsail?

  Consulte as cotas de serviço mais recentes e quais delas podem ser aumentadas em Cotas de serviço do Lightsail na Referência geral da AWS. Se você precisar aumentar a cota, abra um caso junto ao atendimento ao cliente.

- Como posso obter mais ajuda?

  Estamos ao seu lado. O Quick Assist no Lightsail oferece dicas úteis e imediatas sobre as ações do console. No console do Lightsail, você também pode acessar uma biblioteca de guias de conceitos básicos, visões gerais e tópicos detalhados. E se você quiser usar a API ou a CLI, o Lightsail tem uma referência de APIs completa para todas as linguagens de programação permitidas. Também é possível usar os recursos de suporte do Lightsail:

Se você tiver um problema com sua conta ou faturamento, entre em contato com o atendimento ao cliente online. O acesso é gratuito, 24 horas por dia, 7 dias por semana está incluído em sua conta do Lightsail.
Em caso de dúvidas gerais sobre como usar o Lightsail, consulte a documentação do Lightsail e os fóruns de suporte.
Além disso, o AWS Support oferece uma linha de planos pagos para atender às suas necessidades individuais.

- Quais sistemas operacionais eu posso usar com o Amazon Lightsail?

  No momento, o Lightsail oferece suporte a 6 distribuições do Linux ou semelhantes ao Unix – Amazon Linux, Debian, FreeBSD, OpenSUSE e Ubuntu – e a 3 versões do Windows Server – 2012 R2, 2016 e 2019.

- O que são tags?

  Uma tag é um rótulo atribuído a um recurso do Lightsail. Cada tag consiste em uma chave e um valor, ambos definidos por você. O valor da tag é opcional, então você pode escolher criar tags “key-only” (somente chave) para recursos de filtragem no console Lightsail.

- O que posso fazer com tags no Lightsail?

  Tags têm vários casos de uso – elas permitem agrupar e filtrar recursos no console Lightsail e nas APIs, rastrear e organizar custos na sua fatura e regular quem pode visualizar ou modificar os recursos pelas regras de gerenciamento de acesso. Ao usar a marcação com tags nos recursos você pode:

 Organizar – use o console Lightsail e os filtros de API para visualizar e gerenciar recursos baseado nas tags atribuídas a eles. Isso é útil quando há muitos recursos do mesmo tipo: você pode identificar rapidamente um recurso específico com base nas tags que atribuiu a ele.
Alocar custos – rastreie e aloque custos em diferentes projetos e usuários aplicando marcações nos recursos e criando “cost allocation tags” (tags de alocação de custo) no console de faturamento. Para instâncias, você pode dividir a fatura e compreender os custos por projeto e por cliente.
Gerenciar acesso - controle como os usuários com acesso a sua conta da AWS podem editar, criar e excluir recursos do Lightsail usando as políticas do AWS Identity and Access Management. Isso permite colaborar mais facilmente com outros sem precisar fornecer a eles acesso total aos recursos do Lightsail.
Saiba mais sobre como usar tags no Lightsail >>

- Quais recursos podem ser marcados?

  Atualmente, o Lightsail tem suporte para marcação com tags para os seguintes recursos:

Instâncias (Linux e Windows)
Serviços de Contêiner
Discos de armazenamento em bloco
Load balancers
Bancos de dados
Zonas de DNS
Snapshots de instância, disco e banco de dados
Snapshots manuais também têm suporte para tags e recebem automaticamente as mesmas tags que o recurso de origem. Você pode editar essas tags ao usar um snapshot para criar uma nova instância, disco ou banco de dados.

- Como posso aplicar tags aos meus snapshots do Lightsail?

  O console Lightsail automaticamente aplica marcações nos snapshots com as mesmas tags do recurso pai. Contudo, as tags não são copiadas automaticamente a partir de um recurso para os snapshots automáticos. Se você usa a API do Lightsail para criar um snapshot, você mesmo pode escolher as tags para o snapshot.
Importante: As tags de snapshots de banco de dados atualmente não estão inclusas nos relatórios de faturamento (tags de alocação de custos).

- Qual é a diferença entre tags de chave/valor e tags somente de chaves?

  As etiquetas do Lightsail são pares de chave/valor, permitindo a organização de recursos como instâncias em diferentes categorias, por exemplo, project:Blog, project:Game, project:Test. Isso permite controle total em todos os casos de uso como organização de recursos, relatórios de fatura e gerenciamento de acesso. O console Lightsail permite a marcação com etiquetas de recursos com tags somente de chaves para filtragem rápida no console.

- O Amazon Lightsail é compatível com monitoramento e alertas?

  Sim. Com o Amazon Lightsail, você pode coletar métricas sobre vários recursos, incluindo instâncias, load balancers e bancos de dados. Para qualquer recurso individual, você pode configurar dois limites de alarmes para cada métrica. Se o limite do alarme for violado, você receberá uma notificação no console do Lightsail e, opcionalmente, poderá optar por receber uma mensagem de e-mail e/ou SMS. Não há cobrança adicional pelo recurso de alertas e monitoramento no Lightsail. No entanto, você pode incorrer em cobranças da sua operadora de celular por mensagens SMS.
 
 
## Load balancer do Lightsail:
- O que posso fazer com load balancers do Lightsail?

  Os load balancers do Lightsail permitem que você crie sites e aplicativos altamente disponíveis. Ao distribuir o tráfego nas instâncias em zonas de disponibilidade diferentes e direcionar o tráfego apenas para instâncias de destino sem problemas de integridade, os load balancers do Lightsail reduzem o risco de falhas do seu aplicativo causadas por algum defeito na instância ou devido a uma interrupção do datacenter. Com os load balancers do Lightsail e várias instâncias de destino, sites e aplicativos também podem acomodar aumentos no tráfego da web e manter um bom desempenho para os visitantes durante os períodos de pico na carga.

Além disso, você pode usar os load balancers do Lightsail para criar aplicativos seguros e aceitar o tráfego HTTPS. O Lightsail elimina a complexidade da solicitação, do provisionamento e da manutenção de certificados SSL/TLS. O gerenciamento incorporado de certificados solicita e renova certificados para você e os adiciona automaticamente ao seu load balancer.

- Posso usar load balancers com instâncias executadas em zonas de disponibilidade ou regiões da AWS diferentes?

  Não é possível usar load balancers com instâncias em diferentes regiões da AWS. No entanto, é possível usar instâncias de destino em diferentes zonas de disponibilidade com o load balancer. Na verdade, recomendamos que você distribua suas instâncias de destino entre zonas de disponibilidade para maximizar a disponibilidade de aplicativos.

- Como o load balancer do Lightsail lida com picos de tráfego?

  Os load balancers do Lightsail escalam automaticamente para processar picos de tráfego para o aplicativo sem necessidade de ajustes manuais. Se o aplicativo experimentar um pico temporário de tráfego, o load balancer do Lightsail escalará automaticamente e continuará a direcionar tráfego às instâncias do Lightsail com eficiência. Embora o load balancer do Lightsail seja projetado para lidar facilmente com picos de tráfego, os aplicativos que experimentam altos volumes de tráfego de forma contínua podem sofrer degradação ou limitação de desempenho. Se você espera que o aplicativo gerencie mais de 5 GB/hora de dados ou tenha um grande número de conexões (mais de 400 mil novas conexões/hora, mais de 15 mil conexões ativas simultâneas) de forma contínua, recomendamos o uso do Amazon EC2 com Application Load Balancing.
  
- Como os load balancers do Lightsail direcionam o tráfego para minhas instâncias de destino?

Os load balancers do Lightsail direcionam o tráfego para suas instâncias de destino sem problemas com base em um algoritmo Round Robin.
  
- Como o Lightsail sabe se minhas instâncias de destino não apresentam problemas?

  Durante a criação do load balancer, será solicitado que você especifique um caminho (um arquivo comum ou o URL de uma página da web) para que o Lightsail execute o ping. Se a instância de destino puder ser acessada usando esse caminho, o Lightsail direcionará o tráfego para lá. Se uma ou mais instâncias de destino não emitirem resposta, o Lightsail não direcionará o tráfego para elas. Se for necessário, você pode atualizar o caminho de verificação de integridade nas telas de gerenciamento do load balancer.
  
- Qual é a diferença entre tags de chave/valor e tags somente de chaves?

  As tags do Lightsail são pares de chave/valor, permitindo a organização de recursos como instâncias em diferentes categorias, por exemplo, project:Blog, project:Game, project:Test. Isso permite controle total em todos os casos de uso como organização de recursos, relatórios de fatura e gerenciamento de acesso. O console Lightsail permite a marcação com tags de recursos com tags somente de chaves para filtragem rápida no console.

- Posso atribuir uma instância a vários load balancers?

Sim. Se você desejar fazer isso, o Lightsail aceita a adição de instâncias como instâncias de destino para mais de um load balancer.

- O que acontecerá com as instâncias de destino quando o load balancer for excluído?

  Se você excluir o load balancer, as instâncias de destino anexadas continuarão em execução normalmente e serão exibidas no console do Lightsail como instâncias normais do Lightsail. Observe que provavelmente será necessário atualizar seus registros de DNS para direcionar o tráfego para uma das suas antigas instâncias de destino depois que você excluir o load balancer.
  
- O que é persistência de sessões?

  A persistência de sessões permite que o load balancer associe a sessão de um visitante a uma instância de destino específica. Isso garante que todas as solicitações do usuário durante a sessão sejam enviadas para a mesma instância de destino. O Lightsail aceita a persistência de sessões para aplicativos que exigem que os visitantes acessem as mesmas instâncias de destino para manter a uniformidade dos dados. Por exemplo, vários aplicativos que exigem a autenticação do usuário podem se beneficiar do uso da persistência da sessão. Você pode ativar a persistência de sessões para um load balancer específico por meio das telas de gerenciamento do load balancer após a criação.
  
- Para quais tipos de conexões os load balancers do Lightsail oferecem suporte?

Os load balancers do Lightsail aceitam conexões HTTP e HTTPS.

Link relevante: https://aws.amazon.com/pt/lightsail/faq/#:~:text=P%3A%20O%20que%20%C3%A9%20o,hospedar%20suas%20aplica%C3%A7%C3%B5es%20na%20nuvem.  &&   https://aws.amazon.com/pt/lightsail/resources/
