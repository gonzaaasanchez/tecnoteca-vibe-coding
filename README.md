# Vibe Coding: de la Idea al Producto Digital con IA

Trayecto de 8 clases desarrollado en alianza con **eCloud Agency** y **Vercel** para **Tecnoteca Rosario**. Los/as participantes aprenden a crear productos digitales desde cero utilizando inteligencia artificial como compañera de desarrollo.

## Slides del curso

Este repo contiene los slide decks (HTML autocontenido, sin build) de cada clase. Ver [`index.html`](index.html) para la landing con el listado completo, o entrar directo a cada clase:

1. [De la necesidad a la Idea](clases/clase-1.html)
2. [De la Especificación al Diseño](clases/clase-2.html)
3. [Base de datos y APIs](clases/clase-3.html)
4. [Guardando Información](clases/clase-4.html)
5. [Roles y Panel Administrador](clases/clase-5.html)
6. [De Producto Inicial a Producto Vivo](clases/clase-6.html)
7. [Demo Day (clases 7 y 8)](clases/clase-7.html)

> Nota: el programa original divide el Demo Day en clases 7 y 8, pero ambas se cubren en un único slide deck (`clases/clase-7.html`).

## Previsualizar localmente

```bash
# Abrir la landing directamente
open index.html

# O servir con Python para evitar problemas de fuentes/rutas
python3 -m http.server 8000
# luego visitar http://localhost:8000
```

## ¿Qué es el Vibe Coding?

Es una nueva forma de crear productos digitales, aplicaciones, páginas web, usando inteligencia artificial como compañera de desarrollo. En lugar de escribir código a mano línea por línea, le describís a la IA lo que querés construir, y ella te ayuda a programarlo. Vos seguís tomando las decisiones importantes: cómo se ve, cómo funciona y qué problema resuelve. Es una práctica que está cambiando la forma en que hoy se construye software en todo el mundo.

## ¿Por qué no necesito conocer de código?

Porque la herramienta que vamos a usar, V0 de Vercel, entiende instrucciones escritas en lenguaje cotidiano. A través de prompts específicos, que vas a aprender a construir durante el curso, la IA genera el código y modifica el producto según lo que vos le indiques. Tu trabajo no es programar, sino pensar como creador de producto: entender qué necesita el usuario, tomar decisiones de diseño y guiar a la IA para que construya lo que tenés en mente.

## ¿Qué vas a hacer en el curso?

Vas a desarrollar un proyecto real, recorriendo todo el proceso de creación de un producto digital:

- Definir la idea: qué vas a crear y para quién
- Diseñar la interfaz: cómo se va a ver y usar
- Construir con IA: ir generando funcionalidades reales con V0
- Publicarlo en internet: que cualquiera pueda acceder y probarlo
- Iterar: mejorarlo en base a la experiencia de usuario

Al finalizar el curso, vas a tener un producto funcional, publicado en internet, creado por vos mismo/a.

## Plan de estudio

### Clase 1 - De la necesidad a la Idea

**Objetivo:** Comprender los fundamentos del Vibe Coding como nueva metodología de creación de productos digitales asistida por inteligencia artificial, identificando problemas reales y oportunidades de mejora para definir una propuesta de producto con foco en las necesidades de los usuarios.

**Temas principales:**
- ¿Qué es el Vibe Coding?
- Formación de equipos de trabajo.
- El rol de la IA en el desarrollo de productos digitales.
- Detección de problemas y oportunidades.
- Definición del usuario objetivo.
- Delimitación y validación inicial de la idea.

**Entregable:** Definición del proyecto grupal y propuesta de valor inicial.

### Clase 2 - De la Especificación al Diseño: primera interfaz web publicada en internet

**Objetivo:** Transformar una idea en una primera solución visual funcional, aprendiendo a utilizar herramientas de generación de interfaces mediante IA para diseñar, iterar y publicar un producto digital sin necesidad de programar.

