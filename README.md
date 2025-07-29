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
- Controle de acesso por **roles (usuario, administrador, tecnico)**
- Redirecionamentos e filtros com base nas permissões
- Proteção contra acesso não autorizado em páginas críticas

---

## 🧱 Arquitetura

- Projeto em **arquitetura monolítica**
- Camadas bem definidas:
  - `Controller`
  - `Service`
  - `Repository`
  - `Model`
- Utilização de **Spring Data JPA** para abstração do acesso ao banco

---
## 📦 Funcionalidades

### 👤 Usuário
- [x] Cadastro e login de usuários
- [x] Edição de dados de perfil (nome, e-mail, senha e foto)
- [x] Recuperação de senha por e-mail com link de alteração
- [x] Disparo automático de e-mails informativos (compra de tickets, saldo baixo, etc.)

### 🎫 Tickets
- [x] Compra de tickets de forma presencial ou digital
- [x] Integração com a **API Pix do Banco do Brasil** para pagamentos
- [x] Visualização de saldo de tickets e histórico de uso
- [x] Geração de **QR Codes** para autenticação no restaurante

### 🛠️ Administração
- [x] Painel administrativo com gestão de vendas e permissões
- [x] Geração automática de **relatórios diários** de vendas
- [x] Acompanhamento de atividades do sistema e dos usuários

### 📱 Interface e experiência
- [x] Interface responsiva e intuitiva para acesso via celular e desktop
- [x] Alertas visuais e por e-mail sobre status de tickets e ações importantes


---

## 🖼️ Imagens do Sistema


### 🔑 Tela de Login  
<img width="1919" height="961" alt="Image" src="https://github.com/user-attachments/assets/2b18fad3-8b8e-424b-89e3-40524f798bbe" />

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
