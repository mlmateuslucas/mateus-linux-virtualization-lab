# Mateus Linux Virtualization & AI Lab

**Proxmox VE | Debian Linux | Docker | n8n | Artificial Intelligence**

## Sobre o projeto

Este repositório documenta o planejamento e o desenvolvimento de um laboratório pessoal de infraestrutura de TI, virtualização, automação de processos e inteligência artificial.

O objetivo principal é construir uma plataforma inteligente de atendimento empresarial, integrando WhatsApp, Evolution API, Chatwoot, n8n, Google Workspace e modelos locais de inteligência artificial executados com Ollama.

A infraestrutura será hospedada em um ambiente próprio, utilizando Proxmox VE e máquinas virtuais Debian Linux.

## 1. Hardware disponível

| Componente | Especificação |
|---|---|
| Processador | Intel Core i5-7200U |
| Núcleos / Threads | 2 / 4 |
| Frequência | 2,5 GHz / até 3,1 GHz |
| Memória RAM | 16 GB DDR4 |
| Armazenamento principal | NVMe 250 GB |
| Armazenamento secundário | HD 1 TB |
| GPU | Intel HD Graphics 620 |
| Virtualização | Intel VT-x |

## 2. Infraestrutura planejada

- Proxmox VE como hipervisor.
- Debian 12 como sistema operacional dos servidores virtuais.
- Docker e Docker Swarm para gerenciamento de containers.
- Portainer para administração visual.
- Traefik para proxy reverso e publicação dos serviços.
- PostgreSQL para armazenamento de dados.
- PGVector para armazenamento e recuperação vetorial.

## 3. Projeto principal: Central Inteligente de Atendimento com IA

Desenvolver uma solução integrada de atendimento automatizado, armazenamento de conversas e recuperação de conhecimento empresarial.

### Tecnologias principais

- n8n: automação e orquestração de processos.
- Evolution API: integração com WhatsApp.
- Chatwoot: gerenciamento de atendimentos e conversas.
- Google Drive: armazenamento de documentos empresariais.
- Google Docs: documentação e gestão do conhecimento.
- PostgreSQL: persistência de dados e histórico.
- PGVector: armazenamento vetorial.
- Ollama: execução local de modelos de IA.
- RAG: recuperação de informações documentais para geração de respostas.

### 3.1 Integração WhatsApp

- Recebimento de mensagens.
- Envio de mensagens.
- Integração por webhooks.
- Identificação e organização dos contatos.
- Integração com Chatwoot.
- Registro das interações.

### 3.2 Integração com Google Workspace

- Conexão com Google Drive.
- Consulta de documentos empresariais.
- Integração com Google Docs.
- Extração e processamento de conteúdo.
- Atualização da base de conhecimento.

### 3.3 Armazenamento e consulta de conversas

- Armazenamento do histórico de mensagens.
- Organização por contato e atendimento.
- Persistência em banco de dados.
- Recuperação de conversas anteriores.
- Consultas sobre atendimentos realizados.

### 3.4 Inteligência Artificial e RAG

- Instalação e configuração do Ollama.
- Execução de modelos locais de linguagem.
- Geração de embeddings.
- Integração com PostgreSQL e PGVector.
- Indexação da documentação empresarial.
- Recuperação semântica de informações.
- Geração de respostas fundamentadas nos documentos.

### 3.5 Atendimento automatizado

- Interpretação das mensagens recebidas.
- Consulta à base de conhecimento.
- Geração de respostas com IA.
- Envio das respostas pelo WhatsApp.
- Registro das interações.
- Encaminhamento para atendimento humano quando necessário.

## 4. Arquitetura das máquinas virtuais

**VM 01 — Aplicações e Automação**
- Debian 12
- Docker
- Portainer
- Traefik
- n8n
- Evolution API
- Chatwoot

**VM 02 — Banco de Dados e Conhecimento**
- Debian 12
- PostgreSQL
- PGVector
- Armazenamento de histórico e vetores.

**VM 03 — Administração e Monitoramento**
- Debian 12
- SSH
- Administração Linux
- Monitoramento
- Testes de rede.

**VM 04 — Inteligência Artificial**
- Debian 12
- Ollama
- Modelos locais de linguagem
- Embeddings
- Processamento RAG.

A distribuição será ajustada de acordo com a capacidade física do equipamento e os recursos disponíveis.

## 5. Roadmap de desenvolvimento

1. Preparação da infraestrutura física.
2. Instalação do Proxmox VE.
3. Configuração de armazenamento e rede.
4. Criação das máquinas virtuais Debian.
5. Implantação do Docker e Portainer.
6. Configuração do Traefik.
7. Implantação do n8n.
8. Integração Evolution API e WhatsApp.
9. Implantação e integração do Chatwoot.
10. Integração Google Drive e Google Docs.
11. Armazenamento e consulta das conversas.
12. Implantação PostgreSQL e PGVector.
13. Configuração do Ollama.
14. Desenvolvimento da base de conhecimento empresarial.
15. Implementação do RAG.
16. Desenvolvimento das respostas automáticas com IA.
17. Testes, segurança e documentação.

## 6. Objetivos de aprendizagem

- Administração de servidores Linux.
- Virtualização com Proxmox VE.
- Gerenciamento de containers.
- Administração de redes e serviços.
- Automação de processos.
- Integração de APIs.
- Administração de bancos de dados.
- Inteligência artificial generativa.
- Modelos locais de linguagem (LLMs).
- RAG e bancos de dados vetoriais.
- Integração com Google Workspace.
- Documentação técnica e infraestrutura.

## Status do projeto

**PLANEJAMENTO**

O laboratório e a plataforma de atendimento inteligente estão em fase de planejamento. As instalações, integrações e funcionalidades serão documentadas conforme forem implementadas e testadas.

---

**Autor:** Mateus Lucas

**Área:** Infraestrutura e Operações de TI | Linux | Virtualização | Automação | Inteligência Artificial
