# MCC – Mi Clínica Control 🏥👨‍⚕️👩‍⚕️
**BK Programación** | Proyecto desarrollado por: **Irene Condado Alcantarilla**

**Mi Clínica Control (MCC)** es una aplicación web diseñada para resolver los problemas de comunicación y comprensión entre pacientes y profesionales de la salud en el marco de la consulta médica.

En el día a día, los pacientes acumulan una gran cantidad de documentos en papel, anotaciones sobre la evolución de su enfermedad o dudas que surgen entre citas. Al llegar a la consulta, el tiempo disponible suele ser muy limitado para exponer toda esta información. **MCC** optimiza este proceso digitalizándolo: permite centralizar, organizar y acceder a los datos clínicos en cualquier lugar y momento de forma clara y legible.

Para los médicos y clínicas, la plataforma elimina la necesidad de almacenar expedientes físicos ocupando espacio, reduciendo drásticamente el riesgo de pérdida o deterioro de la información y permitiendo un seguimiento del paciente mucho más completo, eficiente y seguro.

---

## 🚀 Tecnologías Utilizadas

El proyecto está desarrollado utilizando un ecosistema moderno y robusto:

* **[Laravel](https://laravel.com/):** Framework PHP para un desarrollo backend seguro y escalable.
* **[Laravel Breeze](https://laravel.com/docs/billing/breeze):** Paquete oficial para la gestión de autenticación ligera (rutas, controladores y vistas preconfiguradas).
* **[Vite](https://vitejs.dev/):** Herramienta de construcción rápida para compilar y servir los assets del frontend.
* **Blade & Bootstrap:** Motor de plantillas nativo de Laravel combinado con Bootstrap para lograr una interfaz de usuario limpia, intuitiva y 100% responsiva.

---

## ✨ Funcionalidades Clave

* **Sistema de Autenticación Completo:** Registro, inicio de sesión y cierre de sesión seguro mediante Laravel Breeze.
* **Control de Accesos por Roles:** Paneles y vistas adaptadas específicamente para tres perfiles de usuario:
    * 🛡️ **Administrador:** Gestión global del sistema.
    * 🥼 **Facultativo (Médico):** Seguimiento de pacientes e historial clínico.
    * 👤 **Paciente:** Consulta de historial, evolución y control de citas.
* **Gestión Integral (CRUD):** Administración completa de usuarios, enlaces médicos y autorizaciones de acceso.

---

## 📋 Requisitos del Sistema

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu entorno de desarrollo:

* PHP >= 8.1
* Composer
* MySQL o MariaDB
* Node.js >= 18
* NPM

---

## 🛠️ Instalación y Configuración

Sigue estos pasos para poner en marcha el proyecto localmente:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/black-cat-17/MCC.git](https://github.com/black-cat-17/MCC.git)
cd MCC```

---
