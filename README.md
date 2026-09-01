# ITVControl-cliente-offline

<img src="https://github.com/X43K/ITVControl/blob/c343d1baa2b6a1ef822edc28d58ec07b376d64ba/images/logo.webp">

Cliente offline para Windows

Descargue todos los archivos en una carpeta del sistema, por ejemplo: `C:/ClienteITVControl`. Podrá crear un acceso directo a `C:/ClienteITVControl/ITVOffline.hta` para ejecutar el cliente más cómodamente.

Al ejecutar `ITVOffline.hta` por primera vez, aparecerá una pantalla mostrando en rojo **OFFLINE** y, debajo, el botón **"Cambiar clave Sync"**. Pulse dicho botón e introduzca la web y la clave proporcionada por el superadministrador.

A partir de aquí, la aplicación se sincronizará con los datos de su servidor, mostrando las citas asignadas a la(s) flota(s) a la(s) que esta clave esté asignada.

En caso de caída del servidor o pérdida de conexión a la red, el cliente mostrará el mensaje **"OFFLINE mostrando datos de caché"** junto con la fecha y hora de la última sincronización.

Cuando exista una actualización de esta aplicación, simplemente aparecerá un aviso, al aceptarlo se auto-actualizará y reiniciará la aplicacion sin que tenga que hacer nada más.
