# Projeto: Interfaces de Comunicação Serial com RP2040 UART, SPI e I2C

## Autor
**Bruno Santos Costa**

## Descrição
Este projeto implementa uma interface interativa para controlar LEDs RGB, uma matriz de LEDs WS2812 e um display SSD1306, utilizando uma placa BitdogLab e o VS Code. O sistema permite a entrada de dados via monitor serial, interações com botões e apresenta informações gráficas no display OLED.

## Funcionalidades

### 1. Modificação da Biblioteca font.h
- Foi realizada a adição de caracteres minúsculos à biblioteca `font.h`. Foram adicionadas as letras do alfabeto minusculo de a até a letra z para serem exibidos no display SSD1306.

### 2. Entrada de Caracteres via PC
- Utiliza o Serial Monitor do VS Code para entrada de caracteres.
- Caracteres digitados no Serial Monitor são exibidos no display SSD1306.
- Quando um número entre 0 e 9 é digitado, o símbolo correspondente é exibido na matriz de LEDs 5x5 WS2812.

### 3. Interação com o Botão A
- Pressionar o botão A alterna o estado do LED RGB Verde (ligado/desligado).
- As operações são registradas de duas formas:
  - Mensagem informativa sobre o estado do LED exibida no display SSD1306.
  - Texto descritivo enviado ao Serial Monitor.

### 4. Interação com o Botão B
- Pressionar o botão B alterna o estado do LED RGB Azul (ligado/desligado).
- As operações são registradas de duas formas:
  - Mensagem informativa sobre o estado do LED exibida no display SSD1306.
  - Texto descritivo enviado ao Serial Monitor.

## Requisitos
Para reproduzir este projeto, você precisará dos seguintes itens:

### Hardware
- Placa **BitdogLab**
- Display **SSD1306 OLED**
- Matriz de LEDs **WS2812 (5x5)**
- Botões para interação (Botão A e Botão B)

### Software
- **VS Code** com a extensão RaspBerryPi
- SDK do Raspberry Pi Pico
- Bibliotecas adicionais para **SSD1306** e **WS2812**

## Instruções de Uso
1. Conecte a placa BitdogLab ao PC.
2. Abra o projeto no VS Code.
3. Compile e envie o código para a placa.
4. Use o monitor serial para enviar caracteres ao sistema.
5. Pressione o botão A para controlar o LED Verde e o botão B para controlar o LED Azul.

## Demonstração
Acesse o link abaixo para assistir à apresentação do projeto no YouTube:
[**Link para o Vídeo no YouTube**](https://youtu.be/SQbnMIH-aqM?si=bUHncEANbB9BtUEQ)

