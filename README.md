# Invernadero Inteligente – Arduino + C# Windows Forms

Sistema de invernadero inteligente que combina **Arduino** y una aplicación de escritorio en **C# / Windows Forms** para monitorear y controlar variables como temperatura, humedad del aire, humedad de suelo y luz, además de gestionar el riego automático.

---

## 🧩 Objetivo del sistema

- Monitorear en tiempo real las condiciones del invernadero.
- Activar/desactivar el riego automáticamente según la humedad del suelo.
- Generar alertas (buzzer) ante condiciones críticas.
- Permitir control manual desde una aplicación en C#.

---

## 🛠️ Tecnologías utilizadas

- **Microcontrolador:** Arduino (por ejemplo, Arduino UNO/Mega 2560)
- **Lenguajes:** C/C++ (Arduino), C# (Windows Forms)
- **Sensores:**
  - Sensor de temperatura y humedad (ej. DHT)
  - Sensor de humedad de suelo
  - Sensor de luz (LDR / fotorresistor)
- **Actuadores:**
  - Buzzer
  - Relay
  - Minibomba de agua (sistema de riego)
- **Comunicación:** Puerto serie entre Arduino y la app en C#.

---

## ⚙️ Funcionalidades principales

- Lectura periódica de:
  - Temperatura y humedad del aire.
  - Humedad de suelo.
  - Nivel de luz.
- Envío de datos desde Arduino a C# vía serial.
- Visualización de los datos en una interfaz de Windows Forms.
- Activación automática del riego cuando la humedad de suelo baja de un umbral.
- Control manual del riego y del buzzer desde la aplicación.
- Alertas sonoras (buzzer) ante condiciones críticas.

---

## 🚀 Estado del proyecto

Proyecto académico en desarrollo y mejora continua, enfocado en la integración de hardware (Arduino) con software de escritorio para automatizar procesos dentro de un invernadero.

---

## 👤 Autor

**Diego Díaz**  
Desarrollador de software con formación en Ingeniería de Sistemas.  
Contacto: `ingddiaz30@gmail.com`
