# Design

Acesso rápido:
  - [Introdução](./README.md)
  - [Concepção](./concepcao.md)
  - [Implementação](./implementacao.md)
  - [Operação](./operacao.md)

Nessa etapa será apresentado a disposição dos componentes e a planta da maquete.

## Componentes:

Quantidade  | Tecnologias | Função
:---------:   | ------   | ------
1           | Placa Arduino MEGA 2560 R3                   |
1           | Sensor de Umidade e Temperatura DHT11        | Junto com um relé e um cooler, controla a temperatura do cômodo
1           | Módulo Relé 5 V                              |
1           | Cooler 120mm                                 |
1           | Sensor de gás MQ-2 inflamável e fumaça       | Junto com um relé, um cooler e o buzzer, controla o nível de gás e previne acidentes
1           | Módulo Relé 5 V                              |
1           | Cooler 120mm                                 |
1           | Buzzer passivo                               |
1           | Módulo Sensor de Umidade/Nível Água Chuva    | Controla a umidade das plantas do jardim
1           |	Sensor de presença e movimento PIR           | Controla a luz do cômodo
1           | Sensor ultrasônico HC-SR04                   | Junto com o micro servo, Controla a entrada do portão
1           | Micro Servo SG92R 9g TowerPro                |
1           | Módulo Matriz de LED 8×8 com MAX7219         | Junto com o módulo relé, controla as luzes de emergência
1           | Display LCD 16×2 I2C Backlight Azul          | Mostra as informações mais relevantes



## Diagrama do circuito:


![Maquete_eletronica](https://user-images.githubusercontent.com/93286152/156659631-73b15313-a02b-4b7f-b970-a617cdd6a0a6.png)




## Planta baixa:


![Planta Baixa PI2](https://user-images.githubusercontent.com/93286152/152165926-d94206d5-7c95-40d2-aad2-73dcb3c7b561.png)



## Referências

Colocar aqui as referências. _Sempre em formato ABNT_.

ADMIN. **Casa inteligente: a tecnologia de Black Mirror já está o seu alcance!** Disponível em: <https://www.delmak.com.br/casa-inteligente-a-tecnologia-de-black-mirror-ja-esta-ao-seu-alcance/>. Acesso em: 23 mai. 2021.
