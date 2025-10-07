# randstad-ecommerce

# 💼 Projeto E-commerce – Desafio DIO (Banco de Dados)

Este repositório contém o projeto de **refinamento do modelo conceitual de e-commerce**, desenvolvido no **MySQL Workbench** como parte do Bootcamp [nome do bootcamp] da **Digital Innovation One (DIO)**.

---

## 🧠 Objetivo do projeto
Refinar o modelo de banco de dados proposto no desafio anterior, aplicando boas práticas de modelagem e criando as relações de forma lógica no **MySQL Workbench**.

---

## 🏗️ Estrutura do projeto
- **ecommerce.mwb** → Modelo completo criado no MySQL Workbench.  
- **projeto-ecommerce.sql** → Script SQL gerado a partir do modelo.  
- **diagrama-ecommerce.png** → Imagem do modelo EER (para visualização rápida).  

---

## 🔍 Entidades e relacionamentos principais
- **Cliente** → cadastra, realiza pedidos.  
- **Pedido** → possui itens, status, data e valor total.  
- **Produto** → pertence a uma categoria e pode estar em vários pedidos.  
- **Pagamento** → relacionado ao pedido.  
- **Entrega** → vinculada ao pedido.  


## 🖼️ Diagrama EER
![Diagrama EER](diagrama-ecommerce.png)

---

## 💡 Ferramentas utilizadas
- MySQL Workbench  

---

## ✍️ Autor
Projeto desenvolvido por **Álvaro Gonçalves Rodrigues**, como parte do bootcamp da [Digital Innovation One](https://www.dio.me/).

