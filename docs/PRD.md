# 🌷 PRD — Ramo Digital de Amor y Amistad

## Información del proyecto

| Campo | Información |
|---|---|
| Versión | 1.0 |
| Estado | Planificación |
| Tipo | Experiencia web interactiva |
| Tecnologías | HTML, CSS, JavaScript, p5.js |
| Usuarios | 10 personas |
| Plataforma | Navegador web |
| Responsive | Sí |
| Base de datos | No |
| Backend | No |

---

# 1. Descripción del proyecto

Crear una experiencia web interactiva como regalo para el **Día del Amor y la Amistad**, destinada a 10 personas diferentes.

La experiencia debe sentirse como un pequeño regalo digital preparado específicamente para cada persona.

Cada persona tendrá una **contraseña única**. Al introducir correctamente su contraseña, se desbloqueará una experiencia personalizada.

La experiencia comenzará con una animación en la que se construirá progresivamente un **ramo de flores generado mediante p5.js**.

El ramo no debe aparecer de golpe.

Debe construirse progresivamente:

**Tallos → hojas → flores → pétalos → apertura → composición final del ramo**

Una vez terminado el ramo, aparecerá el nombre o apodo de la persona y posteriormente un **mensaje personalizado escrito por el creador del regalo**.

La idea es que cada persona sienta:

> "Este ramo fue hecho especialmente para mí."

---

# 2. Objetivo

Crear un regalo digital que combine:

- Personalización.
- Animación.
- Ilustración generativa.
- Flores.
- Mensajes personales.
- Interactividad.
- Una pequeña experiencia de descubrimiento.

El objetivo no es crear simplemente una página con un mensaje, sino una experiencia donde la persona **descubra progresivamente su regalo**.

---

# 3. Público objetivo

El proyecto está diseñado para 10 personas seleccionadas por el creador.

Cada persona tendrá:

- Una contraseña única.
- Un ramo personalizado.
- Una composición floral diferente.
- Un mensaje personal.
- Una experiencia visual propia.

No será necesario crear cuentas de usuario.

---

# 4. Tecnologías

## Tecnologías principales

- HTML5
- CSS3
- JavaScript
- p5.js

## p5.js

p5.js será la biblioteca principal utilizada para crear las flores y sus animaciones.

Se utilizarán herramientas matemáticas y gráficas como:

- `sin()`
- `cos()`
- `tan()`
- `radians()`
- `map()`
- `lerp()`
- `dist()`
- `noise()`
- `rotate()`
- `translate()`
- `scale()`
- `push()`
- `pop()`

También se utilizarán coordenadas polares para crear formas florales.

---

# 5. Concepto visual

## "Un ramo hecho para ti"

La página debe transmitir la sensación de que el usuario está recibiendo un ramo que se está creando especialmente para él.

No debe parecer una página genérica.

No debe parecer una plantilla.

La experiencia debe sentirse:

- Personal.
- Elegante.
- Delicada.
- Cálida.
- Emotiva.
- Moderna.
- Artesanal.

---

# 6. Flujo general

**INICIO**

↓

**Pantalla de bienvenida**

↓

**Introducir contraseña**

↓

**¿Contraseña correcta?**

### Si es incorrecta

Mostrar mensaje de error y permitir otro intento.

### Si es correcta

Mostrar:

> **Acceso concedido.**

↓

**Animación del ramo**

↓

**Ramo completamente formado**

↓

Mostrar:

> **Este ramo es para ti.**

↓

Mostrar:

> **Para: [APODO]**

↓

**CONTINUAR**

↓

**Mensaje personalizado**

↓

**Pantalla final**

↓

**VOLVER AL INICIO**

---

# 7. Pantalla de inicio

La pantalla inicial debe ser sencilla y misteriosa.

## Título

**AMOR & AMISTAD**

## Texto

> Hay algo preparado especialmente para ti.

## Campo

**Ingresa tu contraseña**

## Botón

**ENTRAR**

## Pista

> Tal vez sea algo que solo tú recuerdas.

