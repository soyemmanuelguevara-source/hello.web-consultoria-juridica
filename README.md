# Landing Page — Consultoría Jurídica

Informe de proyecto para el desarrollador. Aquí está toda la información del negocio, los recursos disponibles y las instrucciones para construir la landing page usando la plantilla HTML + Claude.

---

## 1. Sobre el negocio

**Nombre del despacho:** Consultoría Jurídica
**Logo:** búho (owl) sobre columna clásica, estilo heráldico/sello, en dorado y azul marino (navy + gold).

El despacho está integrado por dos abogados que atienden distintas áreas del derecho:

### Mtro. Mario Eduardo Estrada Aguilar — Abogado Penalista
- **Especialidad:** Derecho Penal y Juicios Orales (defensa en procedimientos penales, audiencias orales, medidas cautelares, amparo penal y recursos).
- **Experiencia:** Más de 15 años.
- **Slogan:** "La Mejor Defensa Penal" / "Tu defensa, mi compromiso" / "Tu libertad es nuestra prioridad".
- **WhatsApp:** 229 522 7860
- **Correo:** lic.mario.eduardo@gmail.com
- **Dirección:** Calle Vasco Núñez de Balboa entre George Washington y José Martí #238, Fracc. Reforma, Veracruz.
- **Diferenciadores:** Atención 24/7, consulta confidencial, agenda por QR/WhatsApp.
- **Contenido educativo para la landing** (viene en los banners, se puede usar como sección de "consejos" o "qué hacer si..."):
  - *¿Qué hacer cuando te detienen?* → 1) Mantén la calma 2) No declares nada 3) Pide hablar con tu abogado 4) No firmes nada sin leer 5) Informa a un familiar.
  - *¿Detuvieron a un familiar?* → Mantén la calma, pregunta en qué Ministerio Público está, no permitas que declare sin abogado, no firmes documentos sin leerlos. Mensaje clave: "Cada minuto puede cambiar completamente el caso."

### Lic. Dulce Olivia Acevedo Ramírez — Abogada
- **Cédula profesional:** 15603925
- **Especialidades:** Derecho Civil, Derecho Familiar (divorcios, pensión alimenticia, custodia, régimen de visitas, patria potestad), Derecho Laboral (despidos injustificados, prestaciones, negociación), Derecho Mercantil (constitución de empresas, contratos mercantiles, cobranza, litigios comerciales), Amparos y Juicios.
- **Slogan:** "Tu tranquilidad, mi compromiso. Justicia, ética y vocación."
- **Funciones que ofrece (para sección "servicios" o "cómo te ayudamos"):** Asesorar, Analizar y evaluar, Representar, Negociar y mediar, Litigar, Prevenir conflictos.
- **Teléfono:** 229 338 3693
- **Correo:** oli58895@gmail.com
- **Dirección:** Calle Balboa #238 entre George Washington y José Martí, Col. Reforma, Veracruz, Ver.

> Ambos abogados comparten prácticamente la misma dirección/colonia (Reforma, Veracruz), por lo que la landing puede presentarse como **un despacho conjunto** con dos perfiles/especialistas, o dar más peso a un socio si el cliente así lo indica. Confirmar con el cliente cuál enfoque prefiere antes de maquetar el "Sobre nosotros".

### Servicios consolidados (para menú / sección de servicios)
1. Derecho Penal y Juicios Orales
2. Derecho Civil
3. Derecho Familiar
4. Derecho Laboral
5. Derecho Mercantil
6. Amparos y Juicios

### Redes sociales
Facebook, WhatsApp, Instagram, TikTok (iconos disponibles en los banners; agregar como enlaces/botones flotantes de contacto).

---

## 2. Recursos en la carpeta `imagenes/`

| Archivo | Contenido | Uso sugerido |
|---|---|---|
| `WhatsApp Image ...12.50.56 PM.jpeg` | Banner "¿Te detuviste? Conoce y ejerce tus derechos" — Mario Eduardo, con los 5 pasos, datos de contacto y QR | Sección hero o "conoce tus derechos" del área penal |
| `WhatsApp Image ...12.50.56 PM (1).jpeg` | Banner "Abogada" — Dulce Olivia, con las 6 funciones de un abogado y foto profesional | Sección "Sobre la abogada" / servicios civil-familiar |
| `WhatsApp Image ...12.50.56 PM (2).jpeg` | Banner "¿Detuvieron a un familiar?" — Mario Eduardo, con QR de contacto | Sección secundaria / bloque de urgencia área penal |
| `WhatsApp Image ...12.50.56 PM (3).jpeg` | Banner con logo, redes sociales y lista de servicios (versión Dulce Olivia) | Referencia de servicios y redes |
| `WhatsApp Image ...12.50.57 PM.jpeg` | **Logo del despacho** (búho, fondo blanco) | **Logo oficial** — ver nota abajo |
| `ejemplo pagina web (me paso este diseño el cliente).pdf` | Diseño de referencia que el cliente compartió (versión Mario Eduardo, incluye "Derecho Penal y Juicios Orales" en la lista de servicios) | **Guía de estilo visual**: usar como inspiración de jerarquía, colores (azul marino + dorado), tipografía serif para títulos, e íconos circulares para servicios |

