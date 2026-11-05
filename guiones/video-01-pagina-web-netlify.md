# Video 1 — Cómo crear una página web con IA y publicarla en Netlify

Duración editada: **14:40**. Diez bloques, cada uno con una sola idea. Español, de tú, frases cortas.

El plano del celular se graba al final y se coloca también en el segundo 0. El minuto 0 muestra el resultado ya terminado, con la frase cambiada. El paso a paso viene después.

Negocio de ejemplo, inventado: **Rueda Norte**, taller de bicicletas en el Barrio Alameda. El espectador cambia esos textos por los suyos.

---

## 1. Títulos y miniatura

Los tres caben en menos de 70 caracteres.

1. Cómo crear una página web con IA y publicarla en Netlify (56)
2. Crea tu primera web con IA y publícala hoy (42)
3. Tu web en internet, abierta en el celular (41)

Miniatura: un celular en vertical con la página de Rueda Norte abierta y la dirección `netlify.app` legible, y el texto «Tu web, hoy».

---

## 2. Hook (primeros 15 segundos)

El resultado va antes que cualquier explicación. Del segundo 0 al 3, el celular a pantalla completa, sin voz: se lee la dirección y se ve la página. Del 3 al 15, esta frase, mientras el pulgar baja un poco:

> Esta página ya está en internet. La estoy viendo en el celular. Al final, la abres tú.

No se ve el escritorio. No se nombra una herramienta ni un comando. Esta toma es la del cierre, movida aquí en edición.

---

## 3. Capítulos

Cada capítulo es un bloque de edición. Una idea por bloque.

| Tiempo | Capítulo | Idea única |
| --- | --- | --- |
| 0:00 | Así queda en tu celular | El resultado, y el camino en tres pasos |
| 1:10 | Un solo archivo, primero el teléfono | Qué hay en la carpeta |
| 2:30 | El negocio que vas a cambiar | Los textos que se sustituyen |
| 3:50 | Cursor escribe la página | El prompt genera `index.html` |
| 5:40 | La pruebas en ancho de teléfono | Verla estrecha, antes de publicarla |
| 7:05 | La primera versión con git | `git init`, `git add`, `git commit` |
| 8:35 | La subes a GitHub | Repo nuevo y vacío, luego `git push` |
| 10:15 | Netlify la publica | Conectar el repo, raíz, sin build |
| 11:55 | Cambias una frase y se publica sola | Segundo commit, push, republicación |
| 13:25 | La abres en el celular | URL, repo, republicación, y una frase para suscribirse |

---

## 4. Guion por bloques

### Bloque 1 · 0:00–1:10 · Así queda en tu celular

Una idea: el resultado ya existe, y el video solo recorre el camino hasta llegar ahí.

**Se dice**

> Esta página ya está en internet. La estoy viendo en el celular. Al final, la abres tú.
>
> Hoy dejas la tuya igual: un archivo, hecho en Cursor, guardado en GitHub y publicado.
>
> Vamos por partes. Primero la página. Después la guardamos en GitHub. Después Netlify le da una dirección. Si cambias un texto y lo subes, Netlify la publica otra vez, solo.
>
> Hoy no vemos dominio propio, formularios, blog, bases de datos, inicio de sesión, posicionamiento en buscadores ni estadísticas de visitas.

**Se ve**

- 0:00–0:15: celular, navegador, dirección `*.netlify.app` legible, página de Rueda Norte con la frase ya cambiada («Tu bici lista hoy, en Alameda.»). El pulgar recorre el inicio y los tres servicios.
- Corte al escritorio. Tarjeta con tres líneas: Página. GitHub. Netlify.
- Tarjeta corta con lo que queda fuera: dominio, formularios, blog, base de datos, inicio de sesión, posicionamiento, estadísticas. No se abre ninguno.

**Corte**

Timelapse de nada. Este bloque sale de la toma final. Quita el desenfoque del celular y cualquier aviso. No insertes aquí la espera de Netlify.

---

### Bloque 2 · 1:10–2:30 · Un solo archivo, primero el teléfono

Una idea: el proyecto es un archivo, pensado para el ancho del teléfono.

**Se dice**

> Esta es la carpeta. Se llama rueda-norte. Dentro hay una foto, y en un momento habrá un solo archivo de página: index.html.
>
> La pensamos para el teléfono. En el escritorio es el mismo contenido, con más aire.
>
> No se instala nada. Yo escribo en Cursor. VS Code es el mismo tipo de programa. Hoy no lo abrimos.

