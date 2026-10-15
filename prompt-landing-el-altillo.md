# PROMPT MAESTRO — Landing page «El Altillo · Objetos»

> Copiá todo lo que sigue y pegalo como prompt en el modelo/herramienta que vaya a construir la web.

---

## 0. Rol y mandato

Actuá como un estudio senior de diseño web + creative developer especializado en sitios de diseño industrial (referencias de nivel: Teenage Engineering, Nothing, Dieter Rams/Braun, studios de product design europeos). Tu tarea es construir **la landing page de El Altillo**, un estudio de diseño industrial y materialización de Marcos Juárez, Córdoba, Argentina.

La web tiene que sentirse **viva**: un taller en funcionamiento. Máquinas que trabajan, piezas que se materializan, planos que se dibujan solos. No es una web “linda con animaciones”: es una **máquina de taller hecha web**, de precisión, con ritmo, sobria y deliberadamente no genérica.

Entregable: **un único archivo HTML autocontenido**, offline, sin dependencias externas (sin CDN, sin Google Fonts remoto, sin imágenes externas: todo SVG inline / CSS / JS vanilla / canvas). Debe abrir perfecto con doble clic desde `file://` y poder compartirse por WhatsApp. No usar localStorage ni nada que falle en `file://`.

Pie de página obligatorio, visible: **«Idea y desarrollo Giuliano G. Biagiotti.»**

---

## 1. Quiénes somos (memoria de marca)

- **Nombre:** El Altillo — Objetos. Instagram: @elaltillo.objetos
- **Bajada oficial:** «Diseño industrial · Materialización»
- **Bio actual:** «Objetos con algo distinto.»
- **Claim de lanzamiento (ya usado en IG, mantenerlo como ADN):** «Objetos que vale la pena encontrar.»
- **Otro claim existente:** «Del sueño al objeto.» / «Así nace un objeto en El Altillo. Del croquis en pantalla a la pieza terminada. No hay pasos menores: cada detalle se piensa, se prueba y se ajusta antes de pasar al siguiente.»
- **Ubicación:** Marcos Juárez, Córdoba. El taller funciona literalmente en un altillo.
- **Equipo:** diseño industrial a cargo de Agustina Massei; gestión técnica de proyectos/productos a cargo de Giuliano G. Biagiotti.
- **Canal de contacto actual:** pedidos por mensaje directo de Instagram (dejar además un botón WhatsApp con número placeholder `+54 9 XXXX XXXXXX` para reemplazar).

### Posicionamiento
Marca **aspiracional, snob, de pertenencia**. Le habla a alguien que quiere tener *el* objeto que nadie más tiene, y a empresas que quieren que su marca se toque. Tono: seguro, breve, técnico-poético. Nada de “¡Hola! 😊”, nada de exceso de signos. Frases cortas. Silencios visuales. Precisión.

### Qué hacemos (servicios)
1. **Diseño industrial de objetos** — desde cero, a pedido. Forma, función, material, fabricabilidad.
2. **Materialización** — llevamos la idea a pieza física: impresión 3D, corte y grabado láser, mecanizado, terminaciones. «Usamos todo»: la impresión 3D es una herramienta más, no el negocio.
3. **Project management / gestión técnica de proyectos y productos** — para marcas y empresas. Escuchamos y, desde el minuto siguiente, hay cronograma, hitos, proveedores, costos y control. Somos el puente entre la idea y la fábrica.
4. **Prototipos para empresas** — validación rápida de forma y uso antes de invertir en matricería.
5. **Merch de diseño / objetos corporativos** — piezas con identidad para marcas (no el típico llavero promocional).
6. **Cartelería corpórea e iluminada** — nombres, logos, letras con volumen, con o sin luz.
7. **Objetos para eventos** — souvenirs, piezas de mesa, números decorativos, carteles para torta.

### Hoja de ruta (contarla en la web como narrativa de escala)
**Objetos → Merch → Industrial.** Empezamos con piezas chicas y perfectas; vamos hacia series para marcas y hacia producto industrial. La web debe comunicar que el estudio *ya piensa como industria* aunque hoy fabrique de a una.

