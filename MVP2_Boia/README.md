# 🛰️ MVP 2 — Estação Flutuante Monobloco (Boia Autônoma 4G)

O **MVP 2** consolida a segunda geração da arquitetura do ecossistema H.I.D.R.A. Esta versão evolui o conceito distribuído para uma **estação flutuante monobloco totalmente integrada e autônoma**, eliminando a necessidade de infraestrutura de margem (torre) e otimizando a eficiência energética e logística de implantação em canais urbanos.

---

## 🛠️ Arquitetura do Sistema e Inovações

- **Processamento Centralizado:** Adoção do microcontrolador **ESP32-S3**, unificando o gerenciamento de energia, a amostragem dos sensores e o protocolo de comunicação em um único núcleo de alta performance.
- **Telemetria Direta via Celular (4G LTE):** Integração do modem **A7670SA**, permitindo o envio autônomo dos dados diretamente da boia para a nuvem/dashboard sem intermediários.
- **Topologia de Sensores Otimizada:** Placa de circuito impresso (PCB) dedicada para o condicionamento dos sinais analógicos e digitais das sondas limnológicas.
- **Operação Ultra-Low Power:** Rotinas de descanso profundo (*Deep Sleep*) e gerenciamento dinâmico de alimentação para operação autossustentável via sistema fotovoltaico compacto.

---

## 📸 Registros de Campo (Ensaios Operacionais)

| Ensaio em Campo — Vista Lateral | Ensaio em Campo — Operação |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/bab9130b-93eb-4cdd-9b27-c74381e09ee3" width="350" alt="Boia MVP2 em Campo 1"> | <img src="https://github.com/user-attachments/assets/b7f5b7c7-75db-41ae-b007-f16aa46d8e74" width="350" alt="Boia MVP2 em Campo 2"> |
| *Validação de flutuabilidade <img width="972" height="682" alt="WhatsApp Image 2026-07-21 at 11 18 10 PM" src="https://github.com/user-attachments/assets/00104136-54e6-4a23-aedd-a1801bd3d950" />
 no Canal da Cohab* | *Estação autônoma realizando medições e telemetria em tempo real* |


---

## ⚡ Hardware, Esquemáticos e Conexões

Abaixo estão apresentados o esquema elétrico da placa de circuito impresso dedicada, o modelo de layout (PCB) e o diagrama de conexões com os sensores físico-químicos.

### 1. Placa de Circuito Impresso (PCB Integrada)

| Esquemático Elétrico da PCB | Modelo / Layout da PCB |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/53e3424c-673b-4919-a7e0-2da727907689" width="400" alt="Esquemático PCB MVP2"> | <img src="https://github.com/user-attachments/assets/3518b85e-5728-45a7-9a4b-2ff115f4940b" width="400" alt="Modelo PCB MVP2"> |
| *Esquema elétrico da placa de condicionamento e processamento* | *Layout do circuito impresso (PCB) projetado para a boia* |

---

### 2. Diagrama de Interconexão dos Sensores

| Esquema de Ligação dos Sensores com a PCB |
| :---: |
| <img src="https://github.com/user-attachments/assets/34947acd-4f16-4546-a19f-c1e18e53c96e" width="600" alt="Ligação dos Sensores com a PCB"> |
| *Mapeamento de pinagem, barramentos de sinal e alimentação das sondas limnológicas* |

---

## 🎥 Demonstração de Funcionamento em Campo



---

## 📄 Arquivos do Projeto para Download