**Se ve**

- Finder o el explorador de archivos: carpeta `rueda-norte`. Dentro, solo `foto.webp`.
- Cursor ya abierto en esa carpeta. Barra lateral con la foto. Terminal visible, en silencio.
- Un segundo de VS Code en un recuadro, o solo nombrado. No se crea ahí un proyecto.
- Dibujo simple, o el celular apagado al lado del monitor: primero estrecho, luego ancho. Mismo contenido.

**Corte**

Corta la búsqueda de la carpeta y el arranque de Cursor. Empieza con la carpeta ya abierta. Si Cursor pide login, fuera. Eso se resolvió antes de grabar.

---

### Bloque 3 · 2:30–3:50 · El negocio que vas a cambiar

Una idea: estos textos son de ejemplo, y se cambian por los del espectador.

**Se dice**

> El ejemplo es un taller inventado. Se llama Rueda Norte. Está en el Barrio Alameda.
>
> La oferta dice: tu bici lista hoy. La recogemos en el barrio.
>
> Hay tres servicios. Revisión general. Frenos y cambios. Pinchazo del día.
>
> Hay una frase de una clienta. Un botón de WhatsApp. Y un pie con el horario.
>
> El número es falso. Tú cambias el nombre, los textos y el enlace. La estructura se queda: inicio, para quién es, tres servicios, una prueba, el botón final y el pie.

**Se ve**

Tarjeta fija, texto grande, este orden:

- Rueda Norte · Barrio Alameda
- Tu bici lista hoy. La recogemos en el barrio.
- Revisión general / Frenos y cambios / Pinchazo del día
- «Salí pedaleando el mismo día.» — Lucía, Alameda
- Botón: Escribir por WhatsApp
- Pie: Martes a sábado

No se abre otra web de referencia. No se ve una plantilla.

**Corte**

Si dudaste el nombre, fuera. La tarjeta entra ya escrita. Este bloque es la tarjeta y la voz, nada de teclear.

---

### Bloque 4 · 3:50–5:40 · Cursor escribe la página

Una idea: el prompt le pide a Cursor el archivo, y el archivo aparece.

**Se dice**

> Abro el chat de Cursor y pego el prompt, el texto de la petición. Está en la descripción del video.
>
> Le pide un solo archivo, con las secciones de antes, pensado primero para el teléfono.
>
> Envío. La espera se acelera. Al volver, el archivo de la página, index.html, está en la carpeta.
>
> Si Cursor creó otro archivo, lo borro. Se quedan la página y la foto.

**Se ve**

- Chat de Cursor, modo agente o el chat que escriba archivos en la carpeta. Pegar el prompt de la sección 5, completo, de un solo golpe.
- El scroll se detiene un momento en cada condición, en este orden: primero el teléfono, secciones, Tailwind por un enlace, ancho y alto de la foto, carga diferida fuera del inicio, contraste, botones grandes, un solo archivo.
- Clic en enviar.
- El archivo `index.html` aparece en la barra lateral. Se abre. Se ven, sin leerlos todos: la etiqueta de Tailwind, la de la fuente Outfit, y la imagen `foto.webp` con `width` y `height`.
- Si hay archivos de más, se borran en un corte seco. Quedan `index.html` y `foto.webp`.

**Corte**

Timelapse de toda la generación: el texto que va saliendo y la espera de la IA. Deja el antes (la petición enviada) y el después (archivo abierto). Corta también cualquier explicación larga del chat. El entregable es el archivo, no la respuesta.

---

### Bloque 5 · 5:40–7:05 · La pruebas en ancho de teléfono

Una idea: mirar la página estrecha, en el navegador, antes de publicarla.

**Se dice**

> Abro el archivo en el navegador. Todavía no es internet. Es la página en tu computador.
>
> Achico la ventana hasta el ancho de un teléfono.
>
> Recorro. La frase. El botón. La foto. Para quién es. Los tres servicios, uno debajo del otro. La frase de Lucía. El botón final. El pie.
>
> El botón cabe en el pulgar. El texto se lee. La foto cabe en el ancho.

**Se ve**

- Doble clic en `index.html`, o arrastrarlo al navegador. Se ve `file://`, todavía no es internet.
- El borde de la ventana se arrastra hasta quedar estrecha. Referencia: cabe un celular al lado, con la pantalla apagada.
- Recorrido de arriba abajo, despacio, una sección por corte. La foto se ve entera, sin scroll horizontal.

