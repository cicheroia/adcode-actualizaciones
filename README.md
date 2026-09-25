# Versiones del Sistema AdCode

De acá cada Sistema AdCode instalado baja sus versiones nuevas y las instala solo. `version.json` dice cuál es la última
y dónde está; el instalador va como archivo de cada release.

El instalador va cifrado y `version.json` va firmado. Cada sistema comprueba la firma y la huella del archivo antes de
instalar nada, y descarta lo que no esté firmado con la llave de quien publica.
