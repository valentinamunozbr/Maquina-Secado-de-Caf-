# ☕🌱 Secador de Café Inteligente con ESP32

Proyecto desarrollado en **ESP32** para el control automatizado de un **secador de café**.  
El sistema utiliza sensores de humedad y temperatura, control de potencia con una celda Peltier, servomotores y un reloj de tiempo real (RTC) para registrar datos con timestamp.  

---

## 📖 Descripción

El sistema de secado de café busca optimizar el proceso mediante:
- **Monitoreo ambiental** con sensores de temperatura y humedad (DHT22 y DS18B20).
- **Control de temperatura** mediante una **celda Peltier** con gestión de potencia.
- **Apertura y cierre de compuertas** usando un **servo**.
- **Registro de datos con fecha y hora** gracias al **RTC DS3231**.
- **Gestión multitarea** implementada en **FreeRTOS**.
- **Alarmas visuales y sonoras** para condiciones críticas.
- **Envío de datos por puerto serial** con detección de errores en la trama.

---


