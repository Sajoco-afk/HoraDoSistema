# 🕐 Hora do Sistema

Um projeto simples desenvolvido em **Java** para demonstrar como obter e exibir a **data e hora atual do sistema**, utilizando a classe `Date`.

---

## 📌 Sobre o Projeto

O programa cria um objeto da classe `Date`, responsável por obter a **data e hora atual configuradas no sistema operacional**.<br>

Em seguida, essas informações são exibidas no terminal utilizando o método `System.out.println()`.<br>

Este projeto faz parte dos meus estudos de **Java e programação**, sendo um exercício introdutório para praticar conceitos fundamentais da linguagem.<br>

---

## 🛠️ Tecnologias Utilizadas

- ☕ **Java**<br>
- 📦 **Maven**<br>
- 💻 **NetBeans IDE**<br>

---

## 📂 Estrutura do Projeto

A principal classe do projeto é:

   text<br>
HoraDoSistema<br>
└── main()<br>
 
O método main() é responsável pela execução do programa.

## 💻 Funcionamento

### 1. Importação da classe Date

A classe Date é importada da biblioteca padrão do Java:

import java.util.Date;<br>

### 2. Criação do objeto

No método main(), é criado um objeto Date:

Date relogio = new Date();

Esse objeto armazena a data e hora atual do sistema.

### 3. Exibição no terminal

Depois, o programa utiliza System.out.println() para exibir as informações:

System.out.println("A hora do sistema é");<br>
System.out.println(relogio.toString());

## ▶️ Exemplo de Execução

Ao executar o programa, o terminal apresentará algo semelhante a:

A hora do sistema é<br>
Wed Aug 12 22:30:15 BRT 2026

Observação: o resultado varia de acordo com a data, hora e configuração regional do computador.

## 🎯 Objetivo do Projeto

Este exercício tem como objetivo praticar:

📌 Declaração de classes;<br>
📌 Método main;<br>
📌 Criação de objetos;<br>
📌 Importação de bibliotecas Java;<br>
📌 Utilização da classe Date;<br>
📌 Impressão de informações no console;<br>
📌 Conceitos básicos de Programação Orientada a Objetos.<br>

## 📚 Conceitos Estudados

Durante o desenvolvimento deste projeto foram trabalhados conceitos fundamentais de Java, como:

Classes<br>
Objetos<br>
Métodos<br>
Bibliotecas<br>
Importação de classes<br>
Entrada e saída de informações<br>
Programação Orientada a Objetos (POO)<br>
🚀 Como Executar<br>
Pré-requisitos<br>

Para executar o projeto, é necessário ter instalado:

☕ Java JDK<br>
📦 Apache Maven<br>
💻 NetBeans IDE ou outra IDE compatível com projetos Maven<br>
Executando o projeto<br>
Clone este repositório:<br>
git clone URL_DO_REPOSITORIO<br>
Abra o projeto no NetBeans.<br>
Aguarde o Maven carregar as dependências.<br>
Execute a classe:<br>
HoraDoSistema.java<br>
Confira o resultado no terminal.<br>

## 👨‍💻 Autor

Samuel Jorge Covalski

Projeto desenvolvido para fins de estudo e aprendizado em Java.
