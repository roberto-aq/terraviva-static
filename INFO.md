## 1. Iconos utilizados (Font Awesome 6)

Preloader / sello: <i class="fa-solid fa-seedling"></i>

Envío gratis (barra de anuncio): <i class="fa-solid fa-truck-fast"></i>

Logo: <i class="fa-solid fa-leaf"></i>

Búsqueda: <i class="fa-solid fa-magnifying-glass"></i>

Carrito: <i class="fa-solid fa-bag-shopping"></i>

Abrir menú: <i class="fa-solid fa-bars"></i>

Cerrar menú: <i class="fa-solid fa-xmark"></i>

Flecha derecha: <i class="fa-solid fa-arrow-right"></i>

Flecha izquierda: <i class="fa-solid fa-arrow-left"></i>

Garantía 30 días: <i class="fa-solid fa-shield-heart"></i>

Separador del marquee: <i class="fa-solid fa-asterisk"></i>

Check de lista: <i class="fa-solid fa-check"></i>

Proceso · 01: <i class="fa-solid fa-hand-pointer"></i>

Proceso · 02: <i class="fa-solid fa-box-open"></i>

Proceso · 03: <i class="fa-solid fa-spa"></i>

Fecha del artículo: <i class="fa-regular fa-calendar"></i>

Tiempo de lectura / horario: <i class="fa-regular fa-clock"></i>

Suscribirme: <i class="fa-solid fa-paper-plane"></i>

Nota de privacidad: <i class="fa-solid fa-lock"></i>

Dirección: <i class="fa-solid fa-location-dot"></i>

Teléfono: <i class="fa-solid fa-phone"></i>

Redes sociales:
<i class="fa-brands fa-instagram"></i>
<i class="fa-brands fa-tiktok"></i>
<i class="fa-brands fa-pinterest-p"></i>
<i class="fa-brands fa-whatsapp"></i>

Métodos de pago:
<i class="fa-brands fa-cc-visa"></i>
<i class="fa-brands fa-cc-mastercard"></i>
<i class="fa-brands fa-cc-paypal"></i>
<i class="fa-brands fa-cc-amex"></i>

---

## 2. SEO y metadatos

- **lang:** `es`
- **charset:** `UTF-8`
- **viewport:** `width=device-width, initial-scale=1.0`
- **título:** Terra Viva — Estudio Botánico · Plantas de interior en Ecuador
- **meta description:** Plantas de interior curadas a mano, suculentas, colgantes y accesorios. Envíos a todo Ecuador con garantía de 30 días. Vida en cada hoja.
- **favicon:** `img/favicon.svg` (`type="image/svg+xml"`)

---

## 3. Recursos externos (CDN)

- **Google Fonts:** `Fraunces` (display, itálicas + ópticas) + `Outfit` (texto, 300–700), con `preconnect`.
- **Font Awesome:** `6.5.2` (cdnjs).
- **GSAP:** `3.12.5` + `ScrollTrigger` (jsDelivr, `defer`).

---

## 4. Variables CSS

```css
:root {
	/* Color */
	--crema: #f8f5ee;
	--crema-2: #efe9dc;
	--blanco: #fffdf8;
	--tinta: #1c2b22;
	--bosque: #24402f;
	--bosque-profundo: #152119;
	--salvia: #a9bca4;
	--salvia-suave: #dde5d8;
	--terracota: #c2683e;
	--terracota-suave: #e9cdbb;
	--dorado: #d9a441;
	--linea: color-mix(in srgb, var(--tinta) 12%, transparent);
	--sombra: 0 24px 60px -28px
		color-mix(in srgb, var(--tinta) 35%, transparent);
	--sombra-suave: 0 14px 40px -20px
		color-mix(in srgb, var(--tinta) 25%, transparent);

	/* Tipografía */
	--serif: 'Fraunces', 'Georgia', serif;
	--sans: 'Outfit', 'Segoe UI', sans-serif;
	--fs-hero: clamp(2.6rem, 6.5vw, 5.2rem);
	--fs-1: clamp(2.1rem, 4.2vw, 3.4rem);
	--fs-2: clamp(1.6rem, 2.8vw, 2.3rem);
	--fs-3: clamp(1.2rem, 1.8vw, 1.45rem);
	--fs-body: 1.0625rem;
	--fs-s: 0.9375rem;
	--fs-xs: 0.8125rem;

	/* Ritmo */
	--espacio-seccion: clamp(4.5rem, 9vw, 8rem);
	--gutter: clamp(1.25rem, 4vw, 2.5rem);
	--ancho-max: 1280px;

	/* Forma */
	--r-s: 14px;
	--r-m: 22px;
	--r-l: 30px;
	--r-arco: 999px 999px var(--r-m) var(--r-m);
	--r-pildora: 999px;

	/* Movimiento */
	--ease-suave: cubic-bezier(0.22, 1, 0.36, 1);
	--t-rapida: 0.35s var(--ease-suave);
	--t-media: 0.6s var(--ease-suave);

	/* Capas */
	--z-header: 80;
	--z-drawer: 110;
	--z-toast: 130;
	--z-preloader: 150;
}
```