**Corte**

Corta el intento de encontrar el archivo y el arrastre indeciso de la ventana. Entra con la ventana ya estrecha si el arrastre se alarga. No enseñes el modo dispositivo del navegador: es otro tema. Tailwind y la fuente salen de internet: si el archivo se abre sin estilos, recarga. Si el navegador los bloquea por ser un archivo local, haz este mismo control de ancho en la dirección de Netlify, dentro del bloque 8. No montes un servidor.

---

### Bloque 6 · 7:05–8:35 · La primera versión con git

Una idea: guardar la primera versión. En git, ese guardado se llama commit.

**Se dice**

> Ahora guardamos la primera versión. En git, ese guardado se llama commit.
>
> Mira la terminal. Tiene que decir rueda-norte. Si no, escribe:
>
> cd rueda-norte
>
> Escribe: git init
>
> Con esto, git empieza a vigilar la carpeta.
>
> Escribe: git add .
>
> El punto significa todo lo que hay aquí. Lo deja listo.
>
> Escribe: git commit -m "Primera versión de la página"
>
> Listo. El mensaje es el nombre de esta versión. La página ya quedó guardada.

**Se ve**

La terminal, grande, cursor dentro de `rueda-norte`. Cada comando se teclea, se dice y se ejecuta. Se lee la respuesta de cada uno:

```bash
git init
git add .
git commit -m "Primera versión de la página"
```

Tras el commit, se ve el resumen: un commit, `index.html` y `foto.webp`. No hace falta otro comando.

**Corte**

No timelapsees los comandos: son el bloque. Corta errores de dedo y vuelve a teclear limpio. Si `git init` dice que ya estaba iniciado, no lo expliques: es que la carpeta no estaba virgen. En grabación buena, la carpeta es nueva y el comando responde “Initialized”.

---

### Bloque 7 · 8:35–10:15 · La subes a GitHub

Una idea: el proyecto llega a un repositorio nuevo y vacío.

**Se dice**

> En GitHub creo un repositorio. Repositorio es la carpeta del proyecto, ya en internet.
>
> Se llama rueda-norte. Público. No marco ninguna casilla. Si añades un README, un texto de presentación, el repositorio deja de estar vacío y después no se puede subir.
>
> Pulso Create repository. Crear repositorio.
>
> Vuelvo a la terminal. Copio la dirección que GitHub muestra y escribo:
>
> git remote add origin
>
> y pego la dirección. Remote es esa dirección.
>
> Escribe: git branch -M main
>
> Así la línea principal se llama main. No creamos otra.
>
> Escribe: git push -u origin main
>
> Push es subir la versión. La primera vez puede abrirse el navegador para entrar. Aceptas y vuelves.
>
> En el repositorio ya se ve index.html. Y la foto.

**Se ve**

- GitHub → New repository. Nombre `rueda-norte`. Public. Las casillas de README, .gitignore y license se ven desmarcadas. Clic en Create repository.
- La caja “quick setup” con la dirección HTTPS. Clic en copiar.
- Terminal, tres comandos, cada uno dicho en voz alta:

```bash
git remote add origin https://github.com/TU_USUARIO/rueda-norte.git
git branch -M main
git push -u origin main
```

- La respuesta del push: `main -> main`.
- El repo en el navegador, recargado: `index.html` y `foto.webp`. Se abre `index.html` y se ve el código, un segundo.

**Corte**

Timelapse del formulario si tardas en buscar el botón. Congela, legibles, las casillas vacías y el push correcto. Si sale la ventana de permiso de GitHub, timelapse: es una espera de cuenta, no una lección. El checklist pide tener ese permiso resuelto antes; si aun así sale, no lo conviertas en tutorial.

---

### Bloque 8 · 10:15–11:55 · Netlify la publica

Una idea: Netlify publica la raíz del repo, sin comando de build.

**Se dice**

> En Netlify, con el plan gratis, la página recibe una dirección.
>
> Add new project, añadir un proyecto. Import an existing project, importar uno que ya existe.
>
> Elige GitHub y el repositorio rueda-norte.
>
> Build command, el comando para compilar. Lo dejas vacío. Aquí no se compila nada.
>
> Publish directory es la carpeta que se publica. Escribe un punto. El punto es la raíz, donde está index.html.
>
> Deploy site. Publicar.
>
> La espera se acelera. Cuando dice Published, o sea publicada, abro la dirección. Eso ya es internet. Recargo y se ve Rueda Norte.

