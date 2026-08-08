# 🚀 Tu Mensajero

> **La Red de Mensajería Libre en Cuba.**[cite: 1]  
> Plataforma tecnológica para conectar directamente a clientes con mensajeros independientes sin intermediarios ni comisiones[cite: 1].

![Licencia](https://img.shields.io/badge/Licencia-MIT-blue.svg)
![Estado](https://img.shields.io/badge/Estado-APK%20Funcional-success.svg)
![Plataforma](https://img.shields.io/badge/Plataforma-Android%20%7C%20Web%20PWA-orange.svg)

---

## 📌 Visión General

**Tu Mensajero** es un directorio inteligente que organiza el mercado de envíos locales en Cuba[cite: 1]. Sustituye la búsqueda desordenada en grupos informales de mensajería por una plataforma centralizada, ligera y eficiente[cite: 1].

* **Para Clientes:** Publican una solicitud, reciben ofertas de mensajeros cercanos, comparan precios/reputación y eligen[cite: 1].
* **Para Mensajeros:** Ven solicitudes activas en el mapa, envían sus postulación con tarifa propia y construyen reputación mediante valoraciones[cite: 1].
* **0% Comisiones:** El pago se acuerda y realiza directamente entre cliente y mensajero[cite: 1].
* **Canal Integrado:** La comunicación final se efectúa vía WhatsApp como canal natural[cite: 1].

---

## 🛠️ Stack Tecnológico

* **Frontend Móvil:** [Flutter](https://flutter.dev/) (APK Android)
* **Versión Web:** Web App Instalable ([PWA](https://web.dev/progressive-web-apps/))[cite: 1]
* **Backend:** [NestJS](https://nestjs.com/)
* **ORM:** [Prisma](https://www.prisma.io/)
* **Base de Datos:** [PostgreSQL 16](https://www.postgresql.org/)
* **Infraestructura:** [Docker](https://www.docker.com/)

---

## ✨ Funcionalidades Principales

### 📱 Para Clientes
- [x] Publicación de solicitudes de envío con origen, destino y descripción[cite: 1].
- [x] Recepción de postulaciones de múltiples mensajeros en tiempo real[cite: 1].
- [x] Consulta de perfiles de mensajeros y sistema de reputación por estrellas[cite: 1].
- [x] Selección del mensajero y contacto directo por WhatsApp[cite: 1].
- [x] Historial de envíos realizados[cite: 1].

### 🛵 Para Mensajeros
- [x] Visualización en mapa de solicitudes cercanas[cite: 1].
- [x] Postulación a envíos con oferta de precio libre[cite: 1].
- [x] Gestión de perfil público y recepción de calificaciones[cite: 1].
- [x] Mantenimiento del 100% de la tarifa cobrada[cite: 1].

---

## 🚀 Próximas Características (Roadmap)

- [ ] **Integración vía API:** Permitir que tiendas virtuales y emprendimientos conecten sus plataformas para solicitar mensajeros automáticamente[cite: 1].
- [ ] Pruebas de alta concurrencia y casos extremos.
- [ ] Modo Oscuro nativo[cite: 1].

---

## ⚙️ Instalación y Configuración Local

### Requisitos previos
* Flutter SDK (`>=3.0.0`)
* Node.js (`>=18.x`) & npm
* Docker & Docker Compose
* PostgreSQL 16

### Clonar el repositorio
```bash
git clone [https://github.com/tu-usuario/tu-mensajero.git](https://github.com/tu-usuario/tu-mensajero.git)
cd tu-mensajero
