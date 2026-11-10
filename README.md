# 🛡️ Hamilton SafeHouse — Dashboard Web & IoT

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Plataforma](https://img.shields.io/badge/Plataforma-ESP32%20%7C%20Web%20BLE-purple)

Sistema Inteligente de Segurança e Economia Residencial desenvolvido pela turma do **3°MSI-02 (Colégio João XXIII)**. Inspirado na arquitetura de software desenvolvida por **Margaret Hamilton**.

---

## 📸 Capturas de Tela

| Interface Mobile | Interface Desktop |
| :---: | :---: |
| <img src="img/WhatsApp Image 2026-08-05 at 18.59.09 (1).jpeg" width="260"> | <img src="img/WhatsApp Image 2026-08-05 at 18.59.09.jpeg" width="480"> |

---

## ⚙️ Funcionalidades principais

- 🌡️ **Monitoramento Ambiental:** Leituras instantâneas de temperatura e umidade.
- ⚡ **Telemetria Elétrica:** Medição de tensão, corrente, potência e consumo acumulado (PZEM-004T).
- 💧 **Consumo Hídrico:** Leitura de fluxo (L/min) e consumo total por sessão.
- 🔥 **Alerta de Emergência:** Detecção de chama com acionamento automático de LEDs de sinalização e Buzzer.
- 📶 **Conectividade Sem Fio:** Comunicação nativa via Web Bluetooth API (BLE).
- 📊 **Gráficos Dinâmicos:** Histórico de leituras em tempo real renderizado com Chart.js.

---

## 🛠️ Tecnologias Utilizadas

### **Hardware / Microcontrolador**
- ESP32 WROOM-32
- Sensores: DHT11/DHT22, Sensor de Chama, Medidor Elétrico PZEM-004T, Sensor de Fluxo de Água.
- Atuadores: LEDs (Verde/Amarelo/Vermelho) e Buzzer 5V.

### **Frontend**
- HTML5 Semântico com suporte a PWA / Mobile
- CSS3 (Variáveis CSS, Flexbox, Grid e Media Queries para responsividade PC/Mobile)
- JavaScript Vanilla (ES6+)
- Chart.js

---

## 🚀 Como Executar Localmente

A **Web Bluetooth API** exige protocolo seguro (`HTTPS` ou `localhost`).

```bash
# 1. Clone o repositório
git clone [https://github.com/Davy466/site-3msi02mobile.git](https://github.com/Davy466/site-3msi02mobile.git)

# 2. Acesse a pasta do projeto
cd site-3msi02mobile

# 3. Execute um servidor local (exemplo com Python)
python -m http.server 8000