### Portfolio real (usar estos productos, representarlos en SVG/ilustración lineal o como “fichas técnicas”, no inventar otros)
| Pieza | Descripción corta |
|---|---|
| Articulados | Pulpo, corazón, ajolote: piezas impresas articuladas, para jugar, regalar o decorar |
| Equilibrio | Set de posavasos con soporte Yin Yang, diseñado desde cero a pedido |
| Posavasos de diseño | Modelos propios o personalizados (forma, colores, logo) + soporte a medida |
| Aliens | Pedido especial para un local comercial (caso B2B: “¿tenés una idea para tu negocio?”) |
| Halloween | Calaveras/personajes estacionales a pedido |
| Jirafa sobre ruedas | Juguete de bordes redondeados y ruedas libres; animal, color y tamaño a elección |
| Colectivo | Juguete de líneas simples, piezas impresas por separado y ensambladas |
| Autito | Eje y ruedas que giran de verdad |
| Números para armar | Juego didáctico 1–9, motricidad |
| Maceta de 2 piezas | Base calada tipo plato + contenedor texturado |
| Maceta acanalada | Cilíndrica, base copa, textura acanalada |
| Maceta espiral | Esférica, olas en espiral, base negra |
| Portalápices facetado | «El diseño también vive en los objetos de todos los días» |
| Corazón continuo | Soporte de celular de una pieza que se pliega dibujando un corazón |
| Nina / Pony | Carteles corpóreos para mesa de torta, con o sin luz |
| Número calado | Número decorativo de líneas onduladas para mesas y sesiones de fotos |
| Silbato llavero | Souvenir personalizado (color, nombre, medida) |

---

## 2. Identidad visual (respetar la del Instagram)

- **Logo:** línea fina crema que dibuja el techo a dos aguas de un altillo; dentro, una **ventana circular con cruz** (ocre) que proyecta un **haz de luz trapezoidal ocre** sobre un **banquito**. Reconstruirlo en SVG inline vectorial limpio. Animación de entrada: la línea del techo se dibuja (stroke-dashoffset), la ventana se “enciende”, el haz de luz se proyecta y aparece el banquito.
- **Paleta base:**
  - Grafito/carbón fondo: `#1E1D1C` / `#262523`
  - Ocre-mostaza de marca: `#C9A13B` (variantes `#B88E2E`, `#E0BC5E`)
  - Crema de línea: `#EDE6D6`
  - Gris piedra para secundarios: `#8A857C`
  - Acento técnico opcional (sólo en planos/HUD): azul plano de cianotipo muy desaturado `#3E5C76`
- **Tipografía:** serif de alto contraste en mayúsculas espaciadas para titulares (como en los posteos: “ARTICULADOS”, “DEL SUEÑO AL OBJETO”) + sans geométrica liviana para texto + monoespaciada para cotas, códigos de pieza y datos técnicos. Como debe ser offline, usar pilas de sistema bien elegidas (ej. `"Cormorant Garamond", "Didot", "Bodoni 72", Georgia, serif` / `"Inter", "Helvetica Neue", Arial, sans-serif` / `"JetBrains Mono", "SF Mono", Consolas, monospace`) o embeber un subset en base64 si el peso lo permite (<150 KB total).
- **Estética de componentes (obligatoria):**
  - **Neumorfismo** para los elementos principales y permanentes: tarjetas de servicio, botones principales, panel de control, perillas, interruptores. Neumorfismo *oscuro* sobre grafito, con sombras dobles sutiles, nada lavado.
  - **Liquid glass** para todo lo efímero: tooltips, toasts, modales de ficha de producto, menú flotante, chips de estado (“IMPRIMIENDO 64 %”), cursor-lens. Vidrio con `backdrop-filter`, refracción leve, borde especular, ruido sutil.
  - Grano/ruido fino general (SVG feTurbulence) para que no se vea plástico.
  - Retícula visible de plano técnico de fondo (líneas finas crema al 4–6 % de opacidad), con cotas y marcas de registro en las esquinas de las secciones.

---

## 3. El concepto: “El taller encendido”

El sitio entero es **un altillo-taller en corte**, visto como un plano técnico que cobra vida. Cada sección es una **estación de trabajo** con su máquina. Al scrollear, “recorremos el taller”: el haz de luz de la ventana del logo funciona como hilo conductor que ilumina la estación activa.