**Se ve**

Ruta actual de Netlify, en este orden:

1. Projects → Add new project → Import an existing project.
2. GitHub. El repo `rueda-norte`.
3. Branch: `main`.
4. Build command: vacío. Si hay un texto sugerido, se borra.
5. Publish directory: `.`
6. Deploy site.

Luego la fila del deploy pasa a Published. Clic en la URL `*.netlify.app`. La página carga. Se ve el candado y la dirección. Recorrido rápido, ventana ancha: es el mismo contenido, con más aire.

**Corte**

Timelapse desde el clic en Deploy hasta Published. Suele tardar. Deja el antes (los dos campos, build vacío y punto) y el después (Published y la URL abierta). Si Netlify pide autorizar GitHub, timelapse: va en el checklist como hecho previo. No enseñes dominio propio ni los ajustes de DNS. Ni un vistazo.

---

### Bloque 9 · 11:55–13:25 · Cambias una frase y se publica sola

Una idea: un cambio, un push, y Netlify publica otra vez sin que pulses nada.

**Se dice**

> Cambio una frase que se vea. El título pasa de “Tu bici lista hoy” a “Tu bici lista hoy, en Alameda”.
>
> Guardo el archivo.
>
> Escribe: git add .
>
> Escribe: git commit -m "Cambio la frase de la oferta"
>
> Escribe: git push
>
> Esta vez no hace falta la dirección. Ya quedó guardada.
>
> No toco el botón de publicar. Netlify ve esa subida y publica solo.
>
> Cuando termina, recargo la dirección. La frase nueva ya está.

**Se ve**

- `index.html` en Cursor. El título, grande en pantalla. Se edita una sola frase. Guardar (se ve el punto de “sin guardar” desaparecer).
- Terminal:

```bash
git add .
git commit -m "Cambio la frase de la oferta"
git push
```

- Netlify, pestaña Deploys, sin clics de “Trigger deploy”. Entra sola una fila nueva: Building, luego Published.
- El navegador recarga la misma URL. El título nuevo se lee entero.

**Corte**

Timelapse de la espera entre el push y Published. No cortes el momento en que la fila aparece sola: es la prueba. Corta el resto del registro de build.

---

### Bloque 10 · 13:25–14:40 · La abres en el celular

Una idea: cerrar con la misma dirección en la mano, el repositorio detrás, y la republicación que salió sola.

**Se dice**

> La misma dirección, en el celular.
>
> Cargo. Bajo con el dedo. El inicio. Los servicios. El botón.
>
> Detrás están el repositorio, con dos versiones, y Netlify, con dos publicaciones. La segunda salió sola, al subir.
>
> Si te sirvió, suscríbete.

**Se ve**

- Celular en la mano. Pegas la URL en el navegador (de una nota, no tecleada letra a letra). La página carga con la frase “en Alameda”. Scroll real, con el pulgar, hasta el botón de WhatsApp. No hace falta enviarlo.
- Inserto de dos segundos: GitHub, dos commits, “Primera versión de la página” y “Cambio la frase de la oferta”.
- Inserto de dos segundos: Netlify, dos deploys Published. El segundo, atado al push.
- Vuelta al celular. La última frase es la de suscribirse. Nada más después. No hay una segunda llamada, ni un “en el próximo video” hablado.

**Corte**

El scroll del celular va a tiempo real, corto. Timelapse solo si la red tarda en abrir la URL. Esa misma toma, sin la frase de suscribirse, es el hook del segundo 0.

---

## 5. Prompt para pegar en Cursor

Un solo pegado. Si la foto no mide 1200 por 800, cambia esos dos números antes de grabar. El resto se deja igual.

