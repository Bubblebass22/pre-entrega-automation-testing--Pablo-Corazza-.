# 🧪 QA Automation - Swag Labs

## 📌 Propósito del proyecto
Este proyecto contiene **tests automatizados de QA** para el sitio [Swag Labs](https://www.saucedemo.com), con el objetivo de **validar el login y el inventario de productos**, asegurando que las funcionalidades críticas del sitio funcionen correctamente.

---

## 🛠 Tecnologías utilizadas
- **Python 3.8+**
- **Selenium** (automatización de navegador)
- **Pytest** (framework de testing)
- **WebDriver** compatible con tu navegador (Chrome, Firefox, etc.)

---

## ⚡ Instalación de dependencias

- **pip install -r requirements.txt**

---

## 🚀 Cómo ejecutar las pruebas

**Ejecutar todos los tests y generar un reporte HTML:**

pytest -v --html=reporte.html


-v: salida detallada de los tests

--html=reporte.html: genera un reporte visual en formato HTML en la raíz del proyecto

---

## 📄 Reporte HTML

Después de ejecutar el comando anterior, se generará un archivo llamado reporte.html que contiene:

Estado de cada test (exitoso/fallido)

Tiempo de ejecución

Mensajes de error o aserciones fallidas

Información detallada de la ejecución

Puedes abrir este archivo en cualquier navegador para revisar los resultados de forma visual.


