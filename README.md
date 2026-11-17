# LoRaWAN Indoor Coverage Dataset – ETSIIAB Albacete (UCLM)

Experimental dataset of LoRaWAN radio link quality (**RSSI** and **SNR**) collected inside the **Edificio Infante Don Juan Manuel** at *Escuela Politécnica Superior de Albacete* (Universidad de Castilla-La Mancha, Spain), developed within the **Living Lab Albacete** initiative.

## Overview

- **Total measurement points:** 51 locations distributed across 3 floors:
  - **First Floor (`P1`):** 22 points
  - **Ground Floor (`P0`):** 24 points
  - **Basement (`S`):** 5 points
- **Spreading Factors evaluated:** `SF7`, `SF9`, and `SF12`.
- **Repetitions per configuration:** 10 consecutive uplink packets per point and Spreading Factor.
- **Network Infrastructure:** Public LoRaWAN network (*The Things Network*, EU868) with gateway located at the nearby *Instituto de Investigación en Informática de Albacete* (I3A).

## Radio & Hardware Configuration

| Parameter | Value |
| :--- | :--- |
| **Frequency Plan** | EU868 (868 MHz) |
| **Bandwidth (BW)** | 125 kHz |
| **Coding Rate (CR)** | 4/5 |
| **Tx Power** | +14 dBm |
| **Device Class** | Class A (OTAA, LoRaWAN 1.1) |
| **Transceiver** | Semtech SX1276 (ESP32 node) |

## Repository Contents

- `Measurements.csv`: Dataset containing the 10 individual RSSI (dBm) and SNR (dB) uplink measurements recorded per location and Spreading Factor.

## Citation

If you use this dataset in your research, please cite the corresponding Bachelor's Thesis (*Trabajo Fin de Grado*):

M. Alarcón, "Caracterización experimental de cobertura LoRaWAN en un edificio público para aplicaciones de monitorización ambiental en el marco de la iniciativa Living Lab Albacete", Universidad de Castilla-La Mancha (UCLM), 2026.