---

## 5. Secciones (en orden de aparición)

1. **Preloader** — velo de carga con el sello de marca.
2. **Barra de anuncio** — franja superior de envío.
3. **Header** — logo, navegación, búsqueda, carrito, menú móvil.
4. **Menú móvil** — navegación a pantalla completa.
5. **Hero** — titular, CTAs, prueba social y tarjetas flotantes.
6. **Marquee** — cinta animada de mensajes clave.
7. **Categorías** — 4 colecciones (interior, suculentas, colgantes, accesorios).
8. **Destacados** — grid de productos generado por JS (`id="grid-destacados"`).
9. **Editorial** — bloque imagen + texto con lista de beneficios.
10. **Cifras** — 4 contadores animados (tema oscuro).
11. **Proceso** — 3 pasos.
12. **Testimonios** — slider de 4 reseñas.
13. **Journal preview** — 3 artículos destacados.
14. **Galería IG** — 6 fotos de comunidad.
15. **Newsletter** — captura de correo.
16. **Footer** — marca, enlaces, contacto y métodos de pago.

---

## 6. Textos por sección

### Barra de anuncio

> Envío gratis desde $40 · Quito y todo Ecuador

### Navegación

Inicio · Tienda · Nosotros · Journal · Contacto

### Hero

- **Eyebrow:** Estudio botánico · Quito
- **H1:** Tu casa quiere ser _un bosque_
- **Lead:** Plantas curadas a mano en nuestro vivero, entregadas en tu puerta con todo lo que necesitan para florecer contigo.
- **CTAs:** Explorar la colección · Nuestra historia
- **Prueba social:** ★★★★★ · 4.9 / 5 · +2.400 plantas felices en su nuevo hogar
- **Tarjetas flotantes:** Monstera Deliciosa — $34.90 · Garantía 30 días (Si no prospera, la reponemos)

### Marquee

> Envíos a todo Ecuador · Garantía de 30 días · Cultivo responsable · Asesoría de por vida · Macetas artesanales

### Categorías

- **Eyebrow:** Colecciones
- **H2:** Encuentra tu _alma gemela_ vegetal
- **Texto:** Cuatro familias, una para cada rincón y para cada tipo de cuidador.
- **Tarjetas:** Interior · Suculentas · Colgantes · Accesorios

### Destacados

- **Eyebrow:** Las favoritas
- **H2:** Curadas por nuestro _equipo botánico_
- **Enlace:** Ver toda la colección

### Editorial

- **Eyebrow:** Más que una tienda
- **H2:** Plantas con historia, _no inventario_
- **Texto:** Cada planta de Terra Viva nace en nuestro vivero de los valles de Quito, crece sin prisa y llega a tu casa con su propia cartilla de cuidados. No vendemos plantas: presentamos compañeras de vida.
- **Lista:** Aclimatadas 6 semanas antes de viajar · Sustrato propio, libre de turba y plástico · Cartilla de cuidados ilustrada en cada envío · Asesoría botánica de por vida vía WhatsApp
- **Sello:** 9 años cultivando
- **CTA:** Conoce el estudio

### Cifras

- 9+ Años cultivando
- 12.400+ Plantas entregadas
- 120+ Especies en catálogo
- 98% Clientes que repiten

### Proceso

- **Eyebrow:** Cómo funciona
- **H2:** Del vivero a tu sala, _sin estrés_
- **Texto:** Tres pasos y un acompañamiento que no termina con la entrega.
- **01 · Elige con calma:** Filtra por luz, nivel de cuidado o convivencia con mascotas. Cada ficha te dice exactamente qué esperar.
- **02 · La preparamos para viajar:** Embalaje biodegradable diseñado por nosotros: tu planta llega hidratada, protegida y sin una hoja fuera de lugar.
- **03 · Florecen juntos:** Recibe recordatorios de riego, acceso al club Terra Viva y asesoría de nuestros botánicos cuando la necesites.

### Testimonios

