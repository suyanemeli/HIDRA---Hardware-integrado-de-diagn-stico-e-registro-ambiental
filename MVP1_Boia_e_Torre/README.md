# 📡 MVP 1 — Arranjo Distribuído (Boia + Torre de Margem)

O **MVP 1** representa a primeira arquitetura funcional do ecossistema H.I.D.R.A., concebida sob o paradigma de processamento e sensoriamento distribuídos. O sistema foi projetado para operar em canais urbanos a céu aberto, dividindo a responsabilidade de aquisição de dados e de telemetria entre dois módulos interligados.

---

## 🛠️ Arquitetura do Sistema

O arranjo é composto por dois subsistemas principais:

1. **Módulo Flutuante (Boia de Sensoriamento):**
   - **Processamento Local:** Microcontrolador **STM32** dedicado à aquisição contínua, filtragem de ruído e leitura de dados analógicos/digitais.
   - **Sensores Embarcados:** Conjunto de sondas para leitura de parâmetros físico-químicos e limnológicos (pH, Turbidez, cor, 

Temperatura, Condutividade Elétrica e OD).
   - **Comunicação:** Interface industrial robusta via **RS-485 (protocolo Modbus RTU)** acoplada ao cabo umbilical submarino/aéreo.

2. **Módulo de Margem (Torre de Telemetria e Visão):**
   - **Processamento e Gateways:** Módulo **ESP32-CAM** atuando como central de agregação e registro visual.
   - **Registro Visual:** Câmera integrada para inspeção visual periódica do corpo d'água e verificação de biofilme/sujeira nos sensores.
   - **Telemetria:** Conectividade sem fio (Wi-Fi/Local Gateway) para envio dos dados formatados para a nuvem.
   - **Alimentação Autônoma:** Sistema fotovoltaico com painel solar e gerenciamento de carga por bateria.

---

## 📸 Registros de Imagens (Fotos do Hardware)

| Módulo Flutuante (Boia) | Módulo de Margem (Torre) | Visão Conjunta / Instalação |
| :---: | :---: | :---: |
|  |<img src="https://github.com/user-attachments/assets/bde4e551-89c2-4eb5-b3fa-0f74d8044bed" width="300" alt="Boia MVP1"> | |
| *Estrutura da Boia* | | |

## ⚡ Esquemas Elétricos e Layouts das Placas (PCBs)

Abaixo estão dispostos os esquemáticos elétricos e os layouts das placas de circuito impresso desenvolvidas para os dois módulos do MVP 1.


### 🗼 1. Placa do Módulo de Margem (Torre)

| Esquemático da Placa da Torre | Layout da Placa da Torre |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/8b34c723-a216-4ce0-9c65-293664d81be7" width="400" alt="Esquemático Torre"> | <img src="https://github.com/user-attachments/assets/d96cb8a4-1a3a-41ae-8964-0e7b6b833f5b" width="400" alt="Layout PCB Torre"> |
| *Diagrama esquemático das conexões da Torre* | *Layout do circuito impresso (PCB) da Torre* |


## 🎥 Demonstração de Funcionamento e Ensaio em Campo


<p align="center">
  <img src="https://github.com/user-attachments/assets/415757a4-f066-411c-b4a9-e7057caa597b" width="600" alt="Video do Hardware MVP 1">
</p>
<p align="center">
<img width="960" height="1280" alt="Equipe envolvida no desenvolvimento" src="https://github.com/user-attachments/assets/39ff3933-7ae0-4abc-a47b-516ef66b5d7a" />
</p>

---
