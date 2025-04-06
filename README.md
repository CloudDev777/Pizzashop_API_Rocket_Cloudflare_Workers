# 🍕 pizza.shop API

Back-end de um app de delivery de comida (inspirado no iFood/Uber Eats), desenvolvido com **TypeScript**, **Drizzle** e **ElysiaJS**.

> 🔥 Este projeto foi desenvolvido para ser agnóstico ao ambiente de execução. Isso significa que ele pode rodar no **Bun**, **Node.js**, **Cloudflare Workers** ou qualquer runtime compatível com APIs Web padrão.

---

## 🚀 Executando o projeto

Este projeto utiliza o **Docker** para configurar o banco de dados.

### Instalado para rodar a aplicação:
```bash
git clone https://github.com/joaomjbraga/pizzashop-API_Rocket.git
cd pizzashop-API_Rocket
bun i                 # Instala as dependências
docker compose up -d  # Inicia os containers do banco de dados
bun migrate           # Executa as migrações do banco
bun seed              # Popula o banco com dados fictícios
bun dev               # Inicia a aplicação em modo de desenvolvimento
