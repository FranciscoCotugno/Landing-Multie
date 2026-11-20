# Multie — landing

La fuente de verdad es `BIBLIA.md`. Leela antes de proponer o cambiar cualquier escena. Si algo no está ahí, preguntá antes de decidir.

## Reglas que no se rompen

- **Textos:** van tal cual están en el guion de la biblia y en el feedback más reciente. No se reescriben, no se acortan y no se inventan sin aprobación de Cotu. En la página no se nombra cómo se llega a otros países (nada de proxys).
- **Palabras:** "multicuentas", alternada con "teléfonos propios" o "teléfonos reales". Nunca "granja" ni precios. Bots y garantías se mencionan solo en las preguntas frecuentes, con las respuestas aprobadas. No se nombran clientes.
- **Scroll:** con inercia, usando Lenis (`lerp: 0.09`) conectado a GSAP y ScrollTrigger. Es clave.
- **Sin barras de progreso:** nada que marque cuánto falta de una escena. Los pasos 01–04 del proceso sí van, porque son texto del guion.
- **Fondo:** degradado cálido en la apertura y el cierre, negro plano en el medio. Sin estrellas.
- **Teléfonos:** todos salen de un único componente. La interfaz final (TikTok e Instagram) la entregan Cotu y Claude en `componentes/telefono/`: no la rehagas. Las redes se alternan entre teléfonos. Sin halo ni desenfoque.
- **Compu y celular:** la página tiene que funcionar en 1440 px y en 390 px. Ningún objeto tapa un texto. Por decisión de Cotu, ahora se cierra primero la versión de compu y celular se revisa después.
- **Imágenes:** nada de fotos de bancos públicos. Los assets están en `assets/` o los pone Cotu.

## Cómo trabajar

- Los pedidos de cambio están en `feedback/`, uno por revisión. Antes de seguir, leé el más reciente y aplicalo en su orden.

- Una escena por vez, en el orden de la biblia. Antes de programar, mostrá el plan.
- Al terminar cada cambio, sacá capturas en 390 px y 1440 px y revisalas.
- Colores, tipografías, textos y assets van en archivos separados de la lógica (tokens de diseño, contenido y `assets/`). Cotu aprueba todo cambio en esos archivos.
- Si usás taste-skill u otro skill de diseño, respetá la dirección visual de la biblia: no propongas paleta, tipografía ni layout nuevos salvo que te lo pidan.
