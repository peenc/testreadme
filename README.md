# 💳 Capiwallet

Sistema desenvolvido como Trabalho de Conclusão de Curso (TCC) por **Pedro Nunes Cardoso** e **Lennon Ferreira Machado**, com o objetivo de modernizar e automatizar o controle de acesso e consumo no restaurante universitário.

## 🎯 Objetivo

Digitalizar e otimizar o processo de compra e utilização de tickets no restaurante universitário, através de uma **carteira virtual integrada**, facilitando o uso por parte dos alunos e o gerenciamento pela equipe administrativa.

---

## 🛠️ Tecnologias Utilizadas

<div style="display: flex; gap: 10px;">
  
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🔐 Autenticação e Segurança

- Autenticação baseada em **HttpSession**
- Controle de acesso por **roles (usuário, administrador, operador)**
- Redirecionamentos e filtros com base nas permissões
- Proteção contra acesso não autorizado em páginas críticas

---

## 🧱 Arquitetura

- Projeto em **arquitetura monolítica**
- Camadas bem definidas:
  - `Controller`
  - `Service`
  - `Repository`
  - `Entity`
- Utilização de **Spring Data JPA** para abstração do acesso ao banco

---

## 📦 Funcionalidades

- [x] Cadastro e login de usuários
- [x] Compra de tickets digitalmente com saldo da carteira
- [x] Visualização de saldo e histórico de tickets
- [x] Geração de QR Code para validação no restaurante
- [x] Painel administrativo para gestão de vendas e permissões

---

## 🖼️ Imagens do Sistema

> Substitua os caminhos abaixo pelas suas próprias imagens (por exemplo, `docs/login.png`).

### 🔑 Tela de Login  
![Login](docs/login.png)

### 👛 Página da Carteira  
![Carteira](docs/carteira.png)

### 🍽️ Página do Bandejão  
![Bandejão](docs/bandejao.png)

---

## 📐 Diagramas

> Também insira os arquivos de imagem dos diagramas aqui.

### 📌 Diagrama de Casos de Uso  
![Casos de Uso](docs/casos_de_uso.png)

### 🧩 Diagrama de Classes  
![Classes](docs/diagrama_classes.png)

---

## 👨‍💻 Autores

- Pedro Nunes Cardoso  
- Lennon Ferreira Machado  

---

## ⚠️ Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos.  
**É proibida sua reprodução, distribuição ou uso comercial sem autorização dos autores.**
