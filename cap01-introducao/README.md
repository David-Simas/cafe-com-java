# 📘 Capítulo 1: Introdução e Configuração do Ambiente

Neste capítulo você vai aprender:

- O que é Java: JVM, JRE e JDK.
- Por que aprender Java.
- Como instalar o JDK.
- Como configurar variáveis de ambiente (JAVA_HOME, PATH).
- Como escolher e usar uma IDE.
- Como escrever, compilar e executar seu primeiro programa em Java.

---

## ☕ O que é Java?

Java é uma linguagem de programação **orientada a objetos**, multiplataforma e muito utilizada no mercado.

- **JDK (Java Development Kit)**: Pacote completo para desenvolvimento (compilador, bibliotecas, ferramentas).
- **JRE (Java Runtime Environment)**: Ambiente necessário para executar aplicações Java.
- **JVM (Java Virtual Machine)**: Máquina virtual que interpreta o bytecode gerado pelo compilador Java.

---

## ❓ Por que aprender Java?

- Plataforma independente (escreva uma vez, execute em qualquer lugar).
- Grande comunidade e muitas oportunidades no mercado.
- Usado em diversas áreas: sistemas corporativos, Android, back-end, IoT, etc.

---

## ⚙️ Instalando o JDK

1. Baixe o JDK no site oficial da Oracle ou Adoptium (https://adoptium.net).
2. Instale normalmente conforme seu sistema operacional.

### ✅ Variáveis de Ambiente (Windows)

- Adicione o caminho da pasta `bin` do JDK à variável `PATH`.
- Crie a variável `JAVA_HOME` apontando para a raiz da instalação do JDK.

---

## 💻 Escolha da IDE

Você pode usar qualqueuma destas IDEs gratuitas:

- [IntelliJ IDEA Community](https://www.jetbrains.com/idea/)
- [Eclipse](https://www.eclipse.org/)
- [VS Code](https://code.visualstudio.com/) com a extensão *Java Extension Pack*

---

## 🧵 Como Compilar e Executar
▶️ Na linha de comando:

- javac HelloWorld.java
- java HelloWorld

---

## ▶️ Na IDE:

- Clique no botão Run ou Executar.

---

## 📝 Exercícios

1. Modifique o programa para imprimir o seu nome.
2. Faça o programa imprimir duas linhas de texto diferentes.
3. Compile e execute o programa tanto pela linha de comando quanto pela IDE.