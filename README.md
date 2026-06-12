# 🌡️ Termostat de Cameră

Acest proiect reprezintă dezvoltarea la nivel software a unui termostat de cameră inteligent. Sistemul măsoară temperatura ambientală și afișează datele, utilizând firmware dezvoltat atât în limbajul **C**, cât și în **Assembly (ASM)**.

## 📌 Descriere și Funcționalități
Proiectul demonstrează interfațarea senzorilor cu microcontrolere și controlul perifericelor la nivel low-level. 
*   **Măsurarea Temperaturii:** Preluarea și procesarea precisă a datelor de la senzorul de temperatură.
*   **Afișare:** Integrare cu un modul LCD pentru afișarea în timp real a parametrilor.
*   **Dual-Firmware:** Implementarea logicii de control folosind două abordări distincte (C și ASM), demonstrând o înțelegere profundă a arhitecturii microcontrolerului.

## 🛠️ Arhitectura Hardware
*   **Microcontrolere:** 8051
*   **Senzor:**  LM35
*   **Display:** Modul LCD 16x2
*   **Mediu de Simulare:** Proteus Design Suite (`SenzTemperatura.pdsprj`)

## 💻 Structura Codului
Repository-ul conține două directoare principale pentru firmware:
*   📁 **`COD C/`**: Implementarea logicii termostatului în limbajul C.
*   📁 **`COD ASM/`**: Rutinele și controlul perifericelor scrise direct în limbaj de asamblare pentru optimizare la nivel de instrucțiune.

## 📄 Documentație Extinsă
Pentru o analiză detaliată a ecuațiilor de conversie, diagrame de stare, calculul componentelor electronice și explicarea codului linie cu linie, consultați fișierul `DOCUMENTATIE.docx` inclus în acest repository.
---
*Proiect dezvoltat în cadrul studiilor de Electronică Aplicată.*
