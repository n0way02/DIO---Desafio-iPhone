# Projeto iPhone Simulador - Desafio DIO POO

Este projeto é uma implementação do desafio de Programação Orientada a Objetos (POO) proposto pela Digital Innovation One (DIO) na trilha Java Básico. O objetivo é simular as funcionalidades básicas de um iPhone, modelando suas capacidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet através do uso de interfaces e classes em Java.

## Funcionalidades

O projeto simula as seguintes funcionalidades do iPhone:

### 📱 Aparelho Telefônico
* `ligar(String numero)`: Simula uma chamada para um número.
* `atender()`: Simula o atendimento de uma chamada.
* `iniciarCorreioVoz()`: Simula o início do correio de voz.

### 🎵 Reprodutor Musical
* `tocar()`: Simula a reprodução de uma música.
* `pausar()`: Simula a pausa da música.
* `selecionarMusica(String musica)`: Simula a seleção de uma música específica.

### 🌐 Navegador na Internet
* `exibirPagina(String url)`: Simula a exibição de uma página web.
* `adicionarNovaAba()`: Simula a abertura de uma nova aba no navegador.
* `atualizarPagina()`: Simula a atualização da página atual.

## Estrutura do Projeto

O projeto é composto pelas seguintes classes e interfaces em Java:

* `ReprodutorMusical.java`: Interface que define os métodos de um reprodutor musical.
* `AparelhoTelefonico.java`: Interface que define os métodos de um aparelho telefônico.
* `NavegadorInternet.java`: Interface que define os métodos de um navegador na internet.
* `iPhone.java`: Classe principal que implementa todas as interfaces acima, consolidando as funcionalidades em um único objeto. Inclui um método `main` para demonstração.

## Como Executar

Para compilar e executar este projeto:

1.  **Clone o repositório** (se estiver em um, ou baixe os arquivos diretamente).
2.  **Compile os arquivos Java** usando o compilador `javac` em seu terminal, na pasta raiz do projeto:
    ```bash
    javac ReprodutorMusical.java AparelhoTelefonico.java NavegadorInternet.java iPhone.java
    ```
3.  **Execute a classe `iPhone`**:
    ```bash
    java iPhone
    ```

Ao executar, você verá as mensagens de saída no console simulando as ações do iPhone.