### Máquinas a animar (SVG + CSS/JS, estilo dibujo técnico lineal crema con detalles ocre; todas con movimiento de proceso real, no decorativo)
1. **Taladro de banco (columna):** el cabezal baja con el scroll, el mandril gira (rotación con motion blur simulado), salen virutas en espiral (partículas canvas), el cabezal sube y queda un agujero perfecto en la pieza.
2. **Sierra circular de mesa / sierra sin fin:** el disco gira; una tabla avanza y se corta; aserrín en partículas; las dos mitades se separan con física leve.
3. **Impresora 3D FDM:** el cabezal recorre trayectorias X/Y reales (G-code simulado), la cama baja capa por capa y **la pieza crece capa a capa** (ej. la maceta espiral o el pulpo articulado), con contador de capas y % en un chip liquid glass.
4. **Cortadora/grabadora láser de mesa:** tapa semitransparente; punto de láser ocre brillante que recorre un vector (el logo de El Altillo o un nombre tipo “Nina”), dejando el trazo grabado y un leve humo.
5. **Mesa de planos:** un plano que se **dibuja solo** (stroke animation): vistas ortogonales, cotas, rótulo con “EL ALTILLO — Pieza 001 — Esc. 1:1 — Rev. A”. Un compás o escuadra se mueven.
6. **Estantería de materiales:** carretes de filamento que giran levemente, placas de MDF/acrílico, varillas, tornillería, tarros. Hover sobre cada material → ficha liquid glass con propiedades (PLA, PETG, MDF 3 mm, acrílico, madera, metal).
7. **Banco de terminación y luz:** un cartel corpóreo (“Nina”) se ensambla letra por letra y se enciende con un leve parpadeo de neón LED.

Reglas de movimiento:
- Movimiento **mecánico, con easing de máquina** (aceleración/desaceleración tipo servo, `cubic-bezier` con leve overshoot, pausas de ciclo). Nada de rebotes caricaturescos.
- Las máquinas tienen **estado**: en reposo hacen micro-movimientos (ventilador girando, LED de estado parpadeando); al entrar en viewport ejecutan su ciclo; scroll-linked donde tenga sentido.
- Sonido opcional desactivado por defecto (toggle neumórfico “ruido de taller”: zumbido, clic de servos) generado con WebAudio, sin archivos externos.
- Respetar `prefers-reduced-motion`: cada máquina muestra un fotograma final estático elegante.
- Rendimiento: 60 fps en celular de gama media. Pausar animaciones fuera de viewport (IntersectionObserver). Canvas sólo para partículas.

---

## 4. Estructura de la landing (en este orden)

1. **Hero — “Se enciende el altillo”**
   Pantalla oscura → se dibuja el techo, se enciende la ventana, el haz de luz cae y revela el titular:
   **«Objetos que vale la pena encontrar.»**
   Subtítulo: *Diseño industrial · Materialización · Gestión de proyectos.*
   Detrás, en penumbra, se adivinan las siluetas de las máquinas del taller trabajando en loop lento.
   CTA neumórfico primario: «Contanos tu idea» / secundario: «Ver el taller».
   Chip liquid glass flotante con estado en vivo: «● Taller activo — Marcos Juárez, Cba».

2. **Manifiesto** (texto grande serif, aparece palabra por palabra)
   «No hay pasos menores. Cada detalle se piensa, se prueba y se ajusta antes de pasar al siguiente.»
   + 3 principios en monoespaciado: *Pensar · Probar · Ajustar.*

3. **El proceso — “Del sueño al objeto”** (scroll horizontal o pin, una estación por paso)
   01 Escucha → 02 Cronograma y plan (la gestión arranca ya) → 03 Diseño y plano → 04 Prototipo → 05 Ajuste → 06 Materialización → 07 Entrega/serie.
   Cada paso activa su máquina (mesa de planos, impresora 3D, láser, taladro, sierra, banco de luz). Una barra de progreso tipo línea de tiempo de proyecto (Gantt minimalista) avanza arriba: esto vende el servicio de PM sin decirlo.

4. **Servicios** (grilla de tarjetas neumórficas; al hover cada tarjeta “se presiona” como un botón físico y despliega detalle)
   Diseño industrial · Materialización · Project management · Prototipos para empresas · Merch de diseño · Cartelería corpórea e iluminada · Objetos para eventos.

