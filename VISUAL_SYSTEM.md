# Sistema Visual y Reglas de UX - Portfolio Hugo

Este documento describe las decisiones de diseño y las reglas de experiencia de usuario aplicadas en el portfolio.

## 🎨 Estilo Visual

### Paleta de Colores
- **Primario:** `#2563eb` (Blue 600) - Utilizado para acciones principales, enlaces y acentos destacados.
- **Fondo:** `#ffffff` (Blanco) en modo claro, `#0f172a` (Slate 900) en modo oscuro.
- **Superficie:** `#f8fafc` / `#1e293b` - Para tarjetas y fondos de sección alternos.
- **Texto:** `#0f172a` / `#f8fafc` - Alto contraste para legibilidad.

### Tipografía
- **San Serif (Cuerpo y Títulos):** 'Inter', system-ui. Prioriza la legibilidad y el rendimiento al usar fuentes del sistema.
- **Escala:**
  - Hero: 3.5rem
  - H1: 2.5rem
  - H2: 1.8rem
  - Cuerpo: 1rem (16px)

### Espaciado y Radio
- Basado en un sistema de 4px (`0.25rem`).
- Border-radius generoso (`1rem` para tarjetas) para un aspecto moderno y amigable.

## 🧱 Componentes Reutilizables

1.  **Hero:** Diseñado para captar la atención inmediatamente con un título claro y una llamada a la acción (CTA).
2.  **Card:** Layout consistente para proyectos y posts. Incluye tags para categorización rápida.
3.  **Timeline:** Visualización vertical de la experiencia laboral, optimizada para lectura secuencial.

## 🧠 Reglas de UX

1.  **Mobile First:** Todos los layouts son responsivos usando CSS Grid y Flexbox.
2.  **Contraste y Accesibilidad:** Colores elegidos para cumplir con estándares WCAG de legibilidad.
3.  **Jerarquía Visual:** Uso de pesos de fuente y espaciado para guiar el ojo del usuario desde lo más importante (Hero) hacia el detalle (Proyectos/Blog).
4.  **Feedback Visual:** Transiciones suaves en enlaces y tarjetas (`transform: translateY`) para indicar interactividad.
5.  **Modo Oscuro Nativo:** Soporte automático basado en las preferencias del sistema del usuario.
6.  **Rendimiento:** Carga crítica mínima. No dependemos de frameworks pesados de JS o CSS externo.
