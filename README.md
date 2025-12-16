# HiveRooms

## 📌 Proyecto

**HiveRooms** es una plataforma de comunicación digital inspirada en herramientas modernas como Discord y Kumospace. Integra mensajería en tiempo real, salas virtuales y videoconferencias mediante una arquitectura de microservicios, priorizando escalabilidad, seguridad y experiencia de usuario.

## 👥 Equipo

| Usuario      | Nombre Completo                |
| ------------ | ------------------------------ |
| Jomelgar     | Johnny Josué Melgar Machorro   |
| Jeff         | Jeffrey Alejandro Torres Solís |
| Reyesalv20   | Ruth Abigail Reyes Alvarado    |
| bryanbanegas | Bryan Adalberto Banegas Molina |
| AlliVilla    | Allison Lucero Villamil Toledo |
| Hectovargas  | Héctor Stefano Vargas Castro   |
| Rpaz17       | Rebeca Alejandra Paz Guevara   |
| haroldstx    | Harold Joseph Peña Diaz        |
| danielodg    | Daniel Omar Dubon García       |

**Ingeniero:** Ing. Elvin Deras
**Fecha:** 15/12/2025
**Universidad:** Universidad Tecnológica de Centroamérica (UNITEC)

## 🎯 Objetivos

### Objetivo General

Desarrollar una plataforma basada en microservicios que integre mensajería, videoconferencia y gestión de usuarios utilizando tecnologías modernas como Rocket.Chat, Jitsi, WebSockets y autenticación JWT.

### Objetivos Específicos

* Implementar mensajería en tiempo real con Rocket.Chat.
* Diseñar una arquitectura distribuida y escalable.
* Integrar autenticación segura mediante JWT.
* Facilitar videollamadas usando Jitsi (JaaS).

## 🧠 Arquitectura del Sistema

* **Frontend:** React 18, Vite, Tailwind CSS, Shadcn UI
* **Backend:** Node.js (Express), Sequelize
* **Base de Datos:** PostgreSQL y MongoDB
* **Comunicación en Tiempo Real:** WebSockets
* **Servicios Externos:** Rocket.Chat, Jitsi (JaaS)
* **Autenticación:** JWT
* **Infraestructura:** Docker y Docker Compose

## 🚀 Instalación Local

### Requisitos

* Git
* Docker y Docker Compose
* Node.js (para desarrollo sin Docker)

### Frontend

```bash
git clone https://github.com/Jomelgar/HiveRooms-Project.git
npm install
npm run dev
```

### Backend (Docker)

```bash
docker compose up --build -d
```


## 🧩 Servicios Integrados

### Rocket.Chat

* Mensajería en tiempo real
* Integración vía REST API y WebSockets
* Incrustado mediante iframe

### Jitsi (JaaS)

* Videoconferencias integradas
* Control por JWT
* Salas dinámicas y escalables

## 📘 Documentación Completa

La documentación detallada del proyecto (arquitectura, marco teórico, manual de usuario, anexos y bibliografía) se encuentra en el archivo:

📄 **https://1drv.ms/w/c/2ec538ffeb2a6f29/IQB5coFML_EzTojyD6VzzOaKAUDH7RnUXr9GeaalEvxXlTQ?e=mRhQYL**

## ✅ Conclusión

HiveRooms centraliza la comunicación digital en una sola plataforma moderna, segura y escalable, mejorando la colaboración y productividad mediante mensajería y videoconferencias en tiempo real.