---

# 8. Fondo de la pantalla inicial

El fondo puede tener elementos animados muy sutiles:

- Pequeñas partículas.
- Estrellas.
- Pétalos flotando.
- Pequeños puntos de luz.
- Formas abstractas.

La animación debe ser lenta y discreta.

No debe distraer del campo de contraseña.

---

# 9. Sistema de contraseñas

Cada una de las 10 personas tendrá una contraseña diferente.

La estructura de datos debe permitir configurar fácilmente:

- Nombre.
- Apodo.
- Contraseña.
- Ramo.
- Mensaje.

La lógica debe identificar automáticamente a qué persona pertenece la contraseña introducida.

## Contraseña incorrecta

Mostrar:

> Creo que esa no era... intenta nuevamente.

El mensaje debe aparecer con una pequeña animación.

El campo debe permanecer disponible para volver a intentar.

## Contraseña correcta

Mostrar brevemente:

> **Acceso concedido.**

Después realizar una transición hacia la experiencia del ramo.

---

# 10. Seguridad

No se necesita un sistema de autenticación real.

El proyecto funcionará completamente en el navegador.

No utilizar:

- Base de datos.
- Backend.
- Servidores externos.
- Registro de usuarios.
- APIs de autenticación.

Las contraseñas estarán almacenadas dentro del JavaScript.

Esto es suficiente porque el objetivo es crear una experiencia de regalo, no un sistema de seguridad real.

---

# 11. El ramo

El ramo es el elemento principal de toda la experiencia.

No utilizar imágenes estáticas de ramos.

El ramo debe ser **generado mediante código utilizando p5.js**.

El ramo estará compuesto por:

- Tallos.
- Hojas.
- Flores.
- Pétalos.
- Centros florales.
- Estambres.
- Ramas.
- Elementos decorativos.

Cada ramo debe poder personalizarse.

---

# 12. Concepto de animación

El ramo debe parecer que está **creciendo y siendo construido frente al usuario**.

No debe aparecer completamente formado desde el principio.

La animación debe tener varias etapas.

---

# 13. Etapa 1 — Semilla

La pantalla comienza casi vacía.

Aparece una pequeña semilla o punto en la parte inferior.

La semilla puede tener una pequeña animación de movimiento o brillo.

---

# 14. Etapa 2 — Crecimiento de los tallos

Desde la semilla comienza a crecer el primer tallo.

El tallo debe:

- Crecer progresivamente.
- Tener una ligera curvatura.
- Tener un movimiento natural.
- No ser completamente recto.

Después aparecerán otros tallos.

Los tallos pueden crecer con diferentes inclinaciones.

El objetivo es que al final formen la estructura de un ramo.

---

# 15. Etapa 3 — Aparición de hojas

Las hojas deben aparecer progresivamente.

Cada hoja debe:

1. Comenzar pequeña.
2. Crecer.
3. Girar ligeramente.
4. Alcanzar su tamaño final.

Agregar detalles internos como nervaduras.

Las hojas no deben ser simples óvalos.

---

# 16. Etapa 4 — Aparición de las flores

Después de que los tallos hayan crecido, comenzarán a aparecer las flores.

Las flores deben aparecer **una por una**.

Ejemplo:

**Flor 1 → pausa → Flor 2 → pausa → Flor 3 → pausa → Flor 4**

Esto debe generar una sensación de crecimiento natural.

---

# 17. Etapa 5 — Formación de los pétalos

Los pétalos deben aparecer progresivamente.

No mostrar todos los pétalos simultáneamente.

Cada pétalo puede:

- Crecer desde el centro.
- Rotar.
- Aumentar su tamaño.
- Cambiar ligeramente su posición.
- Aparecer con un pequeño retraso.

Las pequeñas variaciones harán que las flores se vean menos artificiales.

---

# 18. Etapa 6 — Apertura de las flores

Una vez formados los pétalos, cada flor debe abrirse.

Los pétalos interiores deben comenzar más cerrados.

