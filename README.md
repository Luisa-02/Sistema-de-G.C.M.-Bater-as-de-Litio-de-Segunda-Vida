# Sistema-de-G.C.M.-Bater-as-de-Litio-de-Segunda-Vida
Sistema inteligente de gestión y monitoreo para baterías de litio 18650 reutilizadas.
# 🔋 SecondLife-BMS
### Sistema de Gestión, Control y Monitoreo para Baterías de Litio de Segunda Vida

<p align="center">
  <img src="docs/arquitectura.png" width="800">
</p>

---

## 📌 Descripción

SecondLife-BMS es un sistema inteligente de gestión de baterías (BMS) diseñado para monitorear, proteger y controlar bancos de baterías de litio 18650 reutilizadas en configuración 4S2P.

El sistema implementa sensado analógico mediante amplificadores operacionales, monitoreo de temperatura y voltaje por celda, protección contra sobrecarga y sobretemperatura, balanceo de celdas y visualización de datos en tiempo real.

---

## 🎯 Objetivos del Proyecto

- Monitorear voltaje individual de cada celda
- Detectar sobretemperatura
- Implementar protección electrónica
- Realizar balanceo de celdas
- Visualizar datos en tiempo real
- Construir un MVP funcional y profesional

---

## ⚙️ Características Principales

✅ Monitoreo de voltaje por celda  
✅ Sensado de temperatura  
✅ Protección contra sobrevoltaje  
✅ Protección contra subtensión  
✅ Protección térmica  
✅ Balanceo de celdas  
✅ Pantalla OLED integrada  
✅ Interfaz de visualización de datos  
✅ Registro histórico de variables  

---

## 🧠 Arquitectura del Sistema

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
- MATLAB
- EasyEDA / Proteus
- GitHub
- Plataforma IoT

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
├── hardware/
├── firmware/
├── docs/
├── simulations/
├── pcb/
├── app/
└── README.md
```

---

## 📱 Interfaz de Visualización

El sistema cuenta con visualización local mediante pantalla OLED y futura integración con plataformas IoT para monitoreo remoto.

---

## 🚀 Futuras Mejoras

- Estimación de SOH
- Balanceo activo
- Dashboard web
- Aplicación móvil
- Machine Learning para degradación

---

## 👨‍💻 Integrantes

- Nombre 1
- Nombre 2
- Nombre 3

---

## 📸 Prototipo

<p align="center">
  <img src="docs/prototipo.jpg" width="700">
</p>

---

## 📄 Licencia

Proyecto académico - Electrónica II
Universidad del Magdalena
