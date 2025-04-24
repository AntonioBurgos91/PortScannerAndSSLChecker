# 🛡️ Vulnerability Port Scanner with GUI

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-success)
![Security](https://img.shields.io/badge/Security-Scanner-critical)

> 🖥️ *Una herramienta interactiva desarrollada en Python para escanear puertos, identificar vulnerabilidades comunes y educar sobre ciberseguridad.*

---

## 🚀 Descripción del Proyecto

Este proyecto consiste en un **escáner de puertos con interfaz gráfica** que permite al usuario ingresar una IP o dominio, escanear una lista predefinida de puertos y detectar si están abiertos. Por cada puerto abierto, se muestran los riesgos de seguridad asociados, ayudando a comprender amenazas como:

- Interceptación de datos
- Fuerza bruta de contraseñas
- Inyección SQL
- Acceso remoto no autorizado

Además de su funcionalidad técnica, es una excelente herramienta educativa para aprender sobre ciberseguridad y análisis de red.

---

## 🧰 Tecnologías Utilizadas

- `socket` – para conexiones de red y escaneo de puertos
- `threading` – para ejecutar múltiples escaneos en paralelo
- `tkinter` – para construir la interfaz gráfica de usuario
- `ssl`, `datetime`, `scrolledtext`, `messagebox` – utilidades adicionales

---

## 🎯 Funcionalidades

- 📡 Escaneo de puertos comunes (FTP, Telnet, SMTP, DNS, MySQL, RDP, etc.)
- 🔐 Alerta de vulnerabilidades conocidas según el puerto detectado
- 🧠 Explicaciones educativas sobre posibles ataques
- 🖼️ Interfaz gráfica clara e intuitiva (Tkinter)
- ⚡ Escaneo multihilo para mayor rapidez

---

## 🖼️ Capturas de Pantalla

> (Agrega aquí screenshots del GUI en funcionamiento. Puedes usar `tkinter` para capturar y compartir visualmente el proyecto.)

---

## 📁 Estructura del Proyecto

```bash
.
├── index.ipynb              # Notebook con todo el código del escáner GUI
├── README.md                # Este archivo
└── requirements.txt         # Librerías necesarias para ejecutar el proyecto
