# Portfolio
## 📖 Descrição do Projeto
Este projeto consiste no desenvolvimento de um **website de portfólio profissional** com o objetivo de apresentar de forma moderna, responsiva e acessível a trajetória, habilidades, projetos e formas de contato. 

O site contará com:  

- **Sobre Mim** – Apresentação em português e inglês, destacando formação, área de atuação, interesses e objetivos profissionais.  
- **Projetos** – Linha do tempo de projetos, com nome, descrição, tecnologias utilizadas, link para o repositório e imagens/GIFs demonstrando o funcionamento.  
- **Experiências** – Registro de experiências profissionais, estágios, freelas e participações em eventos ou projetos.  
- **Contato** – Ícones clicáveis e formulário funcional para envio de mensagens por e-mail.  

Os responsáveis pelo desenvolvimento do projeto são:  
- **Arthur Henrique Teixeira e Silva Bacelete**
- [Portfolio](https://portfolio-new-git-main-baceletes-projects.vercel.app)
- **Gabriel Nogueira Vieira Resende**
- [Portfolio](https://portfolio-blond-kappa-81.vercel.app)
- **Kaio Souza Oliveira Mayer**
- [Portfolio](https://my-portfolio-dev-xi.vercel.app/about)
- **Mateus Rodrigues Costa**
- [Portfolio](https://portifolio-git-main-mateus-projects-b5111fc2.vercel.app)
## 🛠️ Tecnologias Utilizadas
- Java 21
- Spring Boot 3.5.4
- Angular
- Figma
- GitHub e Git
- Docker
## Como Rodar o projeto
  Você precisará ter um e-mail Google ativo e com a autenticação em duas etapas ativada.
  ```.env 
  EMAIL=seu email compelto 
  APP_PASSWARD=Sua cheve de app do google
```
Esse arquvio deve estra preseten no root do seu projeto
# 🐳 Guia Básico de Docker com .env

Este guia traz os comandos essenciais do Docker para **criar, rodar e gerenciar a aplicação**.
## 📌 1. Verificar se o Docker está instalado
```bash
docker --version
docker info
```

---

## 📌 2. Rodar a aplicação
```bash
docker compose up -d
```

---

## 📌 3. Listar containers
```bash
docker ps        # Containers em execução
docker ps -a     # Todos os containers (inclui os parados)
```

---

## 📌 4. Parar os containers
```bash
docker compose down
```
Adicione a flag -v para remover os volumes, se necessário.

## 🎨 Protótipos e Telas
![Protótipo Home](Img/Home.png)  
![Protótipo Experience](Img/Experience.png)  
![Protótipo Project](Img/Projects.png)  
![Protótipo Contact](Img/Contact.png)  