```text
Crea un solo archivo, index.html, en la raíz de este proyecto. No crees ningún otro archivo. No crees package.json ni netlify.toml, que son archivos de configuración, ni carpetas. No uses Node, ni npm (el instalador de paquetes), ni un framework (un esqueleto de aplicación). No escribas una explicación larga en el chat: el entregable es el archivo.

Es la página de presentación de un taller de bicicletas inventado. Una sola pantalla larga. Nombre: Rueda Norte. Lugar: Barrio Alameda. Textos, colores y estructura originales. No copies marcas, textos ni fotos de una plantilla. No uses bancos de imágenes ni URLs externas. La única imagen es el archivo local ./foto.webp, ya comprimida. No inventes fotos de personas.

Idioma de la página: español, de tú. Frases cortas.

Primero el teléfono (mobile first). Los estilos de partida son para un teléfono de 320 a 420 píxeles. En el teléfono, todo va en una columna. El escritorio es el mismo contenido, con más aire, centrado, ancho máximo 640 píxeles. Nada de menú escondido, carrusel ni animaciones.

Orden de las secciones:
1. Encabezado: el nombre Rueda Norte. Sin menú.
2. Hero, la primera pantalla. Orden en el teléfono: frase, botón, foto. La frase y el botón se ven sin bajar. Frase principal: "Tu bici lista hoy." Frase de apoyo: "La recogemos en el barrio." Botón: "Escribir por WhatsApp".
3. Para quién es: una sola frase. Gente del Barrio Alameda que usa la bici a diario y no quiere dejarla una semana en un taller.
4. Tres servicios, uno debajo del otro en el teléfono y en tres columnas solo si hay sitio. Cada uno con título y una frase: "Revisión general", "Frenos y cambios", "Pinchazo del día".
5. Prueba social, una sola cita, sin foto de la persona: "Salí pedaleando el mismo día." — Lucía, Alameda.
6. Cierre: repite la oferta en una frase y un botón grande de WhatsApp.
7. Pie: "Rueda Norte · Barrio Alameda · Martes a sábado".

Enlace de los botones, número de ejemplo: https://wa.me/573000000000?text=Hola%2C%20quiero%20un%20turno%20para%20mi%20bici

Estilos solo con Tailwind por CDN, un enlace que trae los estilos y no se instala, con este script: https://cdn.tailwindcss.com
Una sola familia tipográfica, Outfit, con font-display: swap (el texto se muestra enseguida con una letra de reserva mientras llega la fuente), en este enlace: https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700&display=swap
No añadas otra familia, ni iconos, ni librerías. Si Outfit no carga, la reserva es sans-serif del sistema.

Imágenes. La del hero, la primera pantalla, usa ./foto.webp, width="1200" height="800", alt="Bicicleta apoyada en el taller de Rueda Norte". No le pongas loading="lazy": es lo primero que se ve. Que cubra el hueco sin deformarse (object-fit: cover), al ancho del teléfono, y reserva la proporción 1200/800 (aspect-ratio) para que la página no salte. Cualquier otra imagen que no sea el hero lleva width, height y loading="lazy" (carga diferida: se descarga después). En este archivo no añadas otras imágenes.

Contraste legible. Texto #1c2b24 sobre fondo #f4f0e6. Botón con texto blanco sobre #9a3412. El pie usa el mismo texto oscuro, nunca gris claro. Texto del cuerpo de al menos 18 px en el teléfono.

Botones grandes. Alto mínimo 48 px, texto de 18 px, ancho completo en el teléfono. En escritorio pueden encogerse al contenido, con el mismo alto.

Título de la pestaña: "Rueda Norte · Taller de bicicletas en Alameda".
```

---

## 6. Checklist de grabación

Como máximo, esto. Si algo de aquí no está, no empieces.

1. Cuenta de GitHub creada, sesión abierta en el navegador, y el computador ya puede subir desde la terminal. Así la primera subida no se convierte en un tutorial de claves.
2. Cuenta de Netlify en plan gratis, sesión abierta, y GitHub ya autorizado dentro de Netlify.
3. Cursor instalado, con sesión iniciada, abierto en una carpeta nueva llamada `rueda-norte`. VS Code cerrado.
4. Dentro de esa carpeta, solo `foto.webp`. Sin git iniciado. Lo compruebas porque `git status` todavía diría que no es un repositorio. No dejes esa prueba en el video.
5. `foto.webp` es tuya, en WebP, comprimida. Anotas ancho y alto. Si no son 1200 y 800, los cambias en el prompt antes de pegarlo.
6. El repositorio de GitHub todavía no existe. Lo creas en cámara, público y sin ninguna casilla marcada. Comprueba antes que el nombre `rueda-norte` está libre en tu cuenta. Si no lo está, elige otro y úsalo igual en todo el video.
7. Celular cargado, desbloqueado, en la misma red, para abrir la URL al final. Esa toma también abre el video.
8. En la terminal, `git --version` responde. La terminal se abre ya dentro de `rueda-norte`.
9. El prompt de este guion, con los números reales de la foto, está en una nota listo para pegar.
10. Decidido el enlace del botón. El del prompt es un número falso. Si la dirección va a quedar pública, ten el número real a mano para cambiarlo antes de guardar la primera versión, o acepta que el de ejemplo se verá.

