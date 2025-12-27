# Awesome Sysadmin

[![Awesome](https://awesome.re/badges/nice.svg)](https://awesome.re)

Uma coleção rigorosamente curada de recursos de sysadmin de código aberto de primeira linha, inspirada no projeto [Awesome PHP](https://github.com/ziadoz/awesome-php). Este repositório serve como uma referência autoritativa para engenheiros de infraestrutura, profissionais de DevOps e arquitetos de sistemas que buscam ferramentas robustas e prontas para produção.

## Tabela de Conteúdos

* [Categorias](#categorias)
  * [Backup e Recuperação de Desastres](#backup-e-recuperação-de-desastres)
  * [Clonagem e Provisionamento](#clonagem-e-provisionamento)
  * [Computação em Nuvem e Orquestração](#computação-em-nuvem-e-orquestração)
  * [Armazenamento em Nuvem](#armazenamento-em-nuvem)
  * [Software Colaborativo](#software-colaborativo)
  * [Gerenciamento de Configuração](#gerenciamento-de-configuração)
  * [Integração e Deployment Contínuos](#integração-e-deployment-contínuos)
  * [Sistemas de Arquivos Distribuídos](#sistemas-de-arquivos-distribuídos)
  * [DNS e DHCP](#dns-e-dhcp)
  * [Painéis de Controle de Hospedagem](#painéis-de-controle-de-hospedagem)
  * [Gestão de Ativos de TI](#gestão-de-ativos-de-ti)
  * [Identidade e Acesso](#identidade-e-acesso)
  * [Gerenciamento de Logs](#gerenciamento-de-logs)
  * [Monitoramento e Observabilidade](#monitoramento-e-observabilidade)
  * [Configuração de Rede](#configuração-de-rede)
  * [Bancos de Dados NoSQL](#bancos-de-dados-nosql)
  * [Filas e Mensagens](#filas-e-mensagens)
  * [Bancos de Dados Relacionais (RDBMS)](#bancos-de-dados-relacionais-rdbms)
  * [Segurança e Detecção de Intrusões](#segurança-e-deteção-de-intrusões)
  * [Descoberta de Serviços e Mesh](#descoberta-de-serviços-e-mesh)
  * [Contêineres de Software](#contêineres-de-software)
  * [SSH e Acesso Remoto](#ssh-e-acesso-remoto)
  * [Tickets e Helpdesk](#tickets-e-helpdesk)
  * [Virtualização](#virtualização)
  * [VPN e Redes](#vpn-e-redes)
  * [Servidores Web e Proxies](#servidores-web-e-proxies)
  * [Wikis e Documentação](#wikis-e-documentação)
* [Recursos](#recursos)
* [Contribuir](#contribuir)

---

## Categorias

### Backup e Recuperação de Desastres
*Soluções corporativas de backup e recuperação.*

* **Amanda** - Ferramenta de Backup de Rede Avançada. Modelo cliente-servidor adequado para empresas.
* **Bacula** - Solução corporativa de backup de rede.
* **Backupninja** - Sistema de metadados leve e extensível.
* **Backuppc** - Ferramenta de backup alto desempenho com agrupamento e compactação de arquivos.
* **Burp** - Programa de backup e restauração com deduplicação e criptografia no cliente.
* **Duplicity** - Backups criptografados e eficientes em banda usando o algoritmo rsync.
* **Lsyncd** - Daemon de Sincronização ao Vivo.
* **Rsnapshot** - Utilitário de snapshot baseado no rsync.
* **UrBackup** - Outro sistema de backup fácil de usar.

### Clonagem e Provisionamento
*Ferramentas para imaging de sistema e implantação automatizada.*

* **Clonezilla** - Programa de particionamento e imaging/clonagem de discos.
* **Debian-Installer** - Sistema de instalação via rede para Debian.
* **FOG** - Solução de clonagem e imaging baseada em Linux.
* **RapidDeploy** - Implantação sem agente e gerenciamento de configuração.

### Computação em Nuvem e Orquestração
*Plataformas para gerenciar infraestrutura em nuvem.*

* **AppScale** - Implementação de código aberto do Google App Engine.
* **CloudStack** - Plataforma IaaS para nuvens públicas e privadas.
* **Cobbler** - Servidor de instalação Linux para setup rápido.
* **OpenNebula** - Plataforma flexível de computação em nuvem de código aberto.
* **OpenStack** - Software de código aberto para construir nuvens privadas e públicas.

### Armazenamento em Nuvem
*Sincronização de arquivos e soluções de armazenamento.*

* **Minio** - Servidor de armazenamento distribuído de alto desempenho.
* **Nextcloud** - Um lar seguro para todos os seus dados (fork do ownCloud).
* **OwnCloud** - Garantindo segurança e controle de dados.
* **Seafile** - Plataforma profissional de armazenamento em nuvem.
* **SparkleShare** - Sincronização e colaboração baseada em Git.

### Software Colaborativo
*Ferramentas de colaboração em tempo real.*

* **Citadel/UX** - Solução completa de groupware e email.
* **Egroupware** - Plataforma de colaboração empresarial flexível.
* **Jitsi Meet** - Videoconferência segura e escalável.
* **Mattermost** - Alternativa ao Slack, auto-hospedada.
* **Openmeetings** - Videoconferência e quadro branco colaborativo.
* **Rocket.Chat** - Software de chat alternativo ao Slack.

### Gerenciamento de Configuração
*Ferramentas de automação para configuração de infraestrutura.*

* **Ansible** - Plataforma de automação radicalmente simples.
* **Chef** - Plataforma poderosa de automação de infraestrutura.
* **Puppet** - Framework e linguagem de automação de servidores.
* **SaltStack** - Sistemas gerenciáveis, rápidos e flexíveis.

### Integração e Deployment Contínuos
*Ferramentas de automação de pipelines CI/CD.*

* **Buildbot** - Framework CI/CD baseado em Python.
* **Drone** - Plataforma de CI construída sobre Docker.
* **GoCD** - Ferramenta de entrega contínua.
* **Jenkins** - O servidor CI mais popular de código aberto.

### Sistemas de Arquivos Distribuídos
*Sistemas de armazenamento distribuído escaláveis.*

* **Ceph** - Sistema de armazenamento distribuído unificado.
* **GlusterFS** - Sistema de arquivos de armazenamento anexo à rede escalável.
* **IPFS** - Sistema de arquivos distribuído.
* **MooseFS** - Sistema de arquivos distribuído tolerante a falhas.
* **SeaweedFS** - Sistema de arquivos distribuído simples e altamente escalável.

### DNS e DHCP
*Servidores DNS e ferramentas de gerenciamento DHCP.*

* **Bind9** - Berkeley Internet Name Domain (DNS).
* **CoreDNS** - Servidor DNS escrito em Go.
* **Dnsmasq** - Encaminhador DNS leve e servidor DHCP.
* **IPA** - Gerenciamento Integrado de Identidade e Políticas.
* **PowerDNS** - Servidor DNS versátil.
* **Unbound** - Resolvedor DNS validante, recursivo e cache.

### Painéis de Controle de Hospedagem
*Interfaces web para gerenciamento de hospedagem.*

* **Cockpit** - Interface baseada em web para servidores.
* **Froxlor** - Painel de gerenciamento leve.
* **ISPConfig** - Painel de controle de hospedagem de código aberto.
* **Webmin** - Interface web para administração de sistemas.

### Gestão de Ativos de TI
*Ferramentas para rastrear hardware e inventário de software.*

* **Collins** - Sistema de gestão de ativos de hardware.
* **GLPI** - Gerenciador de Recursos de Informação.
* **iTop** - Plataforma de Gestão de Serviços de TI.
* **Netbox** - Gerenciamento de endereçamento IP (IPAM) e infraestrutura de data center (DCIM).
* **OCS Inventory NG** - Inventário e implantação.

### Identidade e Acesso
*Servidores LDAP e soluções de Single Sign-On.*

* **FreeIPA** - Sistema de Identidade, Políticas e Auditoria.
* **LAM** - Gerenciador de Contas LDAP.
* **OpenLDAP** - Servidor LDAP de código aberto.
* **OpenVPN** - Solução VPN completa de código aberto.
* **phpLDAPadmin** - Ferramenta web de administração LDAP.
* **Samba** - Fornece serviços de arquivos e impressão para clientes SMB/CIFS.

### Gerenciamento de Logs
*Centralização e análise de logs.*

* **Elasticsearch** - Motor de busca e análise.
* **Fluentd** - Camada de logging unificada.
* **Graylog** - Plataforma de gerenciamento de logs.
* **Kibana** - Ferramenta de visualização para Elasticsearch.
* **Logstash** - Pipeline de processamento de dados.

### Monitoramento e Observabilidade
*Soluções de monitoramento de sistemas e aplicações.*

* **Alerta** - Sistema de alertas.
* **Cacti** - Solução de gráficos de rede.
* **Grafana** - Construtor de gráficos e dashboards.
* **Icinga** - Sistema de monitoramento de nível empresarial.
* **Monit** - Ferramenta de monitoramento e gerenciamento.
* **Nagios** - Sistema de monitoramento padrão da indústria.
* **Netdata** - Monitoramento de desempenho em tempo real.
* **Prometheus** - Sistema de monitoramento e banco de dados de séries temporais.
* **Zabbix** - Solução de monitoramento de código aberto.

### Configuração de Rede
*Ferramentas para gerenciar configurações de dispositivos de rede.*

* **Oxidized** - Rastreamento de mudanças e backup de configurações.
* **RANCID** - Rastreia mudanças em dispositivos de rede.
* **Rudder** - Automação e gerenciamento de configuração.

### Bancos de Dados NoSQL
*Sistemas de banco de dados não relacionais.*

* **Cassandra** - Banco de dados NoSQL distribuído.
* **CouchDB** - Banco de dados orientado a documentos.
* **Elasticsearch** - Motor de busca e análise.
* **HBase** - Banco de dados Hadoop.
* **InfluxDB** - Banco de dados de séries temporais.
* **MongoDB** - Banco de dados de documentos.
* **Neo4j** - Banco de dados gráfico.
* **Redis** - Armazenamento de estruturas de dados na memória.
* **Riak** - Banco de dados NoSQL distribuído.

### Filas e Mensagens
*Brokers de mensagens e sistemas de fila.*

* **ActiveMQ** - Broker de mensagens Java.
* **Beanstalkd** - Filas simples e rápidas.
* **Kafka** - Sistema de mensagens distribuído de alta capacidade.
* **NSQ** - Plataforma de mensagens distribuídas em tempo real.
* **RabbitMQ** - Broker de mensagens de código aberto.

### Bancos de Dados Relacionais (RDBMS)
*Sistemas de gerenciamento de bancos de dados SQL.*

* **MariaDB** - Fork desenvolvido pela comunidade do MySQL.
* **MySQL** - O banco de dados mais popular do mundo.
* **PostgreSQL** - Sistema de banco de dados relacional.
* **SQLite** - Motor de banco de dados SQL autônomo.

### Segurança e Detecção de Intrusões
*Ferramentas para proteger a infraestrutura e detectar ameaças.*

* **AIDE** - Verificador de integridade de arquivos e diretórios.
* **ClamAV** - Motor de antivírus de código aberto.
* **Fail2Ban** - Bane IPs após falhas repetidas.
* **Firewall (iptables/nftables)** - Firewall do kernel Linux.
* **OpenVAS** - Framework de varredura de vulnerabilidades.
* **OSSEC** - Sistema de detecção de intrusões baseado em host.
* **Snort** - Sistema de detecção e prevenção de intrusões de rede.
* **Suricata** - Motor de IDS, IPS e NSM de alto desempenho.
* **Wireshark** - Analisador de protocolos de rede.

### Descoberta de Serviços e Mesh
*Descoberta de serviços e configuração dinâmica.*

* **Consul** - Descoberta de serviços e configuração.
* **Etcd** - Loja de chaves confiável e distribuída.
* **Kubernetes** - Sistema de orquestração de contêineres.
* **Linkerd** - Mesh de serviços para aplicações nativas da nuvem.

### Contêineres de Software
*Runtimes de contêineres e ferramentas de orquestração.*

* **Containerd** - Runtime principal de contêineres.
* **Docker** - Plataforma de contêineres.
* **Kubernetes** - Orquestração de contêineres.
* **LXC** - Contêineres Linux.
* **Podman** - Motor de contêineres sem daemon.

### SSH e Acesso Remoto
*Ferramentas seguras de administração remota.*

* **GateOne** - Emulador de terminal e cliente SSH.
* **Mosh** - Shell móvel com roteamento e eco local inteligente.
* **SSH** - Ferramenta padrão de administração remota.
* **Teleport** - Acesso seguro a SSH, Kubernetes, RDP, etc.

### Tickets e Helpdesk
*Sistemas de gerenciamento de serviços e tickets.*

* **Bugzilla** - Rastreador de bugs.
* **Cerb** - Sistema de tickets baseado em email.
* **Flyspray** - Rastreador de bugs.
* **Jira** - Ferramenta profissional de rastreamento de problemas.
* **Mantis** - Rastreador de bugs.
* **OTRS** - Sistema de gerenciamento de solicitações.
* **Redmine** - Aplicação web flexível de gerenciamento de projetos.

### Virtualização
*Hipervisores e plataformas de virtualização.*

* **OpenVZ** - Virtualização baseada em contêineres para Linux.
* **Proxmox VE** - Gerenciamento aberto de virtualização de servidores.
* **QEMU** - Emulador de processador e virtualizador.
* **VirtualBox** - Virtualizador geral completo.
* **Xen** - Hipervisor para x86.

### VPN e Redes
*Soluções de Rede Privada Virtual.*

* **EasyRSA** - Gerenciamento simples de CA.
* **FreeRADIUS** - Servidor RADIUS e de políticas.
* **OpenVPN** - Solução VPN de código aberto.
* **StrongSwan** - Implementação IPsec para Linux.
* **WireGuard** - Túnel VPN moderno, rápido e seguro.

### Servidores Web e Proxies
*Servidores HTTP, balanceadores de carga e proxies inversos.*

* **Apache HTTP Server** - Servidor web popular.
* **Caddy** - Servidor web com HTTPS automático.
* **Envoy** - Proxy de borda/meio/serviço de alto desempenho.
* **HAProxy** - Balanceador de carga TCP/HTTP.
* **Lighttpd** - Servidor web seguro, rápido e flexível.
* **Nginx** - Servidor HTTP de alto desempenho e proxy inverso.
* **Traefik** - Proxy inverso moderno e balanceador de carga.

### Wikis e Documentação
*Plataformas de base de conhecimento e documentação.*

* **DokuWiki** - Wiki simples e aberta.
* **Gollum** - Wiki baseado em Git.
* **MediaWiki** - Motor que alimenta a Wikipédia.
* **MkDocs** - Documentação de projetos com Markdown.
* **Outline** - Base de conhecimento e wiki modernos.
* **Wiki.js** - Aplicativo wiki moderno construído em Node.js.

## Recursos

* **Blogs** - Blogs técnicos de alta qualidade.
* **Books** - Leitura essencial para sysadmins.
* **Communities** - Fóruns e placas de discussão.
* **Newsletters** - Atualizações semanais sobre tecnologia e operações.
* **Podcasts** - Conteúdo de áudio para profissionais de infraestrutura.

## Contribuir

Contribuições são sempre bem-vindas! Por favor, dê uma olhada nas nossas [Diretrizes de Contribuição](CONTRIBUTING.md) antes de enviar um pull request.

1. Certifique-se de que a ferramenta é de código aberto e mantida ativamente.
2. Adicione a ferramenta à categoria apropriada em ordem alfabética.
3. Forneça um resumo breve e descritivo da ferramenta.
4. Envie um PR com uma descrição clara das alterações.

## Licença

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Na medida do possível sob a lei, os contribuidores renunciaram a todos os direitos autorais e direitos relacionados ou vizinhos a este trabalho.