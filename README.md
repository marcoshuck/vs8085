# Intel 8085 - Visual Studio Code Extension

## Características
- Resaltado de sintaxis (Language highlighting)
  - Instrucciones (todas en mayúsculas).
  - Directivas.
  - Etiquetas (Solo palabras).
  - Registros y palabras reservadas.
  - Números en hexadecimal, binario y decimal.
  - Caracteres entre comillas simples.
  - Línea de comentarios.

## Instalación
### Con el instalador de extension de Visual Studio Code
Aún no implementado.

### Con el paquete VSIX
- Descargar el paquete .vsix publicado en este repositorio. **Link de descarga:** https://github.com/marcoshuck/vs8085/releases
- Abrir Visual Studio Code
- Apretar F1, se desplegará la paleta de comandos.
- Escribir VSIX y se mostrará la opción "Install from VSIX".
- Clickear la opción, buscar el archivo descargado e instalar.

Visual Studio Code lo guiará en el resto del procedimiento.


### De modo manual
 - Descargar el código fuente del repositorio
 - Dirigirse a la dirección *C:/Users/NombreDeUsuario/.vscode/extensions*
 - Crear la carpeta vs8085
 - Pegar dentro de la carpeta el contenido del repositorio

Al terminar el procedimiento descripto anteriormente, la extensión ya se encontrará instalada en Visual Studio Code.

## Modo de uso
Una vez instalada la extensión, se debe crear un nuevo archivo nombrado de la siguiente manera: ***ejemplo.8085asm***.

Es decir, la extensión de los archivos DEBE ser "**.8085asm**".

## Colaboración
Todas las pull requests son bienvenidas, pero serán analizadas en base a la necesidad y la buena implementación de las mismas.

## Pendiente
- IntelliSense
- Tooltips