# Work Test - Kim

## 🎯 Objetivo

Crear una aplicación web para descubrir eventos musicales, conciertos y shows en vivo, donde los usuarios puedan comprar tickets, guardar eventos favoritos y explorar artistas.

---

## 🎯 Requisitos Funcionales

### Must Have (Esenciales)

#### 1. Autenticación de usuarios
- Registro e inicio de sesión con Supabase Auth.
- Protección de rutas privadas

#### 2. Catálogo de eventos
- Listado de eventos musicales/shows (usar la seed data)
- Filtros por: ciudad, fecha y artista.
- Vista de detalle del evento:
  - Nombre del artista/banda
  - Venue (lugar del evento)

#### 3. Sistema de Ticketing
- Selección de tipo de ticket y cantidad
- Carrito de compras
- Checkout flow (simulado, sin integración de pago real)
- Confirmación de compra con código QR único generado

---

## 🛠️ Stack Técnico Requerido

- **Frontend**: Next.js 14+ (App Router), React, TypeScript
- **Backend/DB**: Supabase (Auth, Database)
- **Styling**: Libre elección (Tailwind recomendado)
- **State Management**: Zustand o Context API
- **Generación QR**: Librería como `qrcode` o similar

---

## 📦 Entregables

### 1. Codebase
- Repositorio GitHub con código limpio y organizado
- README completo con instrucciones
- Archivo `.env.example` con variables necesarias

### 2. Deploy funcional
- Aplicación desplegada en Vercel
- URL pública accesible

---

## ⭐ Bonus Points (Opcionales)

- **Integración con Spotify API**: 
  - Mostrar preview de canciones del artista
  - Top tracks del artista
  - Vincular perfil de Spotify del usuario

- **Reseñas y ratings**: Los usuarios pueden calificar eventos pasados

- **Sistema de recomendaciones**: Sugerir eventos basados en gustos del usuario

- **Email confirmación**: Envío de ticket por email usando Supabase Edge Functions

- **Dashboard administrativo**: Panel para crear/editar/eliminar eventos

---

## 🎨 Diseño

- Libertad creativa en UI/UX
- Se valorará diseño moderno, intuitivo