Después se expanden hacia afuera.

El resultado final debe parecer una flor que acaba de abrirse.

---

# 19. Etapa 7 — Formación final del ramo

Cuando todas las flores estén abiertas:

- Los tallos terminan de acomodarse.
- Las hojas quedan en su posición.
- Las flores quedan agrupadas.
- El ramo adquiere una composición equilibrada.

El resultado debe parecer un **ramo completo**, no simplemente varias flores separadas.

---

# 20. Etapa 8 — Detalles finales

Agregar detalles muy sutiles:

- Pétalos cayendo.
- Pequeñas partículas.
- Brillos.
- Movimiento ligero de las hojas.
- Pequeños destellos.

Estos elementos no deben sobrecargar la pantalla.

---

# 21. Duración de la animación

La animación completa del ramo debería durar aproximadamente:

**6–12 segundos.**

Debe ser suficientemente lenta para que el usuario pueda apreciar cómo se construye.

No utilizar animaciones demasiado rápidas.

---

# 22. Generación matemática de las flores

Las flores deben generarse mediante matemáticas.

Utilizar coordenadas polares.

Como referencia:

**r = A × sin(k × θ)**

Después convertir a coordenadas cartesianas:

**x = r × cos(θ)**

**y = r × sin(θ)**

Estas técnicas pueden utilizarse para crear:

- Pétalos.
- Centros.
- Patrones.
- Capas.
- Formas radiales.

---

# 23. Rosas matemáticas

Utilizar como referencia el concepto de **rosas matemáticas**.

La ecuación:

**r = A × sin(k × θ)**

puede utilizarse para crear patrones florales.

Sin embargo, no limitar todas las flores a esta fórmula.

Combinar diferentes técnicas matemáticas para conseguir especies diferentes.

---

# 24. Detalle de las flores

Las flores deben verse como **ilustraciones botánicas digitales generadas mediante código**.

No deben parecer emojis.

No deben parecer iconos.

No deben ser únicamente círculos y pétalos básicos.

Cada flor debe incluir detalles como:

- Pétalos superpuestos.
- Curvas.
- Texturas.
- Nervaduras.
- Estambres.
- Centro detallado.
- Variaciones de tamaño.
- Variaciones de rotación.
- Capas.
- Pequeñas imperfecciones naturales.

---

# 25. Diferentes especies

El proyecto debe soportar diferentes especies.

Como mínimo:

1. Rosa.
2. Tulipán.
3. Girasol.
4. Margarita.
5. Flor de cerezo.
6. Loto.
7. Lavanda.
8. Hibisco.
9. Dalia.
10. Flor personalizada.

Cada especie debe tener una estructura visual diferente.

---

# 26. Rosa

La rosa debe utilizar varias capas de pétalos.

Características:

- Centro cerrado.
- Pétalos internos pequeños.
- Pétalos exteriores grandes.
- Pétalos curvados.
- Varias capas.
- Tallo ligeramente curvado.
- Hojas con detalles.

---

# 27. Tulipán

Características:

- Forma de copa.
- Pétalos grandes.
- Pétalos ligeramente superpuestos.
- Tallo largo.
- Hojas alargadas.

---

# 28. Girasol

Características:

- Muchos pétalos.
- Centro grande.
- Centro con patrón de semillas.
- Hojas grandes.
- Tallo grueso.

Utilizar patrones matemáticos inspirados en la distribución natural de las semillas.

Se puede utilizar el ángulo áureo para distribuirlas.

---

# 29. Margarita

Características:

- Muchos pétalos finos.
- Centro circular detallado.
- Hojas pequeñas.
- Forma ligera.

---

# 30. Flor de cerezo

En lugar de una única flor, crear una pequeña rama con varias flores.

Características:

- Varias flores pequeñas.
- Pétalos suaves.
- Ramas.
- Hojas pequeñas.
- Pétalos cayendo lentamente.

---

# 31. Loto

Características:

- Varias capas.
- Pétalos grandes.
- Centro visible.
- Forma simétrica.
- Pequeñas variaciones para evitar una simetría demasiado artificial.

