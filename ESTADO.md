# Calculadora de precios — estado

- Pública desde 15-oct-2026: https://calculadora.aprendeiadecero.com (Netlify, sitio `calculadora-aprendeiadecero`, id a009d9be-0c5e-4c8c-8fee-4daefcb97bc1; subdominio en la zona DNS de Netlify de aprendeiadecero.com).
- Código: https://github.com/jainierrojas-arch/calculadora-de-precios (público).
- La fuente de trabajo sigue en `~/Desktop/Editor de video Academia/academia-ia/herramientas/calculadora_cotizacion.html`; `index.html` es esa misma página con <head> completo (meta, favicon, OG) y pie con enlace a aprendeiadecero.com.
- Publicar cambios: `netlify deploy --prod --dir . --site a009d9be-0c5e-4c8c-8fee-4daefcb97bc1` (no está conectado a GitHub para auto-deploy).
- Sin IA por dentro: no gasta tokens. Solo visitas de Netlify (plan gratis).
- Siguiente idea: constructor de presupuestos con términos y condiciones (leer antes los documentos de Jainier).

- 15-oct-2026: nuevo aspecto (v9) con la marca de aprendeiadecero.com: fondo oscuro con puntos y brillo rojo, letra Archivo Black, título en rojo + contorno, tarjetas con casilla ✓, precio en vivo como ticket. Si el sistema está en modo claro, sale clara. Publicado en el subdominio y en GitHub.

- 15-oct-2026 (v10): mensualidad nueva. Paso 4 «Mensualidad»: planes Básico/Estándar/Prioritario (horas ×1/×2/×3), qué incluye y qué no, servicios reales (dominio, Netlify Personal $9, Twilio, n8n, Claude Haiku 5.5, WhatsApp por país) y pago por uso (uso incluido Poco/Normal/Mucho + cada uso extra a 3× el costo). Ahora son 6 preguntas. Ejemplo barbería Colombia: mensualidad USD 21 → USD 105.
