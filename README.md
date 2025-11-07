# Projeto Passa a bola (Sprint 04 Edge) – Monitoramento de Dados Biométricos com ESP32

## Integrantes
- Erick Gabriel Ferreira dos Santos – RM: 565144  
- Miguel dos Santos de Andrade – RM: 563516  
- Nuno Coutinho Henrique – RM: 562438  
- Yasmin Amorim Affonso – RM: 563645  

---

## Resumo do Projeto

Este projeto desenvolve uma prova de conceito (PoC) de um sistema IoT utilizando o microcontrolador **ESP32**.  
O objetivo é monitorar, em tempo real, dados fisiológicos e de movimento de um atleta, simulando o funcionamento de sensores biométricos e de aceleração.  
Os dados são processados pelo ESP32 e enviados para plataformas online de visualização e armazenamento.

---

## Componentes Utilizados

- **ESP32** – microcontrolador principal utilizado no simulador Wokwi  
- **MPU6050** – sensor de aceleração, giroscópio e temperatura  
- **Sensor de Pulso (BPM)** – simulado via entrada analógica  
- **Sensor de Oxigenação (SpO₂)** – simulado via entrada analógica  

---

## Comunicação e Envio de Dados

O sistema envia as informações coletadas pelos sensores de duas formas:

1. **ThingSpeak (via protocolo HTTP):**  
   Usado para armazenar e exibir gráficos com o histórico de dados coletados.

2. **Broker MQTT Público (`test.mosquitto.org`):**  
   Responsável por transmitir os dados em tempo real, permitindo visualização por meio do aplicativo **MQTT Dashboard**.

---

## Tecnologias e Serviços Utilizados

- **Plataforma de Simulação:** Wokwi (ESP32)  
- **Linguagem de Programação:** C++ (Arduino Framework)  
- **Protocolos de Comunicação:** HTTP e MQTT  
- **Serviços em Nuvem:** ThingSpeak e Mosquitto MQTT  
- **Aplicativo de Visualização:** MQTT Dashboard  

---

## Link da Simulação

A simulação completa do projeto está disponível no link abaixo:

[Visualizar no Wokwi](https://wokwi.com/projects/446997591443410945)

---
