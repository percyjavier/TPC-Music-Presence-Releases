# TPC Music Presence

Rich Presence para el reproductor de música de la web de Mundo Conan.

Aplicación de escritorio para Windows que muestra en tu Discord la canción que escuchas en
[Mundo Conan Music](https://music.mundoconan.com): título, artista, portada, barra de progreso y enlace a la canción.

> **Proyecto de fan, no oficial.** No pertenece ni está afiliado a Mundo Conan, a su creador o estudio, ni a Discord.
> Hecho por un fan de Detective Conan, sin ánimo de lucro.

## Descarga

La **única descarga oficial** está en [Releases](https://github.com/percyjavier/TPC-Music-Presence-Releases/releases).
No descargues la aplicación de ningún otro sitio.

Requisitos: Windows 10 u 11 (64 bits) y la aplicación de escritorio de Discord abierta.

## Comprueba que la descarga es genuina

Cada versión incluye un archivo `SHA256SUMS.txt`. Antes de instalar, ejecuta en PowerShell:

```powershell
Get-FileHash "TPC-Music-Presence-Setup-X.Y.Z.exe" -Algorithm SHA256
```

El resultado debe ser igual al del archivo `SHA256SUMS.txt`. Si no coincide, **no instales** el archivo.

## Aviso de Windows al instalar

Si Windows muestra "Windows protegió su PC" o "editor desconocido", es porque el instalador es nuevo y aún
no tiene reputación en SmartScreen. Si has comprobado el SHA-256, puedes continuar con "Más información" y "Ejecutar de todas formas".

## Privacidad

- La aplicación no accede a tus credenciales ni a datos privados de tu sesión en Mundo Conan Music, y no los guarda ni los envía.
- Solo lee el título, el artista, la portada, el enlace y el progreso de la canción para mostrarlos en tu Discord, de forma local.
- No envía datos a ningún servidor propio.

## Soporte

- **Problemas o errores de la aplicación:** contacta con ThePercyCorner (Discord: `thepercycornerofficial`).
- **Problemas de la web o del reproductor:** pruébalo primero en el navegador. Si el error también ocurre allí,
  contacta con el soporte de Mundo Conan.

## Derechos y licencia

- Todos los derechos de la aplicación Rich Presence pertenecen a **ThePercyCorner**.
- Todos los derechos de la web y del reproductor, y de todo lo relacionado con Mundo Conan Music y Mundo Conan,
  incluidos sus nombres, pertenecen a **Mundo Conan** y a su respectivo creador o estudio.
  Su uso está sujeto a sus [términos y reglas](https://mundoconan.com/html/informacion-reglas).
- No se concede ningún derecho a modificar la aplicación ni a distribuirla a terceros sin permiso expreso de ThePercyCorner.

## Respeto a Mundo Conan

La aplicación se limita a mostrar la web de Mundo Conan Music tal cual es y a leer en pantalla los datos de la canción
que suena. **No modifica la web, no descarga ni copia su contenido, no salta cuentas, restricciones ni normas, y no altera
su funcionamiento.**

Si eres el creador, el estudio o un titular de derechos de Mundo Conan y quieres que la aplicación deje de funcionar con
tu web, o que se cambie o retire algo, escribe a ThePercyCorner (Discord: `thepercycornerofficial`). Se atenderá sin
demora y, si hace falta, se actualizará o retirará la aplicación.

Consulta la licencia completa en [LICENSE.txt](LICENSE.txt).

Copyright (c) 2026 ThePercyCorner. Todos los derechos reservados.
