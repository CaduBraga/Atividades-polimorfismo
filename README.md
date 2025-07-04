# Atividades de Polimorfismo em Java

Este repositório contém um projeto Java para treinar conceitos de Polimorfismo, Orientação a Objetos e organização em MVC, utilizando exemplos de animais, pessoas, livros e produtos.

## 🏗️ Estrutura do Projeto

```
Atividades-polimorfismo/
├── README.md
├── .gitignore
└── src/
    └── br/
        └── com/
            └── AtividadesPolimorfismo/
                ├── Main.java
                ├── model/
                │   ├── animais/
                │   │   ├── Animal.java
                │   │   ├── Cachorro.java
                │   │   ├── Coelho.java
                │   │   └── Gato.java
                │   ├── Livro.java
                │   ├── Pessoa.java
                │   └── Produto.java
                ├── service/
                │   └── Criacao.java
                └── view/
                    └── View.java
```

## 📦 Organização

- **model/**: Classes de domínio (entidades), incluindo animais, pessoas, livros e produtos.
- **service/**: Lógica de criação e manipulação das entidades.
- **view/**: Interface de interação com o usuário (console).
- **Main.java**: Classe principal para execução do sistema.

## Exemplos de Entidades

- **Animal** (superclasse abstrata)
  - Cachorro
  - Gato
  - Coelho
- **Pessoa**
- **Livro**
- **Produto**

## 🎯 Funcionalidades

- Demonstração de polimorfismo com animais.
- Cadastro e manipulação de pessoas, livros e produtos.
- Exemplo de separação em camadas (MVC).
- Interação via console.

## 🚀 Como Compilar e Executar

### Compilação

No terminal, execute:

```bat
javac -cp src src/br/com/AtividadesPolimorfismo/Main.java
```

### Execução

```bat
java -cp src br.com.AtividadesPolimorfismo.Main
```

## Técnicas e Padrões Utilizados

- **MVC:** Separação entre dados, lógica e interface.
- **POO:** Encapsulamento, herança e polimorfismo.
- **Coleções:** Uso de ArrayList para gerenciamento dinâmico.

## 💡 Observações

- **Requisitos:** Java 8 ou superior.
- **Persistência:** Todos os dados são mantidos apenas em memória.
- **Execução:** Apenas via terminal/console.
- **Estrutura modular:** Fácil de expandir para novos exemplos de polimorfismo. 