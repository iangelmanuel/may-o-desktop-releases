# May-O Desktop — descargas

Aquí se publican los instaladores de **May-O Desktop** para Windows, macOS y
Linux. El código es privado; este repositorio solo guarda las descargas y es
desde donde la app se actualiza.

**[Descargar la última versión](https://github.com/iangelmanuel/may-o-desktop-releases/releases/latest)**

| Sistema                      | Archivo                 |
| ---------------------------- | ----------------------- |
| Windows 10/11                | `May-O-Setup-x.y.z.exe` |
| macOS 12+ (Apple Silicon)    | `May-O-x.y.z-arm64.dmg` |
| Linux x64 (cualquier distro) | `May-O-x.y.z.AppImage`  |
| Ubuntu / Debian x64          | `may-o_x.y.z_amd64.deb` |

En Windows y con el AppImage la app se actualiza sola. En macOS, **Buscar
actualizaciones** abre esta página para bajar el `.dmg` nuevo.

## La primera vez

La app todavía no está firmada, así que cada sistema avisa:

- **Windows:** «Editor desconocido». Elige **Más información → Ejecutar de
  todas formas**.
- **macOS:** dice que no puede verificar la app. Ábrela desde **Ajustes del
  Sistema → Privacidad y seguridad → Abrir igualmente**.
- **Linux (AppImage):** dale permiso de ejecución con
  `chmod +x May-O-*.AppImage`. En Ubuntu 22.04+ necesita `libfuse2`
  (`sudo apt install libfuse2`).

En macOS y Linux, las acciones del sistema (volumen, brillo, teclas
multimedia, apagar…) todavía son solo de Windows. El chat, la voz, Work y el
navegador de Mayo funcionan en los tres.

La web: <https://may-o.vercel.app>
