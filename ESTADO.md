# Calculadora de precios — estado

- Pública desde 15-oct-2026: https://calculadora.aprendeiadecero.com (Netlify, sitio `calculadora-aprendeiadecero`, id a009d9be-0c5e-4c8c-8fee-4daefcb97bc1; subdominio en la zona DNS de Netlify de aprendeiadecero.com).
- Código: https://github.com/jainierrojas-arch/calculadora-de-precios (público).
- La fuente de trabajo sigue en `~/Desktop/Editor de video Academia/academia-ia/herramientas/calculadora_cotizacion.html`; `index.html` es esa misma página con <head> completo (meta, favicon, OG) y pie con enlace a aprendeiadecero.com.
- Publicar cambios: `netlify deploy --prod --dir . --site a009d9be-0c5e-4c8c-8fee-4daefcb97bc1` (no está conectado a GitHub para auto-deploy).
- Sin IA por dentro: no gasta tokens. Solo visitas de Netlify (plan gratis).
- Siguiente idea: constructor de presupuestos con términos y condiciones (leer antes los documentos de Jainier).

- 15-oct-2026: nuevo aspecto (v9) con la marca de aprendeiadecero.com: fondo oscuro con puntos y brillo rojo, letra Archivo Black, título en rojo + contorno, tarjetas con casilla ✓, precio en vivo como ticket. Si el sistema está en modo claro, sale clara. Publicado en el subdominio y en GitHub.

- 15-oct-2026 (v10): mensualidad nueva. Paso 4 «Mensualidad»: planes Básico/Estándar/Prioritario (horas ×1/×2/×3), qué incluye y qué no, servicios reales (dominio, Netlify Personal $9, Twilio, n8n, Claude Haiku 5.5, WhatsApp por país) y pago por uso (uso incluido Poco/Normal/Mucho + cada uso extra a 3× el costo). Ahora son 6 preguntas. Ejemplo barbería Colombia: mensualidad USD 21 → USD 105.

- 15-oct-2026 (v11): cada servicio tiene versión Básica (lo más importante, ~la mitad de horas) y Premium (más cosas; lo que ya trae no se cobra como extra). Ejemplo barbería Colombia ahora: app Básica + plan Básico = USD 300 + USD 35/mes (antes USD 980 + 105).

- 15-oct-2026 (v12): paso «Valor» en tiempo y en dinero: horas a la semana que le ahorra + sueldo de quien hace ese trabajo (en su moneda) → horas al mes, días de trabajo y su valor; + dinero extra. Resultado «Lo que gana el cliente»: lo que le deja al mes/año, meses para recuperar la construcción DESPUÉS de pagar la mensualidad, y cuánto recibe por cada $1 de mensualidad (avisa si la mensualidad cuesta más de lo que deja). Va también en el resumen que se copia.
- PENDIENTE (él dirá cuándo): constructor de presupuestos = cotización + contrato listo para firmar (cláusulas y condiciones) + casilla con nombre y datos del cliente que se llenan solos. Leer antes sus documentos.

- 15-oct-2026 (v13): paso 8 «Contrato»: tus datos (guardados en el navegador) + datos del cliente + proyecto (fecha, semanas sugeridas = horas/20, esquema de pago 50/50 · 40/30/30 · 100) + «tus reglas» (sugeridas y editables: validez 15 d, 2 rondas, 5 días hábiles para revisar, garantía 30 d, pausa por atraso 15 d, aviso mensualidad 30 d). Genera cotización + contrato (14 cláusulas escritas con nuestras palabras a partir de las ideas de las guías) en hoja neutra blanco/negro, editable tocando el texto, y «Descargar PDF» (imprimir → Guardar como PDF). Aviso: estimado + guía, no asesoría legal.
