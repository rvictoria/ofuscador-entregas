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
3. Se abre el panel del Ofuscador. En **Inicio**, crea tu catálogo con una contraseña de al menos
   12 caracteres. **Apúntala: no se puede recuperar.**
4. Si usas Claude Code o Codex, acepta cuando te pregunte si los conecta.

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
   en tu programa con los datos reales.
4. **El catálogo**: en el panel, añade los nombres de tus clientes que quieras ocultar siempre.

Si algo te molesta, en el icono del reloj puedes **pausar** la protección 15 minutos, 1 hora o
hasta que la reanudes.

## 4. Cuéntanos qué tal

Lo que más nos ayuda:

- Datos que **no** se ocultaron y deberían (di solo el tipo: «un NIF de empresa», «una matrícula»).
- Cosas que se ocultaron sin motivo.
- Momentos en que preferiste enviar sin proteger o dejaste de usarlo, y por qué.
- Si lo echarías de menos si desapareciera, y cuánto pagarías al mes por él.

En el panel, **Actividad** muestra solo recuentos, tipos y decisiones (nunca textos ni datos):
una captura de esa pantalla nos sirve. **No nos envíes textos con datos reales de clientes.**

## Desinstalar

Configuración de Windows → Aplicaciones → Ofuscador, y quita la extensión en
`chrome://extensions`. Tus datos cifrados se quedan en `%APPDATA%\Ofuscador`: bórrala a mano si
quieres eliminarlos también.
