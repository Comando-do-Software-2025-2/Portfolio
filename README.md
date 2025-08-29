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
- [Portfolio](https://link-que-sera-aberto.com)
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

Este guia traz os comandos essenciais do Docker para **criar, rodar e gerenciar uma aplicação**.
## 📌 1. Verificar se o Docker está instalado
```bash
docker --version
docker info
```

---

## 📌 2. Baixar uma imagem
```bash
docker pull <nome-da-imagem>
# Exemplo:
docker pull ubuntu:20.04
```

---

## 📌 3. Listar imagens disponíveis localmente
```bash
docker images
```

---

## 📌 4. Criar e rodar um container
```bash
docker run -it <nome-da-imagem> /bin/bash
# Exemplo:
docker run -it ubuntu:20.04 /bin/bash
```

---

## 📌 5. Listar containers
```bash
docker ps        # Containers em execução
docker ps -a     # Todos os containers (inclui os parados)
```

---

## 📌 6. Parar, iniciar e remover containers
```bash
docker stop <id-ou-nome-do-container>
docker start <id-ou-nome-do-container>
docker rm <id-ou-nome-do-container>
```

---

## 📌 7. Remover imagens
```bash
docker rmi <id-ou-nome-da-imagem>
```

---

## 📌 8. Construir imagem a partir de um Dockerfile
```bash
docker build -t <nome-da-imagem>:<tag> .
# Exemplo:
docker build -t minha-app:1.0 .
```

---

## 📌 9. Rodar um container mapeando porta
```bash
docker run -d -p 8080:80 <nome-da-imagem>
# Exemplo:
docker run -d -p 8080:80 minha-app:1.0
```

## 🎨 Protótipos e Telas
![Protótipo Home](Img/Home.png)  
![Protótipo Experience](Img/Experience.png)  
![Protótipo Project](Img/Projects.png)  
![Protótipo Contact](Img/Contact.png)  