---

## 7. Descripción de YouTube

Texto para pegar debajo del video:

```text
En este video dejas una página de presentación en internet, de una sola pantalla.
La haces en Cursor, la guardas en GitHub, la publicas en Netlify y la abres en tu celular.

0:00 Así queda en tu celular
1:10 Un solo archivo, primero el teléfono
2:30 El negocio que vas a cambiar
3:50 Cursor escribe la página
5:40 La pruebas en ancho de teléfono
7:05 La primera versión con git
8:35 La subes a GitHub
10:15 Netlify la publica
11:55 Cambias una frase y se publica sola
13:25 La abres en el celular

Herramientas: Cursor, Git, GitHub, Netlify y Tailwind. Tailwind entra por un enlace. No se instala nada.

En el siguiente video le ponemos un dominio propio a esta misma página.
```

El prompt de la sección 5 va en un comentario fijado. En el bloque 4 se ve al pegarlo. No lo leas entero en voz alta.

---

## 8. Tres errores reales, resueltos en cámara

Son inserts de rescate. Sustituyen el momento en que falló. No suman capítulo y no alargan el video por encima de los 16 minutos. En cada uno se dice la frase mientras se hace el arreglo.

No improvises `git pull` (bajar lo que haya en GitHub) ni un push forzado, que pisa lo ya subido. En el primer video, el arreglo es dejar el repositorio vacío.

### Push rechazado

Cuándo: bloque 7, justo después de `git push -u origin main`.

Qué pasó de verdad: el repo de GitHub no nació vacío. Casi siempre porque se marcó “Add a README”. GitHub tiene un commit que tu carpeta no tiene, y rechaza el push. En la terminal se lee algo así:

```text
! [rejected]        main -> main (fetch first)
error: failed to push some refs
hint: Updates were rejected because the remote contains work that you do not have locally.
```

**Se ve:** esa respuesta, un segundo. Luego Settings del repo, al fondo, Delete this repository. New repository, el mismo nombre, casillas sin marcar. Vuelta a la terminal. La dirección es la misma, no hace falta volver a añadirla.

**Frase:**

> El push fue rechazado porque GitHub no estaba vacío. Creo el repositorio otra vez, sin el archivo de presentación, y repito el push.

Se repite, en voz alta y escrito:

```bash
git push -u origin main
```

Se ve `main -> main`. Se sigue el bloque 7 como si este insert no existiera.

### Netlify publicó una carpeta vacía

Cuándo: bloque 8, al abrir la URL.

Qué pasó de verdad: Publish directory no es la raíz. A menudo queda `dist` o `public`. Este proyecto no tiene esa carpeta, o llega vacía, sin `index.html`. La URL dice Page not found, y en Deploys el explorador de archivos no muestra `index.html`. A veces el deploy ni siquiera termina y el registro dice que esa carpeta no existe. El arreglo es el mismo.

**Se ve:** la URL rota, un segundo. Luego Project configuration → Build settings → Configure. Build command vacío. Publish directory: `.` Guardar. Una publicación nueva. En el explorador del deploy aparece `index.html`. La URL, recargada, muestra Rueda Norte.

**Frase:**

> Netlify publicó una carpeta vacía. La carpeta es la raíz, un punto, y el comando de build, lo de compilar, se queda vacío. Corrijo eso y publico otra vez.

### Se ve bien en el escritorio y se rompe en el teléfono

Cuándo: bloque 5, al achicar la ventana. Si solo se nota después de publicar, el arreglo es el mismo y se hace antes del segundo push, para que el celular del cierre ya salga bien.

Qué pasó de verdad: hay un ancho fijo más grande que el teléfono, o una fila que no se apila. La ventana ancha lo esconde. La ventana estrecha enseña un scroll de lado a lado.

**Se ve:** ventana ancha, la página bien. Ventana estrecha, la página se sale por la derecha. En `index.html`, buscas un ancho en píxeles de un contenedor, o un mínimo de ancho grande. Lo cambias para que use el ancho de la pantalla y, si es una fila, para que en el teléfono vaya una debajo de otra. Guardas. Recargas. El scroll de lado desaparece. Un cambio, una recarga. La frase se dice mientras lo haces. No nombres clases de CSS.

**Frase:**

> Se ve bien en el escritorio y se rompe en el teléfono. Quito el ancho fijo, dejo que use el ancho de la pantalla, y recargo.
