# 🃏 Truco y Maña — Showcase Profesional

> Plataforma web interactiva que simula y moderniza el clásico juego de cartas españolas argentino **Truco**, integrada con mecánicas RPG (Juego de Rol) y gestión de usuarios en tiempo real. 

---

## 💡 Sobre el Proyecto & Mi Propósito
Este repositorio funciona como un **escaparate técnico (Showcase)** de mi autoría y participación directa dentro del proyecto colaborativo **Truco y Maña**. 

*Nota: Por motivos de confidencialidad y políticas de privacidad del equipo original, el código fuente completo del sistema backend y frontend se encuentra en repositorios privados. Aquí expongo los módulos, la arquitectura y las soluciones en las que trabajé activamente.*

## 🌐 Despliegue de la Aplicación
El sistema se encuentra funcional y desplegado en producción:
* **Acceso a la plataforma:** [trucoymana.vercel.app](https://trucoymana.vercel.app)

🔑 **Credenciales de prueba para ingreso rápido:**
* **Email / Usuario:** `usuarioDemo@mail.com` (o `usuarioDemo`)
* **Contraseña:** `usuarioDemo11`



## 📁 Repositorios
* **Repositorio Frontend:** [GitHub - Frontend](https)
* **Repositorio Backend:** [GitHub - Backend](https)



## 🛠️ Stack Tecnológico Utilizado
* **Backend:** C# | .NET Core | ASP.NET Core Web API | Entity Framework Core
* **Frontend:** Angular | TypeScript | JavaScript | HTML5 | CSS3 | Phaser
* **Base de Datos & Deploy:** MySQL | Aiven | Render | Vercel
* **Testing & Calidad:** Pruebas unitarias (xUnit)
* **Herramientas:** Git | GitHub | Swagger / OpenAPI | Arquitectura Hexagonal



## 👩‍💻 Mi Aporte Técnico Específico

1. **Estructura Inicial del Backend:** Creación y configuración inicial de la solución en ASP.NET Core API, evaluando y tomando decisiones sobre la organización por capas.
2. **Sistema de Identidad y Seguridad (Backend):** Implementación de ASP.NET Core Identity, guardado de roles de jugador en *claims* para autorizar de forma centralizada los controladores del juego.
3. **Gestión de Autenticación y Cliente (Frontend):** 
   * Creación del `authGuard` en Angular para proteger las rutas privadas del sistema.
   * Desarrollo del **JWT Interceptor** para inyectar automáticamente el token *Bearer* en las peticiones HTTP hacia la API.
   * Implementación de la lógica de cierre de sesión (*logout*) con limpieza segura de credenciales locales (`localStorage`).
4. **Optimización de Interfaz (Responsive):** Adaptación del header web incorporando un logotipo estándar y una versión simplificada (*responsive*) optimizada para tablets y celulares.
5. **Testing Unitario y Calidad:** 
   * Desarrollo de pruebas unitarias robustas aplicando la estructura **AAA (Arrange-Act-Assert)**.
   * Uso de **Mocks** para aislar componentes y garantizar que sean pruebas unitarias puras.
6. **Despliegue e Infraestructura (Cloud/Hosting):** Gestión y puesta en producción del backend en **Render**, configuración de bases de datos relacionales en la nube con **Aiven**, y soporte en el despliegue del frontend en **Vercel**.
   
---
⌨️ Desarrollado con 🧡 por [GabiLeve](https://github.com/GabiLeve)

