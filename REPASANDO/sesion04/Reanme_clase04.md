#### CSS
- Hojas de estilos en cascada.
- Los estilos de agentes de usuario. (son los estilos que te asignan el navegador por default)

# selector {
# propiedad: valor;
# }
- selector: Define a qué elemento HTML será asignado ciertas caracteristicas.
- propiedad: Define qué característica tomar.
- valor: Define el valor que debe tomar esa característica.

## Fuentes y Textos:
➔ font-family: tipo de letra
➔ font-style: estilo (normal, cursiva, ..)
➔ font-weight: peso (normal, negrita, ..)
## peso (400 regular, 700 bold, 500 medium)
➔ font-size: tamaño de letra
➔ text-align: alineación de texto (izquierda, derecha, ..)
➔ text-transform: mostrar un texto en mayúscula, minúscula o la primera letra
de cada palabra en mayúscula.
➔ letter-spacing: espacio entre letras
➔ word-spacing: espacio entre palabras
➔ line-height: altura de la línea de texto
➔ text-decoration: “Decoraciones” como subrayado, tachado, ..
➔ white-space: Determina cómo se maneja el espacio en blanco dentro de un
elemento. Para hacer que las palabras se dividan en sí mismas.

## Formato de fuentes
En la actualidad, en la web se utilizan los siguientes formatos:
.EOT, .TTF , WOFF, .WOFF2 y SVG
No hay un formato universal que funcione tanto en los navegadores nuevos
como en los más antiguos
➔ .EOT (Solo es compatible con IE)
➔ .TTF (Parcialmente compatible con IE)
➔ .WOFF (Es quien ofrece mayor compatibilidad entre los navegadores)
➔ .WOFF2 (Se encuentra en desarrollo para muchos navegadores.)
➔ .SVG (IE y Firefox nunca lo admitieron, y ahora quedó en desuso en
Chrome. Por este motivo, es de uso limitado)

## font-style
➔ normal (El texto no está inclinado.)
➔ italic (Utiliza la versión en cursiva de la fuente: las letras
están ligeramente inclinadas.)

## font-weight
➔ 100 Thin
➔ 200 Extra Light
➔ 300 Light
➔ 400 Normal o Regular
➔ 500 Medium
➔ 600 Semi Bold
➔ 700 Bold
➔ 800 Extra Bold
➔ 900 Ultra Bold

PREFIJOS
Son palabras reservadas que suelen ir delante de algunas
PROPIEDADES CSS3 y nos permite compatibilidad entre diferentes
navegadores para lograr así que nuestro diseño no sufra ningún cambio.

ctrl + shift + P
autoprefije run
Luego de ello eso sube a produccion para que lo suban
