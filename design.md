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
1           | Sensor de Umidade e Temperatura DHT11        | Junto com um cooler, controla a temperatura do cômodo
1           | Cooler 120mm                                 |
1           | Sensor de gás MQ-2 inflamável e fumaça       | Junto com um cooler e o buzzer, controla o nível de gás e previne acidentes
1           | Cooler 120mm                                 |
1           | Buzzer passivo                               |
1           | Módulo Sensor de Umidade/Nível Água Chuva    | Controla a umidade das plantas do jardim
1           |	Sensor de presença e movimento PIR           | Controla a luz do cômodo
1           | Sensor ultrasônico HC-SR04                   | Junto com o micro servo, Controla a entrada do portão
1           | Micro Servo SG92R 9g TowerPro                |
1           | Módulo Matriz de LED 8×8 com MAX7219         | Junto com o módulo relé, controla as luzes de emergência
2           | Módulo Relé 5 V e um Canal                   |
1           | Display LCD 16×2 I2C Backlight Azul          | Mostra as informações mais relevantes



## Diagrama do circuito:


![Diagrama_Circuito_EduardoTenfen_PI2](https://user-images.githubusercontent.com/93286152/145211849-f79c209e-4d5a-463e-a2f4-6cbd0769f89a.png)


## Planta baixa:


![Planta Baixa PI2](https://user-images.githubusercontent.com/93286152/145211884-53caff48-1e53-44b6-b4bc-7d03ccf73326.png)




## Referências

Colocar aqui as referências. _Sempre em formato ABNT_.

ADMIN. **Casa inteligente: a tecnologia de Black Mirror já está o seu alcance!** Disponível em: <https://www.delmak.com.br/casa-inteligente-a-tecnologia-de-black-mirror-ja-esta-ao-seu-alcance/>. Acesso em: 23 mai. 2021.