### ⚠️ Nota importante sobre el logo
El archivo del logo (`WhatsApp Image ...12.50.57 PM.jpeg`) tiene **fondo blanco**. Antes de usarlo en la web, **hay que quitarle el fondo** (por ejemplo con [remove.bg](https://remove.bg)) para poder colocarlo sobre fondos oscuros/de color en el header, footer y loading screen sin que se vea el recuadro blanco.

---

## 3. Instrucciones de trabajo (plantilla + Claude)

El desarrollo parte de una **plantilla HTML existente**. El flujo de trabajo es:

1. Quitar el fondo al logo (remove.bg) antes de integrarlo.
2. Abrir el proyecto con Claude y usar el prompt inicial de la sección 4 para adaptar la plantilla al negocio.
3. **Iterar**: el resultado del primer prompt casi nunca es el final. Después de la primera pasada, seguir dando instrucciones puntuales a Claude (ajustar espaciados, contrastes, animaciones, jerarquía de textos, responsive, etc.) hasta lograr un acabado realmente premium. No conformarse con la primera respuesta.

### Estilo obligatorio
- **Premium / enterprise / corporativo / elegante** — nada de plantillas genéricas o de aspecto "template gratis".
- Paleta principal: **azul marino (navy) + dorado**, tal como el logo y los banners.
- Tipografía: combinar una serif elegante para títulos (tipo la del logo/banners) con una sans-serif limpia para texto.
- **Pantalla de carga (loading screen)** al inicio de la página, antes de mostrar el contenido (ej. logo animado o spinner elegante con la marca).
- Micro-animaciones/transiciones sutiles al hacer scroll (fade-in, reveal), sin exagerar.
- Diseño 100% responsive (mobile-first, ya que gran parte del tráfico llega por WhatsApp/redes).
- Botón flotante de WhatsApp siempre visible.

---

## 4. Prompt inicial sugerido para Claude

```
Voy a convertir esta plantilla HTML en la landing page de un despacho de abogados llamado
"Consultoría Jurídica", integrado por dos abogados:

1. Mtro. Mario Eduardo Estrada Aguilar — Abogado Penalista, más de 15 años de experiencia.
   Especialidad: Derecho Penal y Juicios Orales.
   WhatsApp: 229 522 7860 | Correo: lic.mario.eduardo@gmail.com
   Dirección: Calle Vasco Núñez de Balboa entre George Washington y José Martí #238,
   Fracc. Reforma, Veracruz.

2. Lic. Dulce Olivia Acevedo Ramírez — Abogada, cédula profesional 15603925.
   Especialidades: Derecho Civil, Derecho Familiar, Derecho Laboral, Derecho Mercantil,
   Amparos y Juicios.
   Teléfono: 229 338 3693 | Correo: oli58895@gmail.com
   Dirección: Calle Balboa #238 entre George Washington y José Martí, Col. Reforma, Veracruz.

Servicios a destacar: Derecho Penal y Juicios Orales, Derecho Civil, Derecho Familiar,
Derecho Laboral, Derecho Mercantil, Amparos y Juicios.

Requisitos de diseño (muy importantes):
- Estilo PREMIUM, ENTERPRISE, elegante y de alta confianza — como un despacho corporativo
  de alto nivel, no una plantilla genérica.
- Paleta de color: azul marino (navy) y dorado, igual que el logo adjunto.
- Tipografía serif elegante para títulos, sans-serif limpia para texto de cuerpo.
- Agregar una PANTALLA DE CARGA (loading screen) animada al inicio de la página, antes de
  mostrar el contenido principal.
- Botón flotante de WhatsApp.
- Diseño responsive, mobile-first.
- Secciones: Hero, Sobre el despacho / los abogados, Servicios, ¿Por qué elegirnos?
  (confidencialidad, atención 24/7, experiencia), Testimonios (placeholder), Contacto
  (teléfonos, correos, dirección, mapa) y Footer con redes sociales
  (Facebook, WhatsApp, Instagram, TikTok).

Usa como referencia visual el PDF de diseño que te paso (estructura tipo "sello" con logo,
íconos circulares de servicios y franja dorada). No lo copies literal, es solo referencia de
tono y jerarquía visual.

Empieza por adaptar el header, el hero y la sección de servicios. Iremos ajustando el resto
sección por sección.
```

**Después de este prompt inicial, seguir iterando con Claude** sección por sección (hero, servicios, contacto, footer, loading screen, animaciones) hasta que el resultado se vea realmente premium y corporativo, y no como un primer borrador.
