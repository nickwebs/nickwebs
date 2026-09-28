# Mantenimiento

Este perfil contiene una cabecera, una presentación breve, cinco tecnologías y un enlace a la web. No necesita un build, servicios externos de imágenes o automatizaciones.

## Texto y tecnologías

Edita README.md. Conserva el nombre de pila o alias, una frase sobre el enfoque de desarrollo y una selección breve del stack. Los nombres son texto nativo; los iconos tienen alt vacío porque solo acompañan a esos nombres. Mantén cada icono dentro de picture para evitar que GitHub lo convierta en un enlace sin nombre accesible.

Hay cinco iconos originales de función o abreviatura: HTML, CSS, JavaScript, PHP y Symfony. Todos utilizan el mismo tamaño óptico y la misma paleta. No pretenden ser logotipos oficiales.

Mantén un único enlace profesional en el README. Antes de guardar, comprueba el destino, las rutas de las imágenes y el uso exacto de mayúsculas y extensiones.

## Cabecera

| Variante | SVG principal | PNG alternativo | Dimensiones |
| --- | --- | --- | --- |
| Claro, escritorio | hero-light.svg | hero-light.png | 1200 × 250 px |
| Oscuro, escritorio | hero-dark.svg | hero-dark.png | 1200 × 250 px |
| Móvil, ambos temas | hero-mobile.svg | hero-mobile.png | 640 × 270 px |

Las seis piezas están en assets/hero/. Las cabeceras son composiciones originales: tipografía en trazados, un motivo geométrico basado en la inicial del alias y una retícula sutil. No dependen de fuentes, scripts o recursos remotos y no contienen información de otros trabajos. La versión móvil mantiene el fondo azul tinta en ambos temas.

La paleta conserva azul tinta #18333F y marfil #F5F1E8, con dorado #82632F en claro y #DDC398 en oscuro. Los SVG son arte final; para cambiar la firma, edita o sustituye la pieza en un editor vectorial y exporta de nuevo el PNG correspondiente. No se distribuyen archivos de fuentes.

El picture prioriza móvil, escritorio oscuro y escritorio claro. El umbral móvil es 600 px de viewport. Conserva la consulta de ancho en el primer source, separada de las consultas de tema: GitHub modifica estas últimas cuando se elige un tema manualmente. No combines ancho y tema en una misma consulta. El img ofrece un PNG claro como respaldo. Si GitHub no renderiza un SVG, sustituye sus srcset por los PNG equivalentes.

## Revisión

Después de un cambio, revisa ambos temas a 320, 375, 768 y 1440 px dentro de un ancho de contenido similar al del perfil de GitHub. Comprueba contraste, proporciones, saltos de línea, iconos y ausencia de desplazamiento horizontal.

Revisa también los archivos no utilizados, textos alternativos y metadatos de imágenes. El contenido versionado debe coincidir con lo que se quiere mostrar públicamente. Prepara el commit con rutas explícitas y comprueba el diff.

La comprobación final de rutas, proxy de imágenes y cambios manuales de tema se realiza en GitHub después de publicar con autorización.
