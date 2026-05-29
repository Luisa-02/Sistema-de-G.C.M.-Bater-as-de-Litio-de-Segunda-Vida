# 🔋 SecondLife-BMS
![ESP32](https://img.shields.io/badge/ESP32-Microcontroller-00F5FF?style=for-the-badge&logo=espressif&logoColor=black)
![BMS](https://img.shields.io/badge/System-BMS-8B5CF6?style=for-the-badge&logo=battery&logoColor=white)
![Battery](https://img.shields.io/badge/Battery-18650-FF0080?style=for-the-badge&logo=tesla&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-FF3131?style=for-the-badge&logo=github&logoColor=white)
![Firebase](https://img.shields.io/badge/Software-MATLAB-0066FF?style=for-the-badge&logo=mathworks&logoColor=white)
![Proteus](https://img.shields.io/badge/Simulation-Proteus-7F00FF?style=for-the-badge&logo=circuitverse&logoColor=white)


### Sistema de Gestión, Control y Monitoreo para Baterías de Litio de Segunda Vida

<p align="center">
  <img src="docs/arquitectura.png" width="800">
</p>

---

##  Descripción

SecondLife-BMS es un sistema inteligente de gestión de baterías (BMS) diseñado para monitorear, proteger y controlar bancos de baterías de litio 18650 reutilizadas en configuración 4S2P.

El sistema implementa sensado analógico mediante amplificadores operacionales, monitoreo de temperatura y voltaje por celda, protección contra sobrecarga y sobretemperatura, balanceo de celdas y visualización de datos en tiempo real.

---

##  Objetivos del Proyecto

- Monitorear voltaje individual de cada celda
- Detectar sobretemperatura
- Implementar protección electrónica
- Realizar balanceo de celdas
- Visualizar datos en tiempo real
- Construir un MVP funcional y profesional

---

##  Características Principales

- Monitoreo de voltaje por celda  
- Sensado de temperatura  
- Protección contra sobrevoltaje  
- Protección contra subtensión  
- Protección térmica  
- Balanceo de celdas  
- Pantalla OLED integrada  
- Interfaz de visualización de datos  
- Registro histórico de variables  

---

##  Arquitectura del Sistema

<p align="center">
  <img src="docs/bms-diagram.png" width="900">
</p>

---

## 🔌 Hardware Utilizado

| Componente | Descripción |
|---|---|
| ESP32 | Microcontrolador principal |
| LM339 / Operacionales | Comparadores y sensado |
| Celdas 18650 | Banco de baterías |
| MOSFET/BJT | Etapa de potencia |
| Pantalla OLED | Visualización local |
| Sensores térmicos | Protección de temperatura |

---

## 💻 Software Utilizado

- Arduino IDE
- Proteus
- GitHub
- Plataforma web
- Firebase

---

## 📊 Variables Monitoreadas

- Voltaje por celda
- Voltaje total
- Corriente
- Temperatura
- Estado del sistema
- Estado de carga

---

## 🛡️ Protecciones Implementadas

| Protección | Acción |
|---|---|
| Sobrevoltaje | Desconexión |
| Subtensión | Protección de descarga |
| Sobretemperatura | Corte automático |
| Corriente excesiva | Protección del sistema |

---

## 📂 Estructura del Repositorio

```bash
SecondLife-BMS/
│
├── Informe/
├── Simulación/
├── pcb/
├── Plataforma/
├── Presentación/
├── Costos/
└── README.md
```

---

## 📱 Interfaz de Visualización

El sistema cuenta con visualización local en pantalla OLED y mediante una plataforma web creada con JavaScript, utilizando Firebase.

---

##  Integrantes

- Stiven Martínez
- Luisa Peñaranda
- Luis Mercado
- Hashly Palencia
- María Ángel López
---

## 📸 Prototipo

<p align="center">
  <img src="docs/prototipo.jpg" width="700">
</p>

---

##  Licencia

Proyecto académico - Electrónica II
Universidad del Magdalena
