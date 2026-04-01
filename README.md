# 📦 Classe Produto — Java OOP

Projeto desenvolvido para praticar os fundamentos de **Orientação a Objetos em Java**. A classe `Produto` representa um item com nome e preço, seguindo boas práticas de encapsulamento.

---

## 🗂️ Estrutura do projeto

```
├── Produto.java   # Classe que define os atributos e comportamentos do produto
└── Cabelo.java    # Classe principal com o método main para testar a classe Produto
```

---

## ⚙️ Funcionalidades

- Armazenar **nome** e **preço** de um produto
- Consultar e definir os dados via **getters** e **setters**
- Aplicar **desconto percentual** no preço com o método `aplicaDesconto()`

---

## 📚 Conceitos praticados

- Orientação a Objetos (POO)
- Encapsulamento com modificador `private`
- Métodos getters e setters
- Parâmetros e tipos de retorno
- Diferença entre atributos e variáveis locais
- Uso do `this` para referenciar atributos da classe

---

## 🚀 Como usar

```java
Produto cabelo = new Produto();
cabelo.setNome("Shampoo");
cabelo.setPreco(5.00);

System.out.println("Preço sem desconto: " + cabelo.getPreco()); // 5.0
cabelo.aplicaDesconto(10); // aplica 10% de desconto
System.out.println("Preço com desconto: " + cabelo.getPreco()); // 4.5
```

---

## 🖥️ Saída esperada

```
Produto de cabelo: Shampoo
Preço sem desconto: 5.0
Preço com desconto: 4.5
Produto de cabelo: Óleo desengordurante
Preço sem desconto: 95.0
Preço com desconto: 52.25
```

---

## 🛠️ Tecnologias

- Java

---

## 👤 Autor

Feito com 💙 durante os estudos de Java.
