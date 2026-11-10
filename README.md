# 🛡️ Hamilton SafeHouse — Dashboard Web & IoT

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)
![Platform](https://img.shields.io/badge/Plataforma-ESP32%20%7C%20Web%20BLE-purple)

Sistema Inteligente de Segurança e Economia Residencial desenvolvido pela turma do **3°MSI-02 (Colégio João XXIII)**. Inspirado na arquitetura de confiabilidade desenvolvida por **Margaret Hamilton**.

---

## 📱 Demonstração do Projeto

| Visão Mobile | Visão Desktop |
| :---: | :---: |
| <img src="img/WhatsApp Image 2026-08-05 at 18.59.09 (1).jpeg" width="250"> | <img src="img/WhatsApp Image 2026-08-05 at 18.59.09.jpeg" width="450"> |

---

## ⚙️ Funcionalidades

- 🌡️ **Monitoramento Ambiental:** Leitura de temperatura e umidade em tempo real.
- ⚡ **Telemetria Elétrica:** Medição de tensão, corrente, potência e energia consumida (PZEM-004T).
- 💧 **Gestão de Água:** Leitura de fluxo (L/min) e consumo acumulado por sessão.
- 🔥 **Alerta de Emergência:** Detecção de chama com disparo automático de atuadores físicos (LEDs e Buzzer).
- 📶 **Conexão Sem Fio:** Comunicação nativa via Web Bluetooth API (BLE).
- 📊 **Gráficos Dinâmicos:** Exibição de histórico de leituras com Chart.js.

---

## 🛠️ Tecnologias Utilizadas

### **Hardware / Microcontrolador**
- ESP32 WROOM-32
- Sensores: DHT11/DHT22, Sensor de Chama, Medidor PZEM-004T, Sensor de Fluxo de Água.
- Atuadores: LEDs de sinalização e Buzzer 5V.

### **Frontend & Interface**
- HTML5 semântico com suporte a PWA/Mobile
- CSS3 (Variáveis CSS, Flexbox, Grid e Medias Queries para responsividade PC/Mobile)
- JavaScript Vanilla (ES6+)
- [Chart.js](https://www.chartjs.org/) para plotagem de dados

---

## 🚀 Como Executar o Projeto

### **Requisitos**
Como o projeto faz uso da **Web Bluetooth API**, ele exige um ambiente seguro (`HTTPS` ou `localhost`).

### **Passos**
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/Hamilton-SafeHouse.git](https://github.com/seu-usuario/Hamilton-SafeHouse.git)
