# Java-Basico



### 🚀 **Curso de Programação em Java – Iniciante ao Intermediário**

#### 📚 **Plano de Curso**

1. **Introdução à Programação e ao Java**
2. **Ambiente de Desenvolvimento (JDK, IDE, Hello World)**
3. **Tipos de Dados e Variáveis**
4. **Operadores e Expressões**
5. **Estruturas de Controle: Condições (if, switch)**
6. **Estruturas de Repetição: loops (for, while, do-while)**
7. **Funções e Métodos**
8. **Programação Orientada a Objetos (POO)**
9. **Arrays e Coleções**
10. **Tratamento de Exceções**
11. **Trabalhando com Arquivos**
12. **Projetos Práticos (Exercícios e Miniprojetos)**

---

### ✅ **Lição 1 – Introdução à Programação e ao Java**

#### 📌 O que você vai aprender:

* O que é programação
* O que é Java e por que usá-lo
* Onde o Java é usado no mundo real

#### 🧠 Conceitos:

* **Programação** é o processo de escrever instruções que o computador pode entender e executar.
* **Java** é uma linguagem de programação **orientada a objetos**, **portável**, **segura**, e usada em sistemas embarcados, aplicativos web, móveis (Android), e sistemas corporativos.

#### 🌍 Onde o Java é usado:

* Aplicativos Android
* Sistemas bancários e financeiros
* Servidores web
* Jogos e softwares empresariais

Quando estiver pronto, seguimos para a **Lição 2 – Ambiente de Desenvolvimento e seu primeiro código Java (Hello World)**.


## ✅ **Lição 2 – Ambiente de Desenvolvimento e Seu Primeiro Código Java**

### 🎯 Objetivo da lição:

* Instalar o Java
* Escolher uma IDE (programa para escrever código)
* Criar e executar o primeiro programa: **Hello World**

---

### 🧰 1. Instalar o Java (JDK)

**JDK (Java Development Kit)** é o kit que permite compilar e executar códigos Java.

1. Acesse: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)
2. Baixe a **versão LTS (como Java 17 ou 21)** para o seu sistema operacional (Windows, macOS ou Linux).
3. Instale normalmente como qualquer outro programa.

---

### 🖥️ 2. Escolher e instalar uma IDE

Uma IDE é como um "ambiente de trabalho" para programar.

As duas mais comuns para iniciantes em Java são:

* **IntelliJ IDEA (Community Edition)** – [https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)
* **Eclipse IDE** – [https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/)

💡 Recomendo o **IntelliJ IDEA** por ser mais moderno e intuitivo.

---

### 🧪 3. Seu primeiro programa Java – “Hello World”

#### Passos no IntelliJ (após instalar):

1. Crie um novo projeto Java.
2. Crie um novo arquivo chamado `HelloWorld.java`.
3. Escreva o seguinte código:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, mundo!");
    }
}
```

#### O que esse código faz:

* Define uma **classe** chamada `HelloWorld`.
* Define o **método main**, que é o ponto de entrada do programa.
* Usa `System.out.println` para imprimir **Olá, mundo!** no console.

---

### 🎯 Tarefa:

1. Instale o **JDK** e uma **IDE**.
2. Crie e execute o código acima.

Quando estiver pronto, a gente vai para a **Lição 3 – Tipos de Dados e Variáveis em Java**.

Perfeito! 🎉
Você já deu o primeiro passo importante: **executou seu primeiro programa em Java**! Agora sim, vamos continuar avançando.

---

## ✅ **Lição 3 – Tipos de Dados e Variáveis em Java**

### 🎯 Objetivo da lição:

* Entender o que são variáveis
* Conhecer os principais tipos de dados em Java
* Escrever e testar exemplos simples

---

### 🧠 O que são variáveis?

Variáveis são espaços na memória onde você armazena informações (como nomes, números, etc.) durante a execução do programa.

---

### 🔤 Principais tipos de dados em Java:

| Tipo      | Descrição                        | Exemplo de valor |
| --------- | -------------------------------- | ---------------- |
| `int`     | Número inteiro                   | `25`             |
| `double`  | Número decimal (ponto flutuante) | `3.14`           |
| `char`    | Um único caractere               | `'A'`            |
| `boolean` | Verdadeiro ou falso              | `true`, `false`  |
| `String`  | Conjunto de caracteres (texto)   | `"Java é top!"`  |

---

### ✍️ Exemplo prático:

Crie um novo arquivo chamado `VariaveisExemplo.java` e adicione:

```java
public class VariaveisExemplo {
    public static void main(String[] args) {
        int idade = 20;
        double altura = 1.75;
        char inicial = 'J';
        boolean estudandoJava = true;
        String nome = "Maria";

        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);
        System.out.println("Altura: " + altura);
        System.out.println("Inicial do nome: " + inicial);
        System.out.println("Está estudando Java? " + estudandoJava);
    }
}
```

---

### 🧪 Tarefa:

1. Crie o arquivo `VariaveisExemplo.java`.
2. Execute o programa.
3. Veja os valores sendo exibidos no console.

Se quiser um desafio extra:

> Modifique os valores das variáveis para representar você.
> Ex: seu nome, sua idade, sua altura etc.

---

Quando estiver pronto, seguimos para a **Lição 4 – Operadores e Expressões em Java**.



