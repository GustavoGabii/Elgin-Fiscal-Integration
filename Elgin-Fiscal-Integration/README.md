# Elgin Fiscal Integration (Java)

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-%20Finalizado-green?style=for-the-badge)
![Maintained](https://img.shields.io/badge/Mantido-Sim-blue?style=for-the-badge)

> Projeto desenvolvido em Java para comunicação e automação de impressoras **Elgin i9**, focado em emissão de cupons e comandos via protocolo **ESC/POS**.

---

## 📌 Sobre o Projeto

Este repositório contém a implementação de uma ponte de comunicação entre sistemas Java e o hardware da Elgin. O projeto foi estruturado para facilitar o envio de comandos de texto, formatação e acionamento de periféricos (como guilhotina e gaveta).

Este trabalho faz parte da disciplina de **Programação Orientada a Objetos (Turma ADS B)**.

---

## 🚀 Funcionalidades Implementadas

| Funcionalidade | Descrição | Status |
| :--- | :--- | :---: |
| **Conexão Direta** | Identificação e abertura de portas (USB/Serial). | ✅ |
| **Impressão Simples** | Envio de strings para o buffer da impressora. | ✅ |
| **Comandos ESC/POS** | Negrito, sublinhado e alinhamento de texto. | ✅ |
| **Corte de Papel** | Acionamento automático da guilhotina. | ✅ |
| **QR Code** | Geração e impressão de códigos para cupons fiscais. | ⏳ |

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Java 17
* **IDE:** IntelliJ IDEA
* **Protocolo:** ESC/POS (Epson Standard Code for Point of Sale)
* **Hardware Alvo:** Elgin i9 / i7

---

## 📂 Estrutura de Pastas

```text
├── /lib           # Drivers e SDKs da Elgin (DLLs/JARs)
├── /src           # Código-fonte (.java)
└── /docs          # Manuais de referência ESC/POS da Elgin