- **Eyebrow:** Palabra de cuidadores
- **H2:** Historias que _echaron raíces_
- **María José Andrade** (Arquitecta · Quito): "Mi monstera llegó mejor embalada que mi vajilla de bodas. Ocho meses después tiene tres hojas nuevas y yo una obsesión preciosa."
- **Andrés Cevallos** (Diseñador · Guayaquil): "Maté tres cactus antes de Terra Viva. Su asesoría por WhatsApp me convirtió en alguien a quien sus plantas no le temen."
- **Valentina Ríos** (Fotógrafa · Cuenca): "Pedí el trío de suculentas para mi oficina y terminé amueblando la casa entera alrededor de las plantas. Cero arrepentimiento."
- **Sebastián Mora** (Médico · Ambato): "El bonsái que compré para mi padre venía con una carta sobre su historia. Lloramos los dos. Eso no lo hace ninguna otra tienda."

### Journal preview

- **Eyebrow:** El Journal
- **H2:** Saber cuidar también _se cultiva_
- **Enlace:** Todos los artículos
- **Artículos:**
  - Propagación · 12 May 2026 · 6 min — Propagar en agua: la guía que nos hubiera gustado tener
  - Cuidados · 28 Abr 2026 · 8 min — El mapa de luz de tu casa (y dónde vive feliz cada planta)
  - Riego · 15 Abr 2026 · 5 min — Riego consciente: menos calendario, más observación

### Galería IG

- **Eyebrow:** @terraviva.ec
- **H2:** La comunidad _en verde_

### Newsletter

- **Eyebrow:** El club Terra Viva
- **H2:** Consejos que _florecen_ en tu bandeja
- **Texto:** Una carta botánica al mes: cuidados de temporada, lanzamientos y 10% de descuento en tu primera compra.
- **Placeholder:** tu@correo.com · **Botón:** Suscribirme
- **Nota:** Sin spam. Solo verde. Date de baja cuando quieras.

### Footer

- **Marca:** Estudio botánico en Quito. Cultivamos, curamos y acompañamos plantas que convierten casas en hogares.
- **Columnas:** Tienda (Plantas de interior, Suculentas y cactus, Plantas colgantes, Accesorios) · Estudio (Nuestra historia, Journal, Contacto, Preguntas frecuentes)
- **Visítanos:** Av. González Suárez N27-142, Quito, Ecuador · Lun – Sáb · 9:00 a 19:00 · +593 2 245 6789
- **Legal:** © 2026 Terra Viva · Estudio Botánico. Plantilla premium de demostración.

---

## 7. Imágenes usadas

- `img/favicon.svg` — Favicon
- `img/amalia-vergara.jpg` — Avatar prueba social + testimonio (María José)
- `img/bruno-salgado.jpg` — Avatar prueba social + testimonio (Andrés)
- `img/julieta-paez.jpg` — Avatar prueba social + testimonio (Valentina)
- `img/sebastian-mora.jpg` — Testimonio (Sebastián)
- `img/hero-detalle.jpg` — Imagen principal del hero
- `img/monstera-deliciosa.jpg` — Tarjeta flotante del hero
- `img/categoria-interior.jpg` — Categoría · Interior
- `img/trio-suculentas.jpg` — Categoría · Suculentas
- `img/categoria-colgantes.jpg` — Categoría · Colgantes
- `img/trasplante.jpg` — Categoría · Accesorios
- `img/editorial.jpg` — Editorial (imagen principal)
- `img/nuestra-historia.jpg` — Editorial (imagen secundaria)
- `img/propagar-en-agua.jpg` — Journal · artículo 1
- `img/mapa-de-luz.jpg` — Journal · artículo 2
- `img/riego-consciente.jpg` — Journal · artículo 3
- `img/galeria-1.jpg` … `galeria-4.jpg` — Galería IG
- `img/helecho-colgante.jpg` — Galería IG
- `img/decorar-con-plantas.jpg` — Galería IG

Las tarjetas de **Destacados** no tienen imágenes fijas: las inyecta `home.js` leyendo de `data/products.js`.

---

## 8. Datos dinámicos (atributos `data-*` e IDs)

- `id="featured-grid"` — Contenedor donde `home.js` pinta los productos destacados.
- `data-count-cat="..."` — Conteo de productos por categoría (interior, suculentas, colgantes, accesorios).
- `data-counter="N"` — Cifra animada (sección Cifras).
- `data-reveal` / `data-reveal="stagger"` — Animación de entrada (GSAP).
- `data-reveal-img` — Animación de escala de imagen al entrar.
- `data-delay="..."` — Retraso de la animación de entrada.
- `data-open-cart` — Abre el drawer del carrito.
- `data-newsletter` — Formulario de newsletter (envío simulado).
- `data-year` — Año actual del footer (lo rellena el JS).

El carrito (drawer), los toasts y el contador (`.cart-counter`) son globales: los gestiona `main.js`, no son exclusivos del home.
