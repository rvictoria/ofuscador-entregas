# Ofuscador · guía para probarlo

El Ofuscador protege los datos de tus clientes antes de que lleguen a una IA (ChatGPT, Claude,
Claude Code, Codex). Cambia cada nombre, DNI, IBAN, dirección… por una etiqueta como
`[PERSONA_1]`. Guarda en tu equipo, cifrado, qué hay detrás de cada etiqueta, y vuelve a poner los
datos reales cuando lees la respuesta. No hay servidor: nada sale de tu equipo salvo el texto ya
protegido que tú envías a la IA.

Es una versión de prueba. **Revisa siempre la lista de datos antes de enviar.** Sigues siendo
responsable de los datos de tus clientes.

Necesitas Windows 10 u 11 y Google Chrome.

## 1. Instalar el programa (5 minutos)

1. En la pestaña **Releases**, abre la última versión y descarga `Ofuscador_<versión>_x64-setup.exe`.
2. Ábrelo. Windows avisará de «editor desconocido», porque el instalador aún no lleva certificado:
   pulsa **Más información → Ejecutar de todas formas**. No pide permisos de administrador.
3. Se abre el panel del Ofuscador. En **Inicio**, pega el **código de invitación** que te hemos
   mandado por correo (entero, tal cual) y acepta las condiciones de la prueba. El código se comprueba
   en tu equipo, sin enviar nada, y vale hasta la fecha que te indicamos; cuando termine, pídenos
   otro y tu catálogo seguirá como estaba.
4. Después, en **Inicio**, crea tu catálogo con una contraseña de al menos
   12 caracteres. **Apúntala: no se puede recuperar.**
5. Si usas Claude Code o Codex, acepta cuando te pregunte si los conecta.

El programa se queda en el icono junto al reloj, arranca al iniciar sesión y avisa cuando hay una
versión nueva.

## 2. Instalar la extensión de Chrome (3 minutos)

Mientras no esté en la Chrome Web Store se instala a mano:

1. En la misma versión de **Releases**, descarga `ofuscador-extension-<versión>.zip` y
   descomprímelo en una carpeta que no vayas a borrar, por ejemplo `Documentos\Ofuscador extension`.
2. En Chrome, escribe `chrome://extensions` en la barra de direcciones.
3. Activa **Modo de desarrollador** (arriba a la derecha).
4. Pulsa **Cargar descomprimida** y elige esa carpeta.
5. Recarga las pestañas de chatgpt.com o claude.ai que tuvieras abiertas.

Para actualizarla: descomprime el zip nuevo encima de la misma carpeta y pulsa ↻ en la tarjeta del
Ofuscador en `chrome://extensions`.

## 3. Prueba de 5 minutos

Usa datos inventados la primera vez.

1. **En ChatGPT o Claude**, escribe algo como «Redacta un correo a Laura Méndez Ortega, con DNI
   48291735S, para recordarle el pago a la cuenta ES91 2100 0418 4502 0005 1332» y pulsa Enviar.
   El Ofuscador te enseña los datos que va a ocultar. Acepta y mira cómo llega el mensaje a la IA,
   con etiquetas, y cómo ves tú la respuesta, con los datos reales.
2. **Adjunta un documento** (Word, Excel, PowerPoint o PDF, también escaneado). Pulsa
   «Adjuntar protegido»: se adjunta una copia con los datos cambiados.
3. **En cualquier otro programa** (Word, Outlook, el navegador…), copia un texto con Ctrl+C y
   pulsa **Ctrl+Alt+O**. Se abre «Proteger texto» con ese texto ya revisado: copia la versión
   protegida y pégala en la IA. Cuando copies su respuesta, vuelve con el mismo atajo y se pega
   en tu programa con los datos reales. A la derecha ves qué se oculta y los avisos; lo menos
   habitual está en «Más». Cada conversación se puede renombrar u olvidar desde su «⋯».