---

# 32. Lavanda

En lugar de una sola flor, crear varios tallos de lavanda.

Cada tallo debe contener pequeñas flores agrupadas.

El conjunto debe formar parte del ramo.

---

# 33. Hibisco

Características:

- Pétalos grandes.
- Forma abierta.
- Centro largo.
- Estambres visibles.
- Hojas grandes.

---

# 34. Dalia

Características:

- Muchas capas.
- Gran cantidad de pétalos.
- Pétalos interiores pequeños.
- Pétalos exteriores más grandes.
- Centro complejo.

---

# 35. Flor personalizada

Crear una flor especial mediante una combinación de diferentes patrones matemáticos.

Esta flor puede utilizar:

- Simetría radial.
- Coordenadas polares.
- Variaciones de `sin()`.
- Variaciones de `cos()`.
- Diferentes capas.

Debe sentirse diferente a las demás.

---

# 36. Composición de los ramos

Los 10 ramos no deben ser iguales.

Cada persona debe tener una combinación diferente.

Ejemplo conceptual:

**Ramo 1**

- 2 rosas.
- 2 margaritas.
- 1 lavanda.

**Ramo 2**

- 3 tulipanes.
- 2 flores de cerezo.

**Ramo 3**

- 2 girasoles.
- 2 margaritas.
- 1 flor pequeña.

Las combinaciones deben poder modificarse fácilmente.

---

# 37. Personalización del ramo

Cada ramo debe permitir configurar:

- Flores.
- Cantidad.
- Tamaño.
- Inclinación.
- Colores.
- Posiciones.
- Altura de los tallos.
- Distribución.

Los parámetros pueden modificarse según la arquitectura final.

---

# 38. Configuración de las 10 personas

Debe existir una sección claramente identificada dentro de `script.js` para configurar las 10 personas.

La estructura debe permitir modificar fácilmente:

- Nombre.
- Apodo.
- Contraseña.
- Flores del ramo.
- Cantidad.
- Colores.
- Mensaje.

La lógica de las flores y las animaciones no debería necesitar modificarse.

---

# 39. Ejemplo de configuración

La estructura conceptual puede ser:

**Persona 1**

- Nombre: Nombre 1
- Apodo: Apodo 1
- Contraseña: clave1
- Ramo: rosas + margaritas + lavanda
- Mensaje: mensaje personalizado

**Persona 2**

- Nombre: Nombre 2
- Apodo: Apodo 2
- Contraseña: clave2
- Ramo: tulipanes + flores de cerezo
- Mensaje: mensaje personalizado

Continuar hasta la Persona 10.

---

# 40. Mensajes personalizados

Cada persona debe tener un mensaje completamente independiente.

El mensaje será escrito manualmente por el creador.

Debe soportar:

- Varias líneas.
- Párrafos.
- Saltos de línea.
- Texto largo.

El mensaje no debe ser generado automáticamente.

El creador debe poder escribir exactamente lo que quiera decirle a cada persona.

---

# 41. Apartado de mensajes

Crear dentro del proyecto una sección claramente marcada como:

**CONFIGURACIÓN DE MENSAJES**

Esta sección debe permitir al creador escribir los 10 mensajes sin tener que modificar ninguna función de animación.

La estructura debe ser sencilla de identificar.

Por ejemplo:

**PERSONA 1 — MENSAJE**

Aquí se escribe el mensaje.

**PERSONA 2 — MENSAJE**

Aquí se escribe el mensaje.

Y así hasta la Persona 10.

---

# 42. Presentación del mensaje

Cuando termine el ramo:

Mostrar:

> **Este ramo es para ti.**

Después:

> **Para: [APODO]**

Después mostrar:

**CONTINUAR**

Al presionar el botón:

- El ramo permanece visible.
- Aparece el mensaje.
- El texto entra mediante una animación suave.

Se puede utilizar:

- Fade in.
- Máquina de escribir.
- Revelado progresivo.

