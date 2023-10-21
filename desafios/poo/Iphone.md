# IPhone Java - README

Este é um programa Java que modela um iPhone com funcionalidades de reprodutor musical, aparelho telefônico e navegador na internet. O código usa interfaces para definir os métodos necessários para cada funcionalidade e, em seguida, implementa esses métodos em uma classe `IPhone`.

## Funcionalidade

O código é dividido em três interfaces:

### 1. Reprodutor Musical (ReprodutorMusical)

- `tocar()`: Inicia a reprodução de música.
- `pausar()`: Pausa a reprodução de música.
- `selecionarMusica(String musica)`: Seleciona uma música para reprodução.

### 2. Aparelho Telefônico (AparelhoTelefonico)

- `ligar(String numero)`: Inicia uma chamada telefônica para o número especificado.
- `atender()`: Atende uma chamada telefônica.
- `iniciarCorreioDeVoz()`: Inicia o correio de voz durante uma chamada.

### 3. Navegador na Internet (NavegadorInternet)

- `exibirPagina(String url)`: Exibe uma página da web com a URL especificada.
- `adicionarNovaAba(String url)`: Adiciona uma nova aba de navegador com a página da web especificada.
- `atualizarPagina()`: Atualiza a página atual.

## Classe IPhone

A classe `IPhone` implementa todas as três interfaces e fornece a funcionalidade completa de um iPhone.

- Ele possui atributos para rastrear o estado atual, como se a música está sendo reproduzida, se há uma chamada em andamento, se o correio de voz está ativo e a URL da página da web atual.

- Os métodos da interface ReprodutorMusical são implementados para controlar a reprodução de música.

- Os métodos da interface AparelhoTelefonico são implementados para simular a funcionalidade de chamada telefônica e correio de voz.

- Os métodos da interface NavegadorInternet são implementados para exibir páginas da web, adicionar abas e atualizar a página.

## Executando o Programa

O método `main` da classe `IPhone` demonstra o uso do iPhone simulado. Ele inicia o iPhone, reproduz música, faz chamadas telefônicas, inicia o correio de voz e realiza ações no navegador da web simulado.