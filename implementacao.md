# Implementação do Projeto

Acesso rápido:
  - [Introdução](./README.md)
  - [Concepção](./concepcao.md)
  - [Design/Projeto](./design.md)
  - [Operação](./operacao.md)


## Implementação

  Nas etapas anteriores, todas as funções foram idealizadas e, em seguida, a domótica é planejada para ser aplicada em uma maquete, nesta fase de implementação, é hora de colocar em prática o que foi projetado. Em seguida, será descrito o processo de fabricação da maquete, a codificação, teste e validação de cada tarefa do sistema e a integração geral para alcançar os resultados desejados.

### Construção da maquete

  Na fase de concepção foi apresentada a planta baixa da maquete a ser implementada no projeto, com base na planta baixa, a maquete foi desenvolvida utilizando isopor em sua totalidade e palitos para a fixação.
  
### Testes dos sensores

Os componentes são testados individualmente para provar que estão todos em boas condições de funcionamento e integrados conforme planejado durante a fase de concepção do projeto. 
O código será implementado na forma de tarefas, onde cada tarefa tem tempo para executar o loop e passar os resultados dos sensores.
  
### Sobre o código

O código foi desenvolvido em forma de tarefas, cada uma realizada em um determinado tempo, para que tudo funcione da forma correta, as tarerefas criadas foram:

tarefa_DHT (tarefa de climatização): Essa tarefa faz a leitura da temperatura a cada 8 segundos e mostra a temperatura no display, se a temperatura atingir 23°C, a tarefa ativa um relé que por sua vez ativa um ventilador(cooler) no quarto;

tarefa_MQ2 (tarefa de proteção contra acidentes com gás): Essa tarefa faz a leitura do nível de gás a cada 5 segundos e mostra o nível de gás no display, se o nível de gás atingir 25%, a tarefa ativa um relé que por sua vez ativa um exaustor(cooler), ativa um buzzer de alerta e ativa a matriz de led com uma mensagem de alerta na cozinha;

tarefa_PIR (tarefa de iluminação): Essa tarefa faz a leitura de presença a cada 0,1 segundos, se detectar uma presença, a tarefa ativa um led(luz) no quarto, a luz fica acesa por 10 minutos após a detectar uma presença, se não ouver presença durante 10 minutos a luz é apagada;

tarefa_HCSR04 (tarefa de campainha): Essa tarefa faz a leitura da distancia a cada 1 segundo, se a distancia for menor ou igual a 5cm, a tarefa ativa o buzzer e mostra no display "temos vizitas";

controle_portao (tarefa de abertura do portão): Essa tarefa é feita de forma manual, o portão abre/fecha assim que for digitado a tecla "p" no monitor serial, inicialmente o portão está fechado;

* [Código completo](./Codigo_PI2.ino)

Finalmente, os componentes foram dispostos no modelo e vários testes foram realizados para validar o projeto. Aqui estão alguns aplicativos testados:

* Ativar os sistemas de cada sensor, individualmente e em conjunto.
* Liberar gás com um isqueiro para acionar o sensor de gás.
* Modificar a temperatura de acionamento do ventilador para a temperatura do ambiente.
* Fazer o sensor pir detectar presença e ativar o led.
* Checar o display LCD e verificar se as informações estão corretas.
* Abrir e fechar o portão. 

### A imagem abaixo mostra a já maquete concluida

IMAGEM AQUI

A partir dessas ações, pode-se concluir que todo o sistema está funcionando corretamente, conforme planejado nas fases anteriores de concepção e design.