---

# 43. Pantalla del mensaje

La pantalla debe mantener el ramo como elemento visual principal.

### En computador

El ramo puede aparecer a la izquierda y el mensaje a la derecha.

### En móvil

El ramo puede aparecer arriba y el mensaje debajo.

Debe existir suficiente espacio para leer cómodamente.

---

# 44. Pantalla final

Después del mensaje mostrar:

> **Gracias por formar parte de mi historia.**

Después:

> Este pequeño ramo fue hecho especialmente para ti.

Botón:

**VOLVER AL INICIO**

---

# 45. Diseño visual

## Estilo

- Elegante.
- Delicado.
- Moderno.
- Minimalista.
- Emotivo.
- Natural.
- Personal.

## Evitar

- Exceso de emojis.
- Diseños infantiles.
- Colores demasiado saturados.
- Interfaz sobrecargada.
- Flores genéricas.
- Flores tipo emoji.
- Imágenes estáticas.
- Animaciones rápidas.

El ramo debe ser siempre el protagonista.

---

# 46. Colores

Utilizar una paleta suave y armoniosa.

Los colores de las flores pueden variar según la persona.

No utilizar demasiados colores simultáneamente.

La interfaz debe permitir que el ramo sea el protagonista.

---

# 47. Responsive

La experiencia debe funcionar correctamente en:

- Teléfonos.
- Tablets.
- Computadores.

El canvas de p5.js debe adaptarse automáticamente al tamaño disponible.

Utilizar `windowResized()` para ajustar el canvas cuando cambie el tamaño de la pantalla.

---

# 48. Arquitectura del proyecto

La estructura esperada es:

