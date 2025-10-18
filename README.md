"# 🏅 Sistema de Gestão das Olimpíadas (SGO)

## 🧭 Introdução

O **Sistema de Gestão das Olimpíadas (SGO)** tem como objetivo modelar e representar, de forma estruturada, os principais processos envolvidos na realização dos Jogos Olímpicos.  
A proposta é criar uma **modelagem UML completa**, que descreva as entidades, relações, fluxos e camadas de arquitetura do sistema, sem necessidade de implementação em código.

O sistema busca representar de maneira clara a interação entre os **atores (organizadores, atletas, juízes, comitê)** e as funcionalidades principais, como cadastro de competições, inscrição de atletas, registro de resultados e geração de relatórios de medalhas.

A modelagem do SGO contempla os seguintes diagramas:
- **Diagrama de Caso de Uso** – identifica os atores e suas interações com o sistema.  
- **Diagrama de Classes** – define as entidades, atributos e relacionamentos do domínio.  
- **Diagrama de Pacotes** – organiza as classes em camadas e módulos lógicos.  
- **Diagrama de Componentes** – representa a estrutura modular do sistema.  
- **Diagrama de Implantação** – mostra o ambiente físico e os elementos de hardware e software.

A arquitetura segue o padrão **em camadas (MVC + Service + Repository)**, com o objetivo de garantir **organização, coesão e clareza de responsabilidades** entre as partes do sistema.

---

## 👥 Histórias de Usuário

### **US01 – Cadastrar Competição**
**Como** organizador das Olimpíadas,  
**quero** cadastrar novas competições informando nome da modalidade, data, horário, local e atletas participantes,  
**para** que o sistema registre oficialmente os eventos e permita o controle das inscrições e resultados.

---

### **US02 – Inscrever Atleta**
**Como** atleta representante de um país,  
**quero** me inscrever em uma ou mais competições específicas,  
**para** poder competir nas modalidades em que estou qualificado e representar meu país nas provas.

---

### **US03 – Alocar Local de Competição**
**Como** administrador do sistema,  
**quero** alocar locais para as competições garantindo que não haja conflitos de horários,  
**para** assegurar que cada evento ocorra em um espaço disponível e adequado, evitando sobreposições.

---

### **US04 – Registrar Resultados**
**Como** juiz ou organizador de competição,  
**quero** registrar os resultados das provas informando o vencedor e os classificados em segundo e terceiro lugar,  
**para** manter o histórico das competições e gerar relatórios de desempenho.

---

### **US05 – Gerar Relatório de Medalhas**
**Como** comitê organizador,  
**quero** gerar um relatório consolidado de medalhas por país (ouro, prata e bronze),  
**para** acompanhar o desempenho geral das nações e divulgar o quadro oficial das Olimpíadas.

---

## 🧩 Escopo do Projeto

Este projeto se restringe à **modelagem conceitual e estrutural** do sistema, utilizando a UML (Unified Modeling Language) para representar os elementos e suas interações.  
Não há desenvolvimento de código ou implementação de sistema funcional, sendo o foco a **documentação visual e conceitual** da aplicação.

Os diagramas produzidos têm como finalidade:
- Compreender a estrutura lógica do sistema.  
- Demonstrar o relacionamento entre entidades e camadas.  
- Fornecer uma visão arquitetural clara e organizada.  

---

## 📁 Estrutura do Repositório

**Estrutura do projeto:**
``` 
│
├── README.md
├── diagramas/
│ ├── diagrama-de-caso-de-uso.drawio
│ ├── diagrama-de-classes.drawio
│ ├── diagrama-de-pacotes.drawio
│ ├── diagrama-de-componentes.drawio
│ └── diagrama-de-implantacao.drawio
└── imagens/
├── diagrama-de-caso-de-uso.png
├── diagrama-de-classes.png
├── diagrama-de-pacotes.png
├── diagrama-de-componentes.png
└── diagrama-de-implantacao.png
```
---


## 🧠 Observações

- Este trabalho é **conceitual e não inclui implementação em código**.  
- Todos os diagramas foram desenvolvidos conforme os **requisitos descritos no enunciado do trabalho**.  
- A modelagem segue as **boas práticas de engenharia de software**, com foco em **clareza, coesão e organização arquitetural**.  
- O documento é parte do **Trabalho 1 – Projeto de Software**, sob orientação do professor **João Paulo Aramuni**.

---
