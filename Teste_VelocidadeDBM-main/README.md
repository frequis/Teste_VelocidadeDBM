# Teste_VelocidadeDBM

## Introdução

Este projeto realiza a coleta e análise de potência de sinal WiFi em dBm utilizando um ESP32 conectado a uma rede WiFi. O objetivo é medir a radiofrequência em cenários distintos dentro do Inteli e simular o efeito de uma gaiola de Faraday utilizando o elevador.

### Análise de Dados (calculo.ipynb)

O notebook `calculo.ipynb` processa e visualiza os dados de potência de sinal coletados durante os testes. Ele gera um **gráfico de dispersão com linhas interligando os pontos**, mostrando a variação de sinal em dBm ao longo dos pontos de monitoramento:

1. Sala de aula (10s)
2. Catraca da recepção (10s)
3. Posto do IT Bar - 1º andar (10s)
4. Interior do elevador com porta fechada (20s)
5. Laboratório do André Leal - 2º andar (10s)
6. Última salinha de reunião do mesanino 2 (10s)
7. Saída do elevador
8. Lado oposto da rua - fora do Inteli (10s)

O gráfico permite visualizar claramente o impacto do ambiente físico na intensidade do sinal, especialmente o bloqueio significativo de sinal observado no interior do elevador (simulação de gaiola de Faraday).

### Objetivo do Projeto

Implementar um sistema IoT completo com ESP32, MQTT e dashboard online para monitorar em tempo real a qualidade do sinal WiFi em diferentes ambientes e demonstrar o efeito de blindagem eletromagnética.
