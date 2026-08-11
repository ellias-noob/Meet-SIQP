# 🌲 SIPQ — Sistema Inteligente de Prevenção contra Queimadas

> **Projeto Tecnológico e Ecológico de Mitigação de Incêndios Florestais** > *Escola Estadual de Educação Profissional de Cuiabá — Curso Técnico em Desenvolvimento de Sistemas*

---

## 📌 Sobre o Projeto

O **SIPQ (Sistema Inteligente de Prevenção contra Queimadas)** é uma solução automatizada e preditiva desenvolvida para monitorar, detectar e combater focos de incêndio em propriedades rurais e áreas ambientais vulneráveis. 

Unindo a eficiência da eletrônica com **Arduino**, a inteligência de análise de dados com **Python (IA)** e o uso sustentável de **recursos hídricos (captação de água da chuva)**, o sistema oferece uma resposta rápida e ecológica para mitigar os impactos das queimadas no bioma do Centro-Oeste e proteger a biodiversidade e o patrimônio agrícola.

---

## 🚀 Como Funciona

1. **Análise Preditiva (IA em Python):** Antes e durante a operação, o Python processa dados climáticos e geoespaciais (temperatura, umidade relativa e vento) para identificar zonas de alto risco.
2. **Monitoramento em Tempo Real (IoT / Arduino):** Sensores de fumaça e temperatura espalhados pelo perímetro coletam dados ambientais continuamente.
3. **Validação de Risco:** O Arduino envia os dados via comunicação Serial para o script Python, que valida o risco cruzando as leituras físicas com a previsão meteorológica local.
4. **Combate Automatizado:** Confirmada a ameaça, o sistema aciona relés que ativam mini bombas d'água ligadas a cisternas de água da chuva, pulverizando água através de aspersores estratégicos para resfriar a área e conter o fogo.
5. **Relatórios de Segurança:** O software registra o histórico das leituras e gera relatórios automáticos de eventos e alertas.

---

## 🛠️ Tecnologias e Componentes

### **Hardware & Eletrônica**
* **Placa do Microcontrolador:** Arduino Uno R3
* **Sensor de Fumaça/Gás:** Módulo MQ-2
* **Sensor de Temperatura e Umidade:** Módulo DHT11 / DHT22
* **Atuador:** Módulo Relé 5V (1 Canal)
* **Irrigação:** Mini Bomba d'Água Submersível + Tubulação de Silicone e Aspersores
* **Reservatório:** Cisterna de Armazenamento de Água da Chuva

### **Software & Linguagens**
* **C / C++ (Arduino IDE):** Leitura de hardware e controle de pinos digitais/analógicos.
* **Python 3:** Processamento de dados, inteligência de validação de risco e comunicação Serial (`pyserial`).
* **Git & GitHub:** Controle de versão do código.

---
