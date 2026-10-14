# ☕ Java – Exercícios de Programação Orientada a Objetos

Repositório com exercícios práticos de **Java** e **Programação Orientada a Objetos (POO)**, desenvolvidos durante meus estudos. Cada projeto modela uma situação do mundo real usando classes, objetos, encapsulamento, construtores, métodos e coleções.

## 📚 Conceitos praticados

- Classes, atributos e métodos
- Construtores
- Encapsulamento (`private`, getters e setters)
- Criação e manipulação de objetos
- Arrays e `ArrayList`
- Estruturas condicionais e operador ternário
- Atributos estáticos (`static`) para geração automática de ID
- Sobrescrita de `toString()`
- Organização do código em pacotes (`package`)
- Leitura de dados com `Scanner`

## 📁 Projetos

| Projeto | Descrição | Classes |
|---|---|---|
| **Impressora** | Simula uma impressora com fila de impressão. Ao receber arquivos, o primeiro inicia a impressão e, ao finalizar, o próximo da fila é iniciado. | `Impressora`, `Impressao`, `Aplicacao` |
| **Controle de TV** | Simula um controle remoto: liga/desliga, avança e retorna canais (de 1 a 5) e vai direto para um canal específico. | `ControleTelevisao`, `ControleTelevisaoTeste` |
| **Motor** | Modela um motor com modelo, cilindrada e tipo de combustível, permitindo ligar e desligar. O teste usa `Scanner` para escolher qual motor ligar. | `Motor`, `MotorTeste` |
| **Raça** | Cadastro de raças de animais com análise de risco de extinção baseada em um sistema de pontos (4 critérios; risco a partir de 5 pontos). | `Raca`, `RacaTeste` |
| **Recepção** | Registro de hóspede de um hotel: nome, diárias, forma de pagamento e CPF. | `Recepcao`, `RecepcaoTeste` |
| **Streaming** | Representa uma música de plataforma de streaming: cantor, música, ano e álbum. | `Streming`, `StremingTeste` |
| **Triângulo** | Armazena os lados de um triângulo, calcula a área (fórmula de Heron) e classifica o tipo. Os testes usam uma lista (`ArrayList`) de triângulos. | `Triangulo`, `TrianguloTeste` |

## 🗂️ Estrutura

```
.
├── Impressora/
│   ├── Aplicacao.java
│   └── Impressora.java
├── Impressao/
│   └── Impressao.java
├── ControleTelevisao/
│   ├── ControleTelevisao.java
│   └── ControleTelevisaoTeste.java
├── MeUp1/
│   ├── Motor.java
│   └── MotorTeste.java
├── Raca/
│   ├── Raca.java
│   └── RacaTeste.java
├── Recepcao/
│   ├── Recepcao.java
│   └── RecepcaoTeste.java
├── Streming/
│   ├── Streming.java
│   └── StremingTeste.java
├── Triangulo/
│   ├── Triangulo.java
│   └── TrianguloTeste.java
└── README.md
```

> A estrutura acima segue os nomes dos pacotes declarados em cada arquivo. `Raca` e `RacaTeste` não declaram pacote.

## 🚀 Como executar

### Pré-requisitos

- [JDK 11 ou superior](https://adoptium.net/) instalado
- Uma IDE (IntelliJ IDEA, Eclipse, VS Code) ou apenas o terminal

...

### Pela IDE

Abra a pasta como projeto Java, localize a classe com `main` (`Aplicacao` ou `*Teste`) e execute.

## 🧪 Classes de execução (`main`)

| Projeto | Classe para executar |
|---|---|
| Impressora | `Impressora.Aplicacao` |
| Motor | `MeUp1.MotorTeste` |
| Raça | `RacaTeste` |
| Recepção | `Recepcao.RecepcaoTeste` |
| Streaming | `Streming.StremingTeste` |
| Triângulo | `Triangulo.TrianguloTeste` |

## 🛠️ Tecnologias

- Java
- Git e GitHub

## 👤 Autor

Desenvolvido por Elias Ferreira— [LinkedIn]((https://www.linkedin.com/in/elias-ferreira-de-melo-5bb9b830b/?isSelfProfile=true)) · [GitHub](https://github.com/eliasfmelo)
