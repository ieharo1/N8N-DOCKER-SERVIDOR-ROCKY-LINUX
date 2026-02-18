# N8N-SERVER-ROCKY LINUX

Repositorio de configuración y despliegue de **n8n** en Rocky Linux 9.7 usando Docker y Docker Compose.  
Incluye la estructura de carpetas, `docker-compose.yml`, y archivos de configuración necesarios para levantar un servidor n8n listo para producción básica.

---

## Descripción

Este proyecto contiene:

- Configuración de servidor n8n en Rocky Linux 9.7
- Docker + Docker Compose
- Carpeta de datos persistentes (`n8n_data`)
- Variables de entorno (excluyendo `.env` por seguridad)
- `docker-compose.yml` actualizado para producción
- `.gitignore` configurado para ignorar archivos sensibles y datos temporales

> **Nota:** El archivo `.env` **NO** debe subirse al repositorio por contener credenciales sensibles.

---

## Estructura del proyecto

```text
/opt/n8n/
├── docker-compose.yml       # Configuración de Docker Compose
├── .gitignore               # Ignora .env y datos sensibles
├── README.md                # Este archivo
├── .env                     # Variables de entorno (NO subir)
└── n8n_data/                # Datos persistentes de n8n

---

## 👨‍💻 Desarrollado por Isaac Esteban Haro Torres

**Ingeniero en Sistemas · Full Stack · Automatización · Data**

- 📧 Email: zackharo1@gmail.com
- 📱 WhatsApp: 098805517
- 💻 GitHub: https://github.com/ieharo1
- 🌐 Portafolio: https://ieharo1.github.io/portafolio-isaac.haro/

---

## 📄 Licencia

© 2026 Isaac Esteban Haro Torres - Todos los derechos reservados.