5. **Project management (sección propia, peso B2B)**
   Título: «Tu producto, gestionado de punta a punta.»
   Dashboard ficticio animado (liquid glass) con cronograma, hitos, semáforo de proveedores, costo por unidad y revisión de plano: muestra que pensamos como industria.
   Bullets: relevamiento técnico, cronograma desde el día uno, selección de procesos y proveedores, control de calidad, escalado a serie.

6. **Colección / Portfolio — “Objetos con algo distinto”**
   Cada pieza como **ficha técnica**: ilustración lineal SVG + código (EA-001…), material, proceso, variantes personalizables (color · tamaño · nombre · logo). Filtros neumórficos: Hogar · Juego · Eventos · Marcas · Luz. Click → modal liquid glass con la pieza girando (pseudo-3D en SVG/CSS) y vista “explosionada” de sus partes cuando aplique (maceta 2 piezas, colectivo, autito).

7. **Escala — “Objetos → Merch → Industrial”**
   Una línea de producción que crece al scrollear: de una pieza única a una bandeja de 12 iguales a una cinta transportadora con cientos. Contadores animados. Mensaje: «Empezamos por lo chico. Pensamos en serie.»

8. **Materiales y procesos** (la estantería del punto 3.6, interactiva)

9. **Para marcas** — CTA B2B: «¿Tenés una idea para tu negocio?» con mini-caso Aliens para local comercial.

10. **Contacto** — formulario simulado neumórfico (nombre, qué querés hacer, cantidad estimada, fecha) que arma un mensaje y abre WhatsApp (`wa.me`) o Instagram DM. Sin backend.

11. **Footer** — logo animado en miniatura, Marcos Juárez · Córdoba · Argentina, @elaltillo.objetos**

### Elementos transversales “vivos”
- **Cursor-herramienta:** el cursor es una mira de precisión con coordenadas X/Y en mono; sobre máquinas se convierte en lente liquid glass que magnifica.
- **HUD de taller** fijo y discreto (esquina): hora local, “capas impresas hoy”, temperatura de extrusor simulada.
- **Marcas de registro y cotas** que se dibujan al entrar cada sección.
- Navegación flotante liquid glass que se contrae al scrollear.
- Easter egg: tecla o triple clic en el logo → todas las máquinas trabajan a la vez durante 3 s.

---

## 5. Copy (tono y frases semilla)

Español rioplatense, voseo, frases cortas. Ejemplos a usar o mejorar:
- «Objetos que vale la pena encontrar.»
- «Objetos con algo distinto.»
- «Del sueño al objeto.»
- «No hay pasos menores.»
- «Escuchamos. Y al minuto siguiente, hay un plan.»
- «Usamos todo: la herramienta es la que la pieza pide.»
- «Lo diseñamos desde cero. Lo hacemos real.»
- «Hecho en un altillo. Pensado como industria.»
- «Para los que no quieren lo que tiene todo el mundo.»

Evitar: emojis, “calidad garantizada”, “los mejores precios”, lenguaje de marketplace, stock photos.

---

## 6. Requisitos técnicos

- Un solo `.html` con CSS y JS inline. Vanilla JS, sin frameworks ni librerías externas.
- SVG inline para todo (logo, máquinas, piezas, planos). Partículas en `<canvas>`.
- Mobile first, perfecto en 360 px; las máquinas se simplifican en móvil pero siguen vivas.
- Accesible: contraste AA, `alt`/`aria-label`, foco visible, navegación con teclado, `prefers-reduced-motion`.
- SEO básico: `<title>`, meta description, Open Graph (texto), datos estructurados `LocalBusiness` (Marcos Juárez, Córdoba).
- Peso objetivo < 600 KB. Lighthouse > 90 en performance.
- Código ordenado por secciones, con variables CSS de tema (`--grafito`, `--ocre`, `--crema`…) para ajustar paleta fácil.
- Placeholders claramente marcados para: número de WhatsApp, fotos reales futuras, textos legales.

---

## 7. Criterio de éxito

Al abrirla, alguien tiene que pensar en 3 segundos: *“esto lo hizo un estudio de diseño industrial serio, y el taller está funcionando ahora mismo”*. Si parece una plantilla, está mal. Si las animaciones distraen del producto, está mal. Si se siente como entrar a un altillo con la luz entrando por la ventana redonda y las máquinas trabajando, está bien.

---