**Temas principales:**
- Introducción a v0.
- Principios básicos de UX/UI.
- Construcción de prompts para diseño.
- Generación de interfaces.
- Iteración de diseños.
- Publicación inicial del producto.

**Entregable:** Primera versión visual del producto publicada en internet.

### Clase 3 - Usuarios, Base de datos y primeras funcionalidades dinámicas

**Objetivo:** Incorporar funcionalidades dinámicas al producto mediante la conexión a una base de datos y la implementación de autenticación de usuarios, comprendiendo cómo las aplicaciones gestionan información y acceso para distintos tipos de usuarios.

**Temas principales:**
- ¿Qué es una API? Integración de servicios externos.
- Flujos de información.
- Datos temporales vs. persistentes.
- Conexión a base de datos.
- Modelo de datos inicial.
- Registro y autenticación de usuarios (login/signup).
- Primer CRUD básico.
- Introducción a roles.
- Introducción al panel administrador.

**Entregable:** Un producto conectado a una base de datos real, con un sistema de registro e inicio de sesión funcionando, primeras entidades creadas y al menos un CRUD básico implementado. Además, se deberá contar con una diferenciación inicial de usuarios (usuario y administrador) y un esqueleto de panel administrador listo para evolucionar en las siguientes clases.

### Clase 4 - Persistencia, roles y panel administrador

**Objetivo:** Profundizar en el manejo de datos persistentes, completando operaciones CRUD y construyendo un sistema de roles con un panel administrador funcional para gestionar la información de la aplicación.

**Temas principales:**
- Profundización del modelo de datos y relaciones.
- Ampliación de CRUD sobre entidades principales.
- Validaciones y consistencia de datos.
- Gestión de permisos según roles (usuario vs admin).
- Construcción y evolución del panel administrador.
- Priorización de funcionalidades.

**Entregable:** Un producto con operaciones CRUD completas sobre las entidades principales, un sistema de usuarios con roles funcionando correctamente y un panel administrador funcional que permita visualizar y gestionar la información desde un dashboard con acciones básicas.

### Clase 5 - De Producto Inicial a Producto Vivo

**Objetivo:** Evolucionar el producto incorporando mejoras funcionales y de experiencia, completando el panel administrador e integrando envío de emails para habilitar flujos reales de uso.

**Temas principales:**
- Análisis del uso del producto y recolección de feedback.
- Mejora de experiencia de usuario.
- Accesibilidad y rendimiento.
- Finalización del panel administrador.
- Incorporación de nuevas funcionalidades al dashboard.
- Introducción al envío de emails.
- Integración de emails en flujos del producto.
- Configuración de Resend.

**Entregable:** Un producto con el panel administrador completo, funcionalidades mejoradas a partir del uso y feedback, y al menos un flujo de envío de emails funcionando correctamente dentro de la aplicación.

### Clase 6 - Pre Demo

**Objetivo:** Preparar el producto para su presentación final, dejándolo listo para producción, con dominio propio y configuración completa de despliegue.

**Temas principales:**
- Chequeo general del producto.
- Preparación para la demo.
- Compra de dominio (Nic).
- Configuración de dominio.
- Despliegue en Vercel.
- Configuración final de integraciones (Resend).
- Chequeo general del producto.

**Entregable:** Producto listo para producción, desplegado en internet con dominio propio, todas las integraciones funcionando y preparado para su presentación final.

### Clases 7 y 8 - Demo Day: Presentación de producto listo

**Objetivo:** Comunicar de manera efectiva el proceso de creación del producto, demostrando su funcionamiento, justificando las decisiones tomadas durante el desarrollo y reflexionando sobre los aprendizajes obtenidos a lo largo del curso.

**Temas principales:**
- Preparación final del producto.
- Storytelling de producto.
- Presentación y demostración.
- Reflexión sobre aprendizajes.
- Próximos pasos: Esto es el comienzo, no el fin.

**Entregable:** Presentación final del proyecto con demostración funcional, relato de producto y publicación lista.
