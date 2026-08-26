# 🚀 Portfólio de Servidor Ubuntu com segurança, isolamento de aplicações e alta disponibilidade.

Este repositório contém a infraestrutura e as configurações para a publicação segura de uma aplicação web, aplicando boas práticas de segurança e isolamento.

---

## 📐 Diagrama de Arquitetura

![Diagrama da Arquitetura](./Diagrama%20de%20Arquitetura.png)

## 🏛️ Decisões de Arquitetura (ADRs)

- Ubuntu Server 24.04 LTS como SO por sua estabilidade de longo prazo garantida
- Docker + Docker Compose para isolamento e padronização
- Nginx para isolar a porta interna da aplicação com proxy reverso
- SSH por chaves e controle de portas com UFW para evitar ataques e portas sensíveis 

## 🛡️ Evidências de Funcionamento e Segurança

- Docker rodando e UFW ativo
![Diagrama da Arquitetura](./Diagrama%20de%20Arquitetura.png)
- Teste de bloqueio de porta
![Diagrama da Arquitetura](./bloqueio%20de%20porta.png)
- Validação do Nginx
![Diagrama da Arquitetura](./Proxy%20Reverso.png)
- Validação do SSH

![Diagrama da Arquitetura](./SSH.png)

- Arquivo do proxy reverso Nginx funcionando
![Diagrama da Arquitetura](./UFW.png)
