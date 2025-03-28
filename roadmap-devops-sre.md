# Roadmap DevOps / SRE

- [Redes](#redes)
- [Linux](#linux)
- [Shell script](#shell-script)
- [Cloud Computing](#cloud-computing)
- [Configurations Management](#configurations-management)
- [IaC (Infrastructure as Code)](#iac-infrastructure-as-code)
- [Containers](#containers)
- [Git](#git)
- [Teoria DevOps](#teoria-devops)

## Redes

### Modelo OSI (Semana 1)

- Camada 1 - Física
- Camada 2 - Enlace
- Camada 3 - Rede
- Camada 4 - Transporte
- Camada 5 - Sessão
- Camada 6 - Apresentação
- Camada 7 - Aplicação

### Protocolos de Rede (Semana 2)

- TCP/IP
- HTTP/HTTPS (métodos GET, POST, PUT, DELETE e PATCH)
- HTTP/HTTPS (códigos de status)
- gRPC
- WebSockets
- TLS/SSL
- FTP/SFTP
- DNS
- DHCP
- SNMP
- SSH
- Telnet

### Endereçamento IP (Semana 3 e 4)

- IPv4
- IPv6
- Subnetting
- CIDR
- VLSM
- DHCP
- Conceitos de firewall
- NAT

## Linux

### Arquitetura do sistema Linux (Semana 5)

- Kernel e espaço do usuário
- Modos de operação (usuário e kernel)
- Sistemas de inicialização (SysVinit, systemd)

### Gerenciamento de processos e memória (Semana 6)

- Estruturas de dados de processos
- Comandos de controle de processos (ps, top, kill)
- Gerenciamento de memória (swap, caches)

### Gerenciamento de usuários e grupos (Semana 7)

- Criação e gerenciamento de usuários
- Configuração de grupos e permissões
- Autenticação de usuários (PAM, LDAP)

### Gerenciamento de pacotes (Semana 8)

- Gerenciadores de pacotes (apt, yum, dnf)
- Instalação e remoção de pacotes

### Dispositivos e sistemas de arquivos (Semana 9)

- Estrutura do sistema de arquivos (FHS)
- Montagem e desmontagem de sistemas de arquivos
- Sistemas de arquivos comuns (ext4, XFS, Btrfs)
- Permissões e propriedade de arquivos
- Gerenciamento de discos e partições (fdisk, parted)
- RAID e LVM para gerenciamento de armazenamento

### Ferramentas de manipulação e análise de Texto (Semana 10)

- awk
- cut
- grep/egrep
- sed
- sort
- tee
- tr
- uniq
- wc

### Ferramentas de manipulação, cópia, compressão e análise de arquivos (Semana 11)

- rsync
- find
- cat
- less
- more
- diff/sdiff
- gzip
- bzip2
- xz
- tar
- zip/unzip
- file

### Ferramentas de análise de sistema (Semana 12)

- Comandos de monitoramento de sistema (vmstat, iostat)
- Ferramentas de análise de desempenho (sar, perf)
- Ferramentas de análise de uso de disco (du, df)
- Ferramentas de análise de uso de memória (free)
- Ferramentas de análise de uso de CPU (mpstat)
- Ferramentas para análise de logs (journalctl, dmesg)
- Ferramentas de análise de processos (htop, top, strace, lsof)
- Ferramentas de análise de uso de rede (iftop, nload, iptraf,nmap)
- Diagnóstico de problemas de rede (ping, traceroute, netstat)
- Logs de sistema e logs de rede

### Configuração básica de rede (Semana )

- Configuração de interfaces de rede
- Configuração de serviços de rede (SSH, FTP, HTTP)
- Configuração de roteamento estático e dinâmico
- Configuração de tabelas de roteamento e ARP
- Configuração de hosts e resolução de nomes (DNS, /etc/hosts)

### Segurança em sistemas Linux (Semana )

- Controle de acesso (sudo, PAM)
- Configuração de firewall (iptables, firewalld)
- Práticas de segurança para serviços (SSH, FTP)
- Atualizações de segurança e gerenciamento de patches
- Criptografia de arquivos e comunicações (GPG, SSL/TLS)
- Monitoramento de segurança (auditd, SELinux, AppArmor)

### Servidores (Semana )

- Configuração de servidores web (Apache, Nginx, Caddy)
- Configuração de servidores de banco de dados (MySQL, PostgreSQL)
- Configuração de servidores de aplicativos (Tomcat, JBoss)
- Configuração de servidores de arquivos (Samba, NFS)
- Configuração de proxies e balanceadores de carga (Nginx, HAProxy)

## Shell script (Semana )

- Estrutura de scripts (loops, condicionais)
- Manipulação de arquivos e diretórios
- Uso de variáveis e funções
- Uso de expressões regulares
- curl e wget para automação de tarefas
- jq e yq para manipulação de JSON e YAML

## Cloud Computing (Semana )

- [AWS básico](https://aws.amazon.com/pt/certification/certified-cloud-practitioner/#exam-prep)
- [Azure básico](https://learn.microsoft.com/pt-br/training/courses/az-900t00#course-syllabus)

## Configurations Management (Semana )

- JSON
- YAML
- Conceitos de CM
- Ansible

## IaC (Infrastructure as Code) (Semana )

- Conceitos de IaC
- Terraform

## Containers

### Como um container funciona por baixo dos panos (Semana )

- chroot
- namespaces (pid, net, ipc, mnt, uts)
- cgroups
- Linux capabilities
- Overlay filesystem
- Seccomp

### Docker (Semana )

- O que é o Docker?
- Containers vs VMs
- Container runtime
- Instalação do Docker
- Estrutura de um container
- Administrar containers
- Limitar recursos (CPU, memória, I/O) de um container
- Volumes e bind mounts
- Redes no Docker
- Estrutura de uma imagem
- Criar imagens customizadas
- Docker registry e Docker Hub
- Docker Compose
- Docker secrets
- Segurança no Docker (limitação de privilégios, uso de imagens confiáveis)

## Git (Semana )

- O que é o Git?
- Instalação e configuração do Git
- Inicialização de um repositório
- Adicionar e commitar arquivos
- Branches
- Merge e rebase
- Resolução de conflitos
- Tags
- Stash
- Reset e revert
- Cherry-pick
- Reflog
- Submódulos
- Git LFS
- Git Flow, Git SemVer
- Hooks: pre-commit, pre-push, post-receive
- Conceitos do GitHub, GitLab, Bitbucket

## Teoria DevOps

### Livros para leitura

- [O Projeto Fênix](https://www.google.com/search?q=projeto+fenix&sca_esv=b6652a83a08e5308)
- [O Projeto Unicórnio](https://www.google.com/search?q=O+projeto+unic%C3%B3rnio+livro&sca_esv=b6652a83a08e5308&sxsrf)
- [Manual de DevOps](https://www.google.com/search?q=manual+de+devops&sca_esv=b6652a83a08e5308)
- [DevOps na prática - entrega de software confiável e automatizada](https://www.casadocodigo.com.br/products/livro-devops)
- [Como se faz DevOps](https://www.casadocodigo.com.br/products/livro-como-se-faz-devops)
- [Engenharia de Confiabilidade do Google](https://elven.works/livro-sre-google/)
