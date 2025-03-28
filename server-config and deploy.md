# SERVER CONFIGURATION AND APPLICATIONS DEPLOYED PRACTICE

Este proyecto forma parte de la práctica de despliegue de aplicaciones web y configuración de servidores. Se han desplegado tanto un frontend hecho con React como un backend completo con Node.js, Express y MongoDB (Nodepop), incluyendo renderizado del lado del servidor (SSR) y una API REST.

---

## 🖥️ Aplicaciones desplegadas

### 🔹 Frontend - React

- **URL:** [http://react.roberwd17.duckdns.org/login](http://react.roberwd17.duckdns.org/login)
- **Descripción:** Interfaz de usuario desarrollada en React que consume la API REST del backend. Permite autenticarse, visualizar anuncios y gestionar la sesión.

---

### 🔹 Backend - Nodepop (SSR + API)
- tarda un poquito en arrancar
- **URL:** [http://roberwd17.duckdns.org](http://roberwd17.duckdns.org)
- **Descripción:** Aplicación web desarrollada con Node.js y Express. Incluye:
  - Renderizado con EJS para la parte SSR.
  - API REST para gestión de usuarios y anuncios.
  - Autenticación mediante JWT.
  - Conexión a base de datos MongoDB.
  
---

## 📦 Tecnologías utilizadas

- Ubuntu Server en AWS EC2
- NGINX como reverse proxy
- PM2 para gestión de procesos Node.js
- React + Vite (Frontend)
- Node.js + Express (Backend SSR/API)
- MongoDB (base de datos)
- DNS gestionado con DuckDNS

---

## ⚙️ Configuración del servidor

- Servidor desplegado en una instancia EC2 con Ubuntu 22.04
- NGINX configurado para servir ambas aplicaciones en subdominios distintos
- Supervisor configurado para la automatización de arranque y restarts de las apps deployadas

---

## 🔐 Acceso
- Creacion de users bloqueada por seguridad. 
- Para acceder a la aplicación React: ir a `/login` para autenticarse
- El backend SSR muestra los productos del usuario autenticado
- El endpoint `/api/` ofrece acceso a la API REST completa

---

## 🧪 Estado

✅ Proyecto finalizado y funcional  
📁 Estructura organizada y código documentado

---

## ✍️ Autor

Roberto Gomez  
[GitHub](https://github.com/Rober040992)