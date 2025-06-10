# 🔐 Projeto de Segurança de Rede – Ambiente Corporativo

Este repositório documenta a implementação de um ambiente de **segurança de rede corporativa**, desenvolvido em um servidor físico Linux com foco em **visibilidade, controle e proteção da infraestrutura**.

---

## 📘 Visão Geral

O projeto foi criado para migrar serviços de uma infraestrutura de testes para um servidor dedicado, utilizando ferramentas modernas como **Docker**, **Prometheus**, **Grafana**, **Pi-hole** e **OpenVPN Access Server**.

A proposta é construir um ambiente **modular, documentado e escalável**, com foco em boas práticas de segurança e monitoramento.

---

## 🎯 Objetivos

- Migrar serviços de uma infraestrutura de testes para ambiente dedicado.
- Monitorar métricas da rede, serviços e desempenho com Prometheus + Grafana.
- Bloquear anúncios e rastreamento via Pi-hole.
- Criar um acesso remoto seguro com OpenVPN-AS.
- Utilizar Docker para facilitar manutenção e escalabilidade.
- Documentar o processo como portfólio técnico.

---

## 🧰 Tecnologias e Ferramentas Utilizadas

| Categoria         | Ferramenta / Equipamento               |
|------------------|----------------------------------------|
| Servidor         | Linux Server (bare metal)              |
| Contêineres      | Docker, Docker Compose                 |
| Monitoramento    | Prometheus, Grafana                    |
| DNS Seguro       | Pi-hole                                |
| VPN              | OpenVPN Access Server (via Docker)     |
| Infraestrutura   | Equipamentos de rede padrão corporativo|

---

## 📌 Status Atual

- ✅ Infraestrutura configurada com IP fixo e acesso remoto
- ✅ Serviços migrados e funcionando em containers
- ✅ Monitoramento básico e dashboards iniciais prontos
- 🔄 Melhorias em andamento: alertas, automações e backups

---

## 📁 Estrutura da Documentação

Cada diretório contém instruções detalhadas para replicação:

