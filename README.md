# ⚡ Nexa Sistemas — Docker & Nginx

Ambiente conteinerizado para o site institucional da **Nexa Sistemas**, desenvolvido como parte de uma atividade prática de introdução e fixação de **Docker**.

A aplicação entrega uma interface estática responsiva, inspirada no design minimalista e analógico do **Notion**, servida por um servidor web **Nginx** executado isoladamente em um container Docker.

---

## 📁 Estrutura de Arquivos

```text
nexa-docker/
├── html/
│   └── index.html      # Página institucional (Design Notion-style)
├── Dockerfile          # Instruções de montagem da imagem Nginx
└── README.md           # Documentação do projeto
