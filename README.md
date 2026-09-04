# ⚡ Nexa Sistemas — Desafio Prático Docker (Estudo)

> 📌 **Aviso:** Este projeto consiste em um **exercício prático para fins puramente acadêmicos e de estudo**, com o objetivo de consolidar fundamentos de conteinerização com Docker e configuração do servidor web Nginx.

A proposta do laboratório simula uma demanda real para uma empresa fictícia (**Nexa Sistemas**): empacotar uma página institucional estática dentro de um container Docker, mapeando portas de comunicação e gerenciando o ciclo de vida do container via CLI.

---

## 🎯 Objetivos de Aprendizagem

* Compreender a estrutura e comandos básicos de um `Dockerfile` (`FROM`, `COPY`).
* Gerar imagens customizadas utilizando o Nginx como base (`docker build`).
* Executar containers isolados com mapeamento de portas externas (`docker run -p`).
* Gerenciar paradas, inicializações e remoções de instâncias (`docker stop` / `docker rm`).
* Praticar versionamento com Git e documentação no GitHub.

---

## 📁 Estrutura do Projeto

```text
nexa-docker/
├── html/
│   └── index.html      # Interface estática estilizada no padrão Notion
├── Dockerfile          # Instruções de montagem da imagem Nginx
└── README.md           # Documentação e guia de estudo
