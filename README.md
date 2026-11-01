# Descargas de gdgdev.com

Aquí publico los instaladores de mis aplicaciones. Cada app tiene su ficha en **[gdgdev.com](https://gdgdev.com)** con capturas, qué hace y cómo empezar: lo más cómodo es descargar desde allí. Este repo solo guarda los archivos.

## Aplicaciones

| App | Qué es | Descarga | Ficha |
|---|---|---|---|
| **Toggly** 0.1.0 | Cambia la resolución de tus monitores y el audio con un clic, con perfiles y reglas. Windows 10 y 11. | [Instalador](https://github.com/Guillermo-David/descargas/releases/download/toggly/Toggly-setup.exe) · [Portable](https://github.com/Guillermo-David/descargas/releases/download/toggly/Toggly-portable.exe) · [SHA256SUMS](https://github.com/Guillermo-David/descargas/releases/download/toggly/SHA256SUMS.txt) | [Ver ficha](https://gdgdev.com/apps/toggly/) |
| **PartScreen** 0.1.0 | Ve YouTube, Netflix o cualquier web con vídeo a pantalla completa, pero solo en la parte del monitor que tú elijas. Windows 10 y 11. | [Instalador](https://github.com/Guillermo-David/descargas/releases/download/partscreen/Partscreen-win-x64-setup.exe) · [Portable](https://github.com/Guillermo-David/descargas/releases/download/partscreen/Partscreen-win-x64-portable.exe) · [SHA256SUMS](https://github.com/Guillermo-David/descargas/releases/download/partscreen/SHA256SUMS.txt) | [Ver ficha](https://gdgdev.com/apps/partscreen/) |
| **Mathemagic** 1.0.0 | Calculadora científica que recuerda tus fórmulas, con conversores, gráficas, ecuaciones y más. Windows. | [Instalador](https://github.com/Guillermo-David/descargas/releases/download/mathemagic/Mathemagic_x64-setup.exe) | [Ver ficha](https://gdgdev.com/apps/mathemagic/) |
| **Pildoras** 3.1.0 | Un cuaderno para tus pequeñas ideas: apuntes cortos en Markdown, con fórmulas, etiquetas y enlaces. Windows. | [Instalador (.msi)](https://github.com/Guillermo-David/descargas/releases/download/pildoras/Pildoras.msi) | [Ver ficha](https://gdgdev.com/apps/pildoras/) |
| **Almorzeitor** 1.0.0 | App web para coordinar los almuerzos del grupo; el pedido sale al bar por WhatsApp. Se despliega gratis en Render + Upstash. | [Código (.zip)](https://github.com/Guillermo-David/descargas/releases/download/almorzeitor/almorzeitor.zip) | [Ver ficha](https://gdgdev.com/apps/almorzeitor/) |

Las apps web no necesitan descarga: **[PDFácil](https://pdfacil.gdgdev.com)** ([ficha](https://gdgdev.com/apps/pdfacil/)) y **[Sopa de letras](https://sopa.gdgdev.com)** ([ficha](https://gdgdev.com/apps/sopa-de-letras/)) se usan directamente en el navegador.

Todas las versiones: [Releases](https://github.com/Guillermo-David/descargas/releases).

## Aviso de Windows (SmartScreen)

Los instaladores no llevan firma digital (cuesta un dinero que prefiero ahorrarme), así que al abrirlos Windows puede mostrar «Windows protegió su PC». Para continuar, pulsa **Más información** y luego **Ejecutar de todas formas**. Si quieres asegurarte de que el archivo es el que yo subí, comprueba su huella (abajo).

## Comprobar que la descarga está intacta

Cada archivo tiene una huella SHA-256. Si la de tu descarga coincide con la publicada, el archivo es exactamente el que subí, sin cortes ni cambios por el camino.

1. Busca la huella publicada:
   - En las apps con **SHA256SUMS.txt** (Toggly, PartScreen), ábrelo: hay una línea por archivo. El nombre de la línea lleva la versión (p. ej. `Toggly-0.1.0-setup.exe`), así que fíjate en la de `setup` o la de `portable` según lo que bajaste.
   - En el resto, la huella aparece junto a cada archivo en la página de la release (`sha256:…`).
2. Calcula la huella de tu archivo. En PowerShell, desde la carpeta de descargas:
   ```powershell
   Get-FileHash .\Toggly-setup.exe -Algorithm SHA256
   ```
   O en el Símbolo del sistema (cmd):
   ```cmd
   certutil -hashfile Toggly-setup.exe SHA256
   ```
   Cambia el nombre por el del archivo que hayas descargado.
3. Compara las dos huellas (da igual mayúsculas o minúsculas). Si son iguales, todo en orden. Si no, no lo abras: bórralo, vuelve a descargarlo y, si sigue sin coincidir, [avísame](https://gdgdev.com/#contacto).

## ¿Te han servido?

Todas las apps son gratis. Si alguna te ahorra tiempo, puedes [invitarme a un café en Ko-fi](https://ko-fi.com/guillermo_david) ☕

Más apps, novedades y contacto en **[gdgdev.com](https://gdgdev.com)**.
