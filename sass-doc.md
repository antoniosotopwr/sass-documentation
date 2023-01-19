# Pasos para ejecutar sass en la terminal con nodejs ya instalado

[Documentacion oficial de sass](https://sass-lang.com/guide)

**IMPORTANTE**
Se recomienda hacer un respaldo de su archivo css antes del siguiente paso **4)**, incluso del proyecto

**Pasos:**

1) Ingresar el comando "npm install -g sass" en la terminal de vscode o npm
2) Tener un archivo CSS
3) Crear una carpeta con el nombre "scss" y dentro un archivo .scss
4) Para compilar el codigo, se usa el siguiente comando:"sass --watch ./scss/main scss ./css/style.css" (una vez se ejecute este comando se borrara el contenido de tu archivo css).
5) Para dejar de trabajar con sass introducimos el comando "ctrl + c"
6) Si queremos trabajar con sass de nuevo ingresamos de nuevo el comando del paso 4

> Sobre el paso 4) Basicamente le dices de que archivo sass quieres que se tomen los estilos y a que archivo css los debe mandar.
Sintactimante significa sass --watch ".scss origen" ".css destino"

## Nesting

Lo usamos para saber que los estilos solo corresponden a ese solo bloque.

## Ampersand &

Se usa para volver a llamar al selector padre sin tener que escribirlo manualmente.
Tambien usa nesting.

## Variables

Nos ayuda a facilitar la modificacion en el codigo, solo modificamos el valor de la variable en un solo lugar.

---

**Nota:** Si se llega a tener un problema con sass usando node y npm, se puede instalar la extension de vscode
llamada live sass compiler (ver que sea la nueva version)

Para usarla simplemente se da clic en el boton watch sass y es el equivalente a compilar manualmente con watch sass

No se recomienda su uso ya que puede tener problemas