**proyecto/**

- `index.html`
- `style.css`
- `script.js`
- `README.md`

No utilizar frameworks adicionales.

p5.js será la biblioteca principal.

---

# 49. Organización del código

El código debe estar dividido en funciones independientes.

Funciones esperadas:

- `setup()`
- `draw()`
- `drawStem()`
- `drawLeaf()`
- `drawPetal()`
- `drawRose()`
- `drawTulip()`
- `drawSunflower()`
- `drawDaisy()`
- `drawCherryBlossom()`
- `drawLotus()`
- `drawLavender()`
- `drawHibiscus()`
- `drawDahlia()`
- `drawCustomFlower()`
- `drawFlowerCenter()`
- `drawStamen()`
- `drawBouquet()`
- `animateBouquet()`
- `checkPassword()`
- `showAccessGranted()`
- `showBouquet()`
- `showMessage()`
- `resetExperience()`

La arquitectura puede modificarse si existe una solución mejor, pero debe mantenerse modular y fácil de editar.

---

# 50. Estados de la experiencia

Utilizar estados para controlar la navegación.

Estados principales:

- `inicio`
- `acceso`
- `ramo`
- `mensaje`
- `final`

Esto permitirá controlar fácilmente qué debe aparecer en cada momento.

---

# 51. Rendimiento

Debido a que el proyecto utilizará flores generativas complejas:

- Evitar cálculos innecesarios en cada frame.
- Reutilizar geometrías cuando sea posible.
- Controlar la cantidad de partículas.
- Evitar crear demasiados objetos constantemente.
- Utilizar variables de progreso para las animaciones.
- Mantener una tasa de frames estable.

El objetivo es conseguir flores detalladas sin sacrificar demasiado rendimiento.

---

# 52. Requisitos funcionales

## RF-01

El usuario debe poder introducir una contraseña.

## RF-02

El sistema debe comprobar la contraseña.

## RF-03

Cada contraseña debe identificar a una persona.

## RF-04

Una contraseña incorrecta debe mostrar un mensaje de error.

## RF-05

Una contraseña correcta debe desbloquear el contenido correspondiente.

## RF-06

Debe aparecer una animación de acceso.

## RF-07

Debe generarse un ramo mediante p5.js.

## RF-08

El ramo debe construirse progresivamente.

## RF-09

Los tallos deben aparecer mediante animación.

## RF-10

Las hojas deben aparecer mediante animación.

## RF-11

Las flores deben aparecer una por una.

## RF-12

Los pétalos deben formarse progresivamente.

## RF-13

Las flores deben abrirse.

## RF-14

El ramo debe terminar completamente formado.

## RF-15

Deben existir diferentes especies de flores.

## RF-16

Los 10 ramos deben poder ser diferentes.

## RF-17

Debe mostrarse el nombre o apodo correspondiente.

## RF-18

Debe mostrarse un mensaje personalizado.

## RF-19

Debe existir un botón para continuar.

## RF-20

Debe existir un botón para volver al inicio.

---

# 53. Requisitos no funcionales

## Rendimiento

Las animaciones deben funcionar de manera fluida en dispositivos móviles de gama media.

## Usabilidad

El usuario debe entender rápidamente:

1. Dónde colocar la contraseña.
2. Cómo entrar.
3. Cómo continuar.
4. Cómo leer su mensaje.
5. Cómo volver al inicio.

## Mantenibilidad

La información de las 10 personas debe poder modificarse fácilmente.

## Compatibilidad

Debe funcionar en navegadores modernos.

## Privacidad

No enviar mensajes ni contraseñas a servicios externos.

---

# 54. Criterios de aceptación

- [ ] Existe una pantalla inicial.
- [ ] Existe un campo de contraseña.
- [ ] Existen 10 contraseñas.
- [ ] Cada contraseña corresponde a una persona.
- [ ] Las contraseñas incorrectas muestran un error.
- [ ] Las contraseñas correctas desbloquean el contenido.
- [ ] Existe una animación de acceso.
- [ ] Se genera un ramo mediante p5.js.
- [ ] El ramo se construye progresivamente.
- [ ] Los tallos aparecen progresivamente.
- [ ] Las hojas aparecen progresivamente.
- [ ] Las flores aparecen una por una.
- [ ] Los pétalos se forman mediante animación.
- [ ] Las flores se abren.
- [ ] El ramo termina completamente formado.
- [ ] Existen diferentes especies.
- [ ] Las flores tienen suficiente detalle.
- [ ] Las flores no parecen emojis.
- [ ] Los 10 ramos pueden ser diferentes.
- [ ] Cada persona tiene un mensaje diferente.
- [ ] Los mensajes son fáciles de editar.
- [ ] El nombre/apodo aparece correctamente.
- [ ] Existe una pantalla final.
- [ ] Se puede volver al inicio.
- [ ] Funciona en móvil.
- [ ] Funciona en computador.
- [ ] No utiliza base de datos.
- [ ] No requiere backend.

---

# 55. Experiencia emocional deseada

La experiencia debe provocar una sensación similar a:

> "Me dieron una contraseña y descubrí un pequeño espacio que alguien creó exclusivamente para mí."

La contraseña representa el acceso personal.

La animación representa el descubrimiento.

El ramo representa el regalo.

El mensaje representa el vínculo con esa persona.

La combinación de los cuatro elementos debe crear una experiencia íntima, especial y memorable.

---

# 56. Resultado esperado

La experiencia completa debe sentirse así:

1. La persona recibe una contraseña.
2. Entra a la página.
3. Introduce su contraseña.
4. La página reconoce su acceso.
5. Aparece una pequeña animación de transición.
6. Comienza a crecer un tallo.
7. Aparecen otros tallos.
8. Crecen las hojas.
9. Aparecen las primeras flores.
10. Las flores se forman una por una.
11. Los pétalos comienzan a abrirse.
12. Se completa el ramo.
13. Aparecen pequeños detalles y partículas.
14. El ramo queda completamente formado.
15. Aparece:

> **Este ramo es para ti.**

16. Aparece el nombre o apodo.
17. La persona pulsa **CONTINUAR**.
18. Aparece el mensaje personalizado.
19. La persona termina en la pantalla final.

La sensación final debe ser:

> **"Este no es un regalo genérico. Este fue hecho para mí."**