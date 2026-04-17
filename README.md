# 🚲 Sistema de Gestión Operativa y Taller - Mister Bike

## 📋 Sobre el Proyecto
Este proyecto consistió en la digitalización y modernización integral de un local comercial de bicicletas ("Mister Bike"). El objetivo principal fue migrar de un sistema de gestión analógico (basado íntegramente en papel) a un entorno digital centralizado.

**El Problema:**
La administración manual generaba pérdida ocasional de información, demoras significativas al buscar el historial de reparaciones de los clientes y dificultades para llevar un control exacto del stock y los flujos de caja diarios.

**La Solución:**
Diseño e implementación de un sistema de gestión basado en Google Sheets. Para optimizar el rendimiento y garantizar la integridad de los datos, el sistema fue diseñado aplicando separación de responsabilidades en **dos módulos independientes**: uno exclusivo para la dinámica del taller y otro para la administración de la tienda.

---

## 🛠️ Módulo 1: Gestión de Taller

Este módulo está enfocado en la trazabilidad de las reparaciones y la atención al cliente.

**Características principales:**
* Registro de ingreso y egreso de bicicletas.
* Seguimiento del estado de las reparaciones en tiempo real (Pendiente, En proceso, Terminado).
* Base de datos de clientes para agilizar el contacto, mantener el historial técnico y mejorar la fidelización.

### Capturas del Módulo Taller:
<img src="https://github.com/user-attachments/assets/70728b51-09b0-4a52-82ab-eba955f7ecd1" alt="Dashboard del Taller" width="800">
<img src="https://github.com/user-attachments/assets/fa2b1108-b9b3-4dc1-bbbd-86f26ca419c4" alt="Seguimiento de Clientes - Taller" width="800">

## 📦 Módulo 2: Administración y Tienda

Este módulo maneja la lógica de negocio, inventario y finanzas.

**Características principales:**
* Control automatizado de stock de repuestos y bicicletas.
* Alertas visuales de faltantes.
* Registro de ventas directas.
* Control del flujo de caja (ingresos y egresos diarios/mensuales).

### Capturas del Módulo Tienda:
<img src="https://github.com/user-attachments/assets/fa461000-9e2f-496c-93a0-beb57dd01e6b" alt="Control de Stock e Inventario" width="800">
<img src="https://github.com/user-attachments/assets/773530c6-4ea4-4a12-9eef-9732816f85f5" alt="Registro de Ventas y Caja Diaria" width="800">

---

## 💻 Tecnologías y Herramientas Utilizadas
* **Google Sheets / Excel:** Fórmulas avanzadas, validación de datos, cruce de información y formato condicional para alertas visuales.
* **Lógica de Sistemas:** Diseño modular, separación de responsabilidades y estructuración de bases de datos relacionales simples.
