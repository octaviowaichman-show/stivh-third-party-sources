# STIVH — código fuente de terceros

STIVH incluye componentes de código abierto bajo licencias LGPL, GPL y MPL
(Qt / PySide6, FFmpeg, python-zeroconf, python-soxr / libsoxr, certifi, tqdm).
Estas licencias piden ofrecer el código fuente exacto de esos componentes junto
con el programa que los distribuye.

Cada versión de STIVH tiene un release por plataforma (`v<versión>-macos`,
`v<versión>-windows`) con:

- los archivos fuente de cada componente, en la versión que viaja en el instalador;
- la configuración de compilación de cada FFmpeg (`*-configure.txt`);
- `SOURCES.md`: qué componente es cada archivo, su licencia, su uso en STIVH y su SHA-256.

Ver [Releases](https://github.com/octaviowaichman-show/stivh-third-party-sources/releases).

Los textos completos de las licencias viajan con la app
(`THIRD_PARTY_NOTICES.md` y `THIRD_PARTY_LICENSES.txt`).
