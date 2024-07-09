# Lectura-11

Contenido de audio y video

### 1.Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.
Usar audio y video en la web por mucho tiempo, desde comienzos del 2000 cuando empezamos a tener un ancho de banda suficientemente rápido para soportar cualquier tipo de video (los archivos de video son mucho más grandes que texto o imágenes). En los inicios, las tecnologías web nativas como HTML no tenían el soporte para incrustar audio y video en la Web, tecnologías privadas (o basadas en plugins).
### 2.Describe el uso de los atributos src y controls en el elemento "video".
El atributo *src* se utiliza para indicar el nombre del archivo de vídeo que se desea reproducir.
Debes incluir una o más fuentes de vídeo dentro del elemento "*video*" utilizando la etiqueta "*source*".
Cada fuente de vídeo debe tener un atributo src que apunte a la ubicación del archivo de vídeo y un atributo type.
### 3.¿Por qué es importante tener contenido de respaldo en el elemento "video"?
Es importante por que va depender de los sistemas operativos o dispotivos y la accesibilidad, tener el respaldo nos ayuda a adaptarnos.
### 4.Escribe una historia corta en donde <audio> y <video> son personajes. A Complete Guide To Grid.
### 5.¿En qué se diferencia el layout Grid del Flex?
Flex: Diseñado para una dimensión (filas o columnas).
Ideal para alinear elementos en una sola dirección.

Grip: Diseñado para dos dimensiones (filas y columnas).
Perfecto para crear diseños complejos y estructuras de cuadrícula.
### 6.Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.
Grid container:
Es el elemento padre al que se le aplica display: grid.
Actúa como un contenedor para todos los elementos hijos del grid.
Define el número de filas y columnas en el diseño de la cuadrícula.

Grid item:
Son los descendientes directos del contenedor con display: grid.
Representan los elementos individuales dentro de la cuadrícula.
Cada grid item ocupa una o más celdas de la cuadrícula.

Grid line:
Son las líneas divisorias que componen la estructura del grid.
Definen los límites de las filas y columnas en la cuadrícula.

# Imágenes Responsivas

### 1.Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?
Adaptabilidad a todos los dispositivos:
Permite que un sitio web se ajuste automáticamente a diferentes tamaños de pantalla y dispositivos, desde smartphones hasta tablets y ordenadores de sobremesa.
Ofrece una experiencia de usuario consistente sin importar el dispositivo utilizado.

Mejora de la experiencia del usuario:
Los usuarios esperan que los sitios web se vean y funcionen bien en sus teléfonos y tablets.
Un diseño responsivo evita una alta tasa de rebote y mejora el tiempo de permanencia.

Aumento del alcance y la visibilidad:
Más del 50% de las búsquedas en internet se realizan a través de dispositivos móviles.
Los motores de búsqueda priorizan los sitios web responsivos en sus algoritmos de ranking.

### 2.Define los siguientes atributos de <img>: srcset y sizes. Escribe un ejemplo de cómo se usan.
Atributo srcset:
Define una lista de imágenes alternativas con diferentes tamaños o resoluciones.
El navegador selecciona la imagen más adecuada según el dispositivo y la densidad de píxeles (DPR).
Atributo sizes:
Indica las dimensiones de representación de la imagen en diferentes puntos de interrupción (breakpoints).
Se combina con el descriptor w del atributo srcset.

### 3.¿Cómo es que srcset es más útil para las imágenes responsivas que CSS o JavaScript?
Selección automática de imágenes:
srcset permite al navegador seleccionar automáticamente la imagen más adecuada según la densidad de píxeles (DPR) y el ancho de la ventana gráfica (viewport).
No requiere intervención manual ni lógica adicional.
Optimización de carga:
Al proporcionar múltiples versiones de la misma imagen, srcset permite cargar solo la imagen necesaria para evitar descargas innecesarias.
Esto mejora la velocidad de carga y reduce el consumo de datos.
Compatibilidad con navegadores antiguos:
srcset es compatible con una amplia gama de navegadores, incluidos los más antiguos.
No depende de JavaScript o estilos CSS avanzados.