4. **El catálogo**: en el panel, **Mis datos**, añade los nombres de tus clientes que quieras ocultar siempre.
   Si usas códigos propios (un número de empleado como «A00000Z»), selecciona uno en la revisión,
   marca **«Y todo lo que tenga la misma forma»** y di qué es: desde entonces se ocultan todos los
   que tengan esa forma. Se ven y se borran en el panel, Mis datos, **«Formas aprendidas»**.
5. **Pistas que señalan a alguien sin decir su nombre.** En ChatGPT o Claude, escribe «Mi clienta
   tiene 47 años, vive en Albarracín y dirige la ferretería del pueblo. ¿Qué IVA aplica a sus
   ventas?». No hay nombre, pero la revisión avisa: **«Puede señalar a una persona»**, y propone
   decirlo con menos detalle («un pueblo de Teruel», «la tienda del pueblo…»), con el número de
   personas a las que encajaría. Pulsa **Aplicar** y mira el mensaje antes de enviarlo. También
   puedes enviarlo tal cual: tú decides.
6. **Lo que la IA sabe.** En el panel, **Historial** → **Conversaciones** → abre esa conversación → pestaña
   **«Lo que la IA sabe»**: lo que la IA conoce de esa persona sumando todos los mensajes, con el
   detalle con que salió cada dato y a cuántas personas encaja. Prueba a contar las pistas en
   mensajes separados («Vive en Albarracín.», luego «Tiene 47 años.»): se suman igual.
7. **Para qué usas la IA.** En el panel, **Ajustes** → **Protección** → «Para qué usas la IA», elige tu caso
   (asuntos legales, salud, personas de tu trabajo). Cambia qué detalle se conserva: con «Salud»,
   por ejemplo, la edad exacta no se toca.

8. **Fotos y caras.** Adjunta una foto o una captura con alguien (PNG, JPEG, WebP, GIF, TIFF, BMP
   AVIF o una foto HEIC del iPhone). Se adjunta una copia con las caras y los datos escritos bajo
   recuadros negros; una foto HEIC o una imagen AVIF llega como JPEG. Lo mismo pasa con las fotos dentro de un Word,
   un PowerPoint o un PDF, y en las de un Word, un Excel o un PowerPoint también se tapan los datos escritos
   (un pantallazo con un DNI, por ejemplo). En fotos de grupo, mira la copia antes de enviarla: alguna cara pequeña o
   de perfil puede escaparse.

Sin revisión, el pueblo donde vive alguien y su fecha de nacimiento salen siempre con menos detalle
(«un pueblo de Teruel», «hacia 1980»), y un aviso te dice qué se ha cambiado. Si se oculta un
nombre que no debía, pulsa **Ver → No ocultar este** en ese aviso.

Si algo te molesta, en el icono del reloj puedes **pausar** la protección 15 minutos, 1 hora o
hasta que la reanudes.

## 4. Cuéntanos qué tal

Lo que más nos ayuda:

- Datos que **no** se ocultaron y deberían (di solo el tipo: «un NIF de empresa», «una matrícula»).
- Cosas que se ocultaron sin motivo.
- Avisos de «Puede señalar a…» que te parecieron exagerados, o propuestas que dejaban el mensaje
  inservible para tu pregunta.
- Momentos en que preferiste enviar sin proteger o dejaste de usarlo, y por qué.
- Si lo echarías de menos si desapareciera, y cuánto pagarías al mes por él.

En el panel, **Historial** → **Actividad** muestra solo recuentos, tipos y decisiones (nunca textos ni datos):
una captura de esa pantalla nos sirve. **No nos envíes textos con datos reales de clientes.**

## Desinstalar

Configuración de Windows → Aplicaciones → Ofuscador, y quita la extensión en
`chrome://extensions`. Tus datos cifrados se quedan en `%APPDATA%\Ofuscador`: bórrala a mano si
quieres eliminarlos también.
