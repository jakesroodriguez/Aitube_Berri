# 🎨 Design System & UI/UX Guidelines — Aitube Berri Taberna (Móvil & Desktop de Alto Impacto)

> **Documento Oficial de Especificación de Diseño y Arquitectura Frontend**
> **Proyecto:** Aitube Berri Taberna — Single Page Application (SPA)
> **Eslogan Oficial:** *"LE DIMOS LA VUELTA A LA TORTILLA"*
> **Especialidad:** Bar gastronómico vasco galardonado — *Finalistas del Campeonato de España de Tortilla de Patatas*.

---

## 🎯 1. Concepto y Personalidad de Marca

- **Posicionamiento de Marca:** Templo gastronómico de la tortilla artesanal en Urretxu (Gipuzkoa).
- **Innovación en Navegación Móvil & Desktop:**
  - **Escritorio (`md:`):** **Isla Dinámica Flotante (*Dynamic Island Nav*)** inteligente (`fixed top-6 left-1/2 -translate-x-1/2`).
  - **Móvil (`< md:`):** **Cápsula de Marca Superior Móvil** (`fixed top-3 left-1/2`) + **Dock de Navegación Inferior Flotante** (`fixed bottom-4 left-1/2`) con botón flotante central de llamada directa `📞`.

---

## 📱 2. Experiencia Móvil de Alto Rendimiento

- **Cabecera Móvil:** Cápsula flotante en cristal oscuro con punto pulsante `🟢 Abierto`, badge `🏆 Finalista` y llamada en un toque.
- **Hero Móvil:** 
  - Insignia de honor destacada.
  - Titular gigante *"LE DIMOS LA VUELTA A LA <span style="color:#C5A059">TORTILLA</span>"*.
  - Tarjeta fotográfica optimizada para pantalla táctil con overlay de valoración 4.6★.
  - Botones táctiles a pantalla completa.
- **Navegación Táctil Inferior:** Dock flotante con 5 accesos rápidos (*Inicio*, *Tortilla*, *Llamar*, *Opiniones*, *Mapa*).

---

## 🎨 3. Paleta de Colores Exclusiva & Tokens Tailwind

| Rol | Color Hex | Clase Tailwind | Uso Principal |
| :--- | :--- | :--- | :--- |
| **Lienzo Hueso Lino** | `#EFECE6` | `bg-bone-bg` | Fondo de secciones secundarias y tarjetas |
| **Landing Hero Oscuro** | `#121212` | `bg-dark-bg` / `bg-zinc-950` | Fondo principal de la Hero Section y Footer |
| **Cápsula & Dock Móvil** | `rgba(18, 18, 18, 0.95)` | `mobile-header-capsule` / `mobile-dock` | Elementos flotantes táctiles para móviles |
| **Isla Dinámica** | `rgba(18, 18, 18, 0.92)` | `dynamic-island` | Cápsula flotante para escritorio |
| **Oro Bronce (Marca)** | `#C5A059` | `text-gold` / `bg-gold` | Logo, lema, botones principales, estrellas |
| **Oro Gradiente** | `#D4AF37` a `#947128` | `gold-gradient-text` | Tipografía principal y acentos de lujo |
| **Acento Azul Champion**| `#2563EB` | `champion-badge-glow` | Insignia de Finalistas de España |

---

## 🏗️ 4. Estructura de Componentes

1. **Top Header:** Isla Dinámica en escritorio y Cápsula de Marca en móvil.
2. **Hero Landing Section:** Split 2 columnas en ordenador y tarjeta responsiva táctil en móvil.
3. **Módulo de Eslogan Corporativo:** Celebrando *"LE DIMOS LA VUELTA A LA TORTILLA"* con badges de ingredientes naturales.
4. **Bento Box de Especialidades:** Tarjetas elevadas con sombras realistas y efectos `hover-lift`.
5. **Reseñas de Google Maps:** Testimonios reales verificados con calificación 5 estrellas.
6. **Ficha de Ubicación & Horarios:** Datos de Urretxu, horario de cierre (0:00) y llamada directa.
7. **Footer & Botón Inviolable de Autor:** Footer 3 columnas con el snippet intacto de **`@jakesroodriguez`**.
