# Teste_VelocidadeDBM

Este projeto realiza a coleta e análise de potência de sinal WiFi em dBm utilizando um ESP32 conectado a uma rede WiFi. O objetivo é medir a radiofrequência em cenários distintos dentro do Inteli e simular o efeito de uma gaiola de Faraday utilizando o elevador.

## Locais do teste

1. Sala de aula

<div align="center">
<sub>-62</sub>
<img src="assets/sala.jpg" width="100%">
</div>

2. Catraca da recepção

<div align="center">
<sub>-71</sub>
<img src="assets/catraca.jpg" width="100%">
</div>

3. Posto do IT Bar - 1º andar

<div align="center">
<sub>-82</sub>
<img src="assets/itbar.jpg" width="100%">
</div>

4. Elevador com porta fechada

<div align="center">
<sub>-70</sub>
<img src="assets/elevador.jpg" width="100%">
</div>

5. Laboratório - 2º andar

<div align="center">
<sub>-72</sub>
<img src="assets/lab.jpg" width="100%">
</div>

6. Última salinha de reunião do mesanino

<div align="center">
<sub>-68</sub>
<img src="assets/mesanino.jpg" width="100%">
</div>

7. Portaria no lado de fora do Inteli

<div align="center">
<sub>-70</sub>
<img src="assets/portaria.jpg" width="100%">
</div>

## Gráfico de dispersão

O gráfico permite visualizar claramente o impacto do ambiente físico na intensidade do sinal.

<div align="center">
<img src="assets/1graphic.png" width="100%">
<sub>Gráfico de dispersão feito com python</sub>
</div>

## Objetivo do Projeto

Implementar um sistema IoT completo com ESP32, MQTT e dashboard online para monitorar em tempo real a qualidade do sinal WiFi em diferentes ambientes e demonstrar o efeito de blindagem eletromagnética.