# Concepção do projeto

Acesso rápido:
  - [Introdução](./README.md)
  - [Design/Projeto](./design.md)
  - [Implementação](./implementacao.md)
  - [Operação](./operacao.md)


Este projeto tem como objetivo desenvolver um sistema de domótica completo, promovendo maior conforto e segurança para os residendes, visando o baixo custo.

#### Seguindo os objetivos definidos no projeto serão utilizados os seguintes componentes respectivamente com suas finalidades:

* Sensor de Temperatura, para controle da temperatuda nos cômodos, quando a temperatura subir além de 25° o ar condicionado/ventilador será ligado e um aviso irá ser enviado
para o display;

* Sensor de gás e de fumaça, quando o sensor detectar um valor acima do normal acionará um exaustor, caso o exaustor não funcione e o valor continuar a subir, um buzzer emitirá um alarme sonoro para evitar um possivel acidente;

* Módulo Sensor de Umidade/Nível Água Chuva, controla a rega das plantas no jardim, quando o sensor de nivel da água estiver acima de 50% e o sensor de umidade abaixo de 75%, emitirá um aviso no display LCD para regar as plantas;

* Sensor de presença, para ligar as luzes do cômodo assim que o residente entrar ou desligar as luzes quando não houver residendes no cômodo.

* Sensor ultrasônico e o micro servo, quando o sensor detectar a uma distância de 3cm do portão de entrada, o display LCD irá emitir um aviso de que possui visita, solicitará que o botão do controle seja acionado para abrir o portão;

* Matriz de led e um módulo relé, irão atuar como luz de emergência, quando a luz acabar o relé irá acionar a matriz de led;

* Display LCD, mostrando as informações mais relevantes do sistema.



Tecnologias para a realização do projeto:


Quantidade  | Tecnologias
:---------:   | ------
1           | Placa Arduino MEGA 2560 R3
1           | Sensor de Umidade e Temperatura DHT11
1           | Sensor de presença e movimento PIR
1           | Sensor de gás MQ-2 inflamável e fumaça
1           | Micro Servo SG92R 9g TowerPro
1           | Módulo Sensor de Umidade/Nível Água Chuva
1           | Módulo Relé 5 V e um Canal
1           | Sensor ultrasônico HC-SR04
1           | Módulo Matriz de LED 8×8 com MAX7219
1           | Buzzer passivo
1           | Display LCD 16×2 I2C Backlight Azul



## Referências

Colocar aqui as referências. _Sempre em formato ABNT_.

ADMIN. **Casa inteligente: a tecnologia de Black Mirror já está o seu alcance!** Disponível em: <https://www.delmak.com.br/casa-inteligente-a-tecnologia-de-black-mirror-ja-esta-ao-seu-alcance/>. Acesso em: 23 mai. 2021.
