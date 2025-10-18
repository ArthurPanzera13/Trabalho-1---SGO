# 🏅 Sistema de Gestão das Olimpíadas (SGO)

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

# 👥 Histórias de Usuário — Sistema de Gestão das Olimpíadas (SGO)

As histórias de usuário abaixo foram elaboradas com base na documentação oficial do trabalho **Sistema de Gestão das Olimpíadas (SGO)**, considerando as regras de negócio e os requisitos descritos no enunciado do professor João Paulo Aramuni.  
O sistema tem como objetivo representar, por meio de modelagem UML, os principais processos de gerenciamento das Olimpíadas — **sem implementação de código**.

---

### **US01 – Cadastrar Competição**
**Como** organizador das Olimpíadas,  
**quero** cadastrar novas competições informando modalidade, data, horário, local e atletas participantes,  
**para** que o sistema registre oficialmente os eventos e permita o controle das inscrições e resultados.

---

### **US02 – Inscrever Atleta**
**Como** atleta representante de um país,  
**quero** me inscrever em uma ou mais competições específicas,  
**para** poder competir nas modalidades em que estou qualificado e representar meu país.

---

### **US03 – Alocar Local de Competição**
**Como** administrador do sistema,  
**quero** alocar locais para as competições de modo que não ocorram conflitos de horário,  
**para** garantir que cada evento aconteça em um espaço disponível e adequado.

---

### **US04 – Registrar Resultados**
**Como** juiz ou organizador de competição,  
**quero** registrar o resultado das provas, informando os três primeiros colocados,  
**para** atualizar o sistema com as medalhas conquistadas por cada atleta e país.

---

### **US05 – Gerar Relatório de Medalhas**
**Como** comitê organizador,  
**quero** gerar relatórios consolidados de medalhas por país,  
**para** acompanhar o desempenho geral das nações e divulgar o quadro oficial das Olimpíadas.

---

### **US06 – Consultar Competições por Modalidade**
**Como** visitante ou jornalista,  
**quero** consultar as competições filtrando por modalidade e data,  
**para** visualizar as informações dos eventos de interesse e planejar minha cobertura ou participação.

---

### **US07 – Consultar Atletas por País**
**Como** membro do comitê ou organizador,  
**quero** visualizar os atletas cadastrados de cada país,  
**para** ter um panorama geral das delegações participantes e suas respectivas inscrições.

---

### **US08 – Atualizar Dados de Competição**
**Como** organizador,  
**quero** editar informações de uma competição antes de sua realização (como horário, local ou participantes),  
**para** corrigir imprevistos e manter as informações atualizadas.

---

### **US09 – Cancelar ou Reagendar Competição**
**Como** administrador,  
**quero** cancelar ou reagendar competições em caso de imprevistos,  
**para** reorganizar o cronograma de provas sem comprometer outras modalidades.

---

### **US10 – Emitir Relatórios Estatísticos**
**Como** membro do comitê técnico,  
**quero** emitir relatórios estatísticos com o número de competições, atletas e medalhas,  
**para** avaliar o desempenho geral e auxiliar em futuras edições dos jogos.

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
