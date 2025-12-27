# Awesome Sysadmin

[![Awesome](https://awesome.re/badges/nice.svg)](https://awesome.re)

A rigorously curated collection of premier open-source sysadmin resources, inspired by the [Awesome PHP](https://github.com/ziadoz/awesome-php) project. This repository serves as an authoritative reference for infrastructure engineers, DevOps professionals, and system architects seeking robust, production-ready tools.

## Table of Contents

* [Categories](#categories)
  * [Backup & Disaster Recovery](#backup--disaster-recovery)
  * [Cloning & Provisioning](#cloning--provisioning)
  * [Cloud Computing & Orchestration](#cloud-computing--orchestration)
  * [Cloud Storage](#cloud-storage)
  * [Collaborative Software](#collaborative-software)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Deployment](#continuous-integration--deployment)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS & DHCP](#dns--dhcp)
  * [Hosting Control Panels](#hosting-control-panels)
  * [IT Asset Management](#it-asset-management)
  * [Identity & Access Management](#identity--access-management)
  * [Log Management](#log-management)
  * [Monitoring & Observability](#monitoring--observability)
  * [Network Configuration](#network-configuration)
  * [NoSQL Databases](#nosql-databases)
  * [Queuing & Messaging](#queuing--messaging)
  * [Relational Databases (RDBMS)](#relational-databases-rdbms)
  * [Security & Intrusion Detection](#security--intrusion-detection)
  * [Service Discovery & Mesh](#service-discovery--mesh)
  * [Software Containers](#software-containers)
  * [SSH & Remote Access](#ssh--remote-access)
  * [Ticketing & Helpdesk](#ticketing--helpdesk)
  * [Virtualization](#virtualization)
  * [VPN & Networking](#vpn--networking)
  * [Web Servers & Proxies](#web-servers--proxies)
  * [Wikis & Documentation](#wikis--documentation)
* [Resources](#resources)
* [Contributing](#contributing)

---

## Categories

### Backup & Disaster Recovery
*Enterprise-grade backup and recovery solutions.*

* **Amanda** - Advanced Network Backup Tool. A client-server model backup tool suitable for enterprises.
* **Bacula** - A powerful, enterprise-grade network backup solution.
* **Backupninja** - Lightweight, extensible meta-backup system for UNIX-like systems.
* **Backuppc** - High-performance client-server backup tool featuring file pooling and compression.
* **Burp** - Network backup and restore program featuring deduplication and client-side encryption.
* **Duplicity** - Encrypted, bandwidth-efficient backups using the rsync algorithm.
* **Lsyncd** - Live Synchronization Daemon. Watches local directory trees and synchronizes changes using rsync.
* **Rsnapshot** - Filesystem snapshotting utility based on rsync.
* **UrBackup** - Another easy-to-use client-server backup system.

### Cloning & Provisioning
*Tools for system imaging and automated deployment.*

* **Clonezilla** - A partition and disk imaging/cloning program.
* **Debian-Installer** - Network installation system for Debian.
* **FOG** - Linux-based cloning and imaging solution.
* **RapidDeploy** - Agentless deployment and configuration management.

### Cloud Computing & Orchestration
*Platforms for managing cloud infrastructure.*

* **AppScale** - Open-source implementation of the Google App Engine.
* **CloudStack** - Apache CloudStack is an IaaS platform for public and private clouds.
* **Cobbler** - Linux installation server that allows for rapid setup of network installation.
* **OpenNebula** - Flexible open-source cloud computing platform.
* **OpenStack** - Open-source software for building private and public clouds.
* **ProfitBricks** - A cloud computing platform with a configuration wizard and API.

### Cloud Storage
*File synchronization and storage solutions.*

* **CloudI** - A cloud API written in Erlang.
* **Minio** - High performance distributed object storage server.
* **Nextcloud** - A safe home for all your data (fork of ownCloud).
* **OwnCloud** - Ensuring data security and control on your own server.
* **Seafile** - Professional open-source cloud storage platform.
* **SparkleShare** - Git-based file synchronization and collaboration.

### Collaborative Software
*Real-time collaboration tools.*

* **Citadel/UX** - A complete groupware and email solution.
* **Egroupware** - A flexible enterprise collaboration platform.
* **Jitsi Meet** - Secure, simple and scalable video conferencing.
* **Kontalk** - Secure messaging based on XMPP.
* **Mattermost** - Open-source, self-hosted Slack-alternative.
* **Openmeetings** - Video conferencing and collaborative whiteboard.
* **RetroShare** - Decentralized communication platform.
* **Rocket.Chat** - Teamchat software alternative to Slack.
* **Trove** - A collaborative editing system.
* **Zimbra** - Collaborative suite (email, calendar, tasks).

### Configuration Management
*Automation tools for infrastructure configuration.*

* **Ansible** - A radically simple IT automation platform.
* **Bcfg2** - Tools for managing system configuration.
* **Chef** - A powerful automation platform for infrastructure.
* **Puppet** - Server automation framework and language.
* **SaltStack** - Fast, scalable, and flexible systems management.

### Continuous Integration & Deployment
*CI/CD pipeline automation tools.*

* **Buildbot** - Python-based CI/CD framework.
* **Drone** - Continuous Integration platform built on Docker.
* **GoCD** - A continuous delivery tool from ThoughtWorks.
* **Jenkins** - The most popular open-source CI server.
* **Woodpecker CI** - A simple CI pipeline with CI/CD capabilities.

### Distributed Filesystems
*Scalable distributed storage systems.*

* **Ceph** - Unified, distributed storage system.
* **GlusterFS** - Scalable network-attached storage file system.
* **HDFS** - Hadoop Distributed File System.
* **IPFS** - Permanent web. Distributed file system.
* **MooseFS** - Fault-tolerant, network distributed file system.
* **OrangeFS** - High-performance parallel file system.
* **SeaweedFS** - Simple and highly scalable distributed file system.
* **Tahoe-LAFS** - Decentralized cloud storage system.

### DNS & DHCP
*DNS servers and DHCP management tools.*

* **Bind9** - Berkeley Internet Name Domain (DNS).
* **CoreDNS** - DNS server written in Go.
* **Dnsmasq** - Lightweight DNS forwarder and DHCP server.
* **Dovecot** - IMAP/POP3 server (often paired with DNS).
* **IPA** - Integrated Identity and Policy Management.
* **PowerDNS** - A versatile DNS server.
* **Unbound** - Validating, recursive, and caching DNS resolver.

### Hosting Control Panels
*Web-based hosting management interfaces.*

* **Cockpit** - Web-based interface for servers.
* **Froxlor** - Lightweight management panel.
* **ISPConfig** - Open-source hosting control panel.
* **Webmin** - Web-based interface for system administration.
* **ZPanel** - Open-source hosting control panel.

### IT Asset Management
*Tools for tracking hardware and software inventory.*

* **CMDB** - A Ruby on Rails CMDB application.
* **Collins** - A hardware asset management system.
* **Disk Catalog** - Backup and cataloging tool.
* **GLPI** - Information Resource Manager.
* **iTop** - IT Service Management platform.
* **Netbox** - IP address management (IPAM) and data center infrastructure management (DCIM).
* **OCS Inventory NG** - Inventory and deployment.

### Identity & Access Management
*LDAP servers and Single Sign-On solutions.*

* **FreeIPA** - Identity, Policy, and Audit system.
* **LAM** - LDAP Account Manager.
* **OpenLDAP** - The open-source LDAP server.
* **OpenVPN** - A full-featured open-source VPN solution.
* **phpLDAPadmin** - A web-based LDAP administration tool.
* **Samba** - Provides file and print services to SMB/CIFS clients.

### Log Management
*Centralized logging and analysis tools.*

* **Elasticsearch** - Search and analytics engine (often used for logs).
* **Fluentd** - Unified logging layer.
* **Graylog** - Open-source log management platform.
* **Kibana** - Visualization tool for Elasticsearch.
* **Logstash** - Server-side data processing pipeline.
* **Nginx** - High-performance web server and reverse proxy (log management features).

### Monitoring & Observability
*System and application monitoring solutions.*

* **Alerta** - Alerting system.
* **Cabot** - Self-hosted, easily-deployable monitoring and alerts service.
* **Cacti** - Network graphing solution.
* **Datadog** - Monitoring service (SaaS/PaaS).
* **Grafana** - Graph and dashboard builder.
* **Icinga** - Enterprise-grade monitoring system.
* **Monit** - Monitoring and management tool.
* **Nagios** - Industry-standard monitoring system.
* **Netdata** - Real-time performance monitoring.
* **Prometheus** - Monitoring system and time series database.
* **Sensu** - Monitoring pipeline for enterprises.
* **Zabbix** - Enterprise-class open-source monitoring solution.

### Network Configuration
*Tools for managing network device configurations.*

* **Oxidized** - Configuration change tracking and backup tool.
* **RANCID** - Tracks configuration changes in network devices.
* **Rudder** - Configuration management and automation.

### NoSQL Databases
*Non-relational database systems.*

* **Cassandra** - Distributed NoSQL database.
* **CouchDB** - Document-oriented database.
* **Elasticsearch** - Search and analytics engine.
* **HBase** - Hadoop database.
* **InfluxDB** - Time series database.
* **MongoDB** - Document database.
* **Neo4j** - Graph database.
* **Redis** - In-memory data structure store.
* **Riak** - Distributed NoSQL database.

### Queuing & Messaging
*Message brokers and queueing systems.*

* **ActiveMQ** - Java-based message broker.
* **Beanstalkd** - Simple, fast queueing.
* **HornetQ** - Java message broker.
* **Kafka** - High-throughput distributed messaging system.
* **NSQ** - Real-time distributed messaging platform.
* **RabbitMQ** - Open-source message broker.

### Relational Databases (RDBMS)
*SQL database management systems.*

* **MariaDB** - Community-developed fork of MySQL.
* **MySQL** - The world's most popular open-source database.
* **PostgreSQL** - Object-relational database system.
* **SQLite** - Self-contained, serverless SQL database engine.

### Security & Intrusion Detection
*Tools for securing infrastructure and detecting threats.*

* **AIDE** - File and directory integrity checker.
* **ClamAV** - Open-source antivirus engine.
* **Fail2Ban** - Bans IPs after repeated failures.
* **Firewall (iptables/nftables)** - Linux kernel firewall.
* **OpenVAS** - Vulnerability scanning framework.
* **OSSEC** - Host-based intrusion detection system.
* **Snort** - Network intrusion detection and prevention system.
* **Suricata** - High-performance Network IDS, IPS and NSM engine.
* **Wireshark** - Network protocol analyzer.

### Service Discovery & Mesh
*Dynamic service discovery and configuration.*

* **Consul** - Service discovery and configuration.
* **Etcd** - Distributed reliable key-value store.
* **Kubernetes** - Container orchestration system.
* **Linkerd** - Service mesh for cloud native applications.
* **Nomad** - Simple and flexible workload orchestrator.
* **Zookeeper** - Centralized service for distributed coordination.

### Software Containers
*Container runtimes and orchestration tools.*

* **Containerd** - Core container runtime.
* **Docker** - Container platform.
* **Kubernetes** - Container orchestration.
* **LXC** - Linux containers.
* **Podman** - Daemonless container engine.
* **Rancher** - Kubernetes management platform.

### SSH & Remote Access
*Secure remote administration tools.*

* **GateOne** - Terminal emulator and SSH client.
* **Mosh** - Mobile shell with roaming and intelligent local echo.
* **SSH** - Standard remote administration tool.
* **Teleport** - Access anything via SSH, Kubernetes, RDP, etc.

### Ticketing & Helpdesk
*IT service management and ticketing systems.*

* **Bugzilla** - Bug tracker.
* **Cerb** - Email-based ticketing system.
* **Diamante** - Collaborative ticketing system.
* **Flyspray** - Bug tracking system.
* **Jira** - Professional issue and project tracking tool.
* **Mantis** - Bug tracker.
* **OTRS** - Ticket request management system.
* **Phabricator** - Suite of tools for software development.
* **Request Tracker** - Ticket tracking system.
* **Redmine** - Flexible project management web application.

### Virtualization
*Hypervisors and virtualization platforms.*

* **OpenVZ** - Container-based virtualization for Linux.
* **Proxmox VE** - Open-source server virtualization management.
* **QEMU** - Processor emulator and virtualizer.
* **VirtualBox** - General-purpose full virtualizer.
* **Xen** - Hypervisor for x86.
* **oVirt** - Virtualization management platform.

### VPN & Networking
*Virtual Private Network solutions.*

* **EasyRSA** - Simple CA management.
* **FreeRADIUS** - RADIUS server and policy server.
* **OpenVPN** - Open-source VPN solution.
* **Pritunl** - Enterprise VPN platform.
* **StrongSwan** - IPsec implementation for Linux.
* **Tailscale** - Mesh VPN based on WireGuard.
* **WireGuard** - Modern, fast, and secure VPN tunnel.

### Web Servers & Proxies
*HTTP servers, load balancers, and reverse proxies.*

* **Apache HTTP Server** - Popular web server.
* **Caddy** - Auto HTTPS web server.
* **Envoy** - High-performance edge/middle/service proxy.
* **HAProxy** - TCP/HTTP load balancer.
* **Lighttpd** - Secure, fast, compliant, and flexible web server.
* **Nginx** - High-performance HTTP server and reverse proxy.
* **Traefik** - Modern HTTP reverse proxy and load balancer.

### Wikis & Documentation
*Knowledge base and documentation platforms.*

* **DokuWiki** - Simple open-source wiki.
* **Documize** - Modern documentation platform.
* **Gollum** - Git-backed wiki.
* **MediaWiki** - Powering Wikipedia.
* **MkDocs** - Project documentation with Markdown.
* **Outline** - Team knowledge base and wiki.
* **Wiki.js** - Modern wiki app built on Node.js.

## Resources

* **Blogs** - High-quality technical blogs (e.g., Kernel.org, LWN.net).
* **Books** - Essential reading for sysadmins (e.g., "The Phoenix Project", "Site Reliability Engineering").
* **Communities** - Forums and discussion boards (e.g., Reddit r/sysadmin, Server Fault).
* **Newsletters** - Weekly updates on tech and ops.
* **Podcasts** - Audio content for infrastructure professionals.

## Contributing

Contributions are always welcome! Please take a look at our [Contribution Guidelines](CONTRIBUTING.md) before submitting a pull request.

1. Ensure the tool is open-source and actively maintained.
2. Add the tool to the appropriate category alphabetically.
3. Provide a brief, descriptive summary of the tool.
4. Submit a PR with a clear description of changes.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.