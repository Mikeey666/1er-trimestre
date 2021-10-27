

# IMAGENES
Las imagenes se guardan directamente de dos maneras

- Por un lado (Ráster) podemos hacer una matriz de puntos (mapa de bits) y a cada punto le asignamos un color (píxel)

# Propiedades de una imagen Ráster
Resolución: Un mapa de bits que tiene un tamaño concreto de AxB. La resolución se puede expresar de diferentes formas:

-> Número total de píxeles, normalmente MP (mega píxeles). Esto es el número que resulta de AxB en millones de píxeles.

-> Líneas horizontales. En vídeo se utiliza la cantidad de líneas horizontales, normalmente se asume una proporción concreta entre A y B. Por ejemplo: 4/3 o 16/9.
Las líneas horizontales suelen ser 240p, 480p, 320p, 1080p, 2k y 4k. 

-> Un archivo puede expresar su resolución diciendo AxB. Por ejemplo: una imagen de 350 x 250 píxeles. Esto se utiliza cuando hablamos de archivos concretos.

*NO confundir* con la resolución de impresión medida en puntos de pulgada (ppp) o (dpi) dots per inch.

# Espacios de color

Sistemas para detallar los colores:

- RGB (Red - Green - Blue) para pantallas.
- CMYK (Cyan - Magenta - Yellow - BLack) para imprimir.
- Colores indexados
- Canal (como los 3 canales de RGB) de transparencia. Este canal se llama canal alfa. Los PNG pueden tenerlo. Los GIF y los JPG no.

**FORMATOS COMUNES**

- JPG : Tiene compresión

![a](https://64.media.tumblr.com/dbde3730e54312dcaf69b729eb8a652c/73f0b73e8e06bdc7-0d/s2048x3072/4929d82d07d7f68de207e4383f41824d587e1481.jpg)

- GIF : Colores indexados. Se puede animar

![k](https://gifburg.com/images/gifs/loading/gifs/0002.gif)

- PNG : No tiene gran compresión

![l](https://www.pngkey.com/png/full/255-2559405_-color-azul-acuarela-png.png)

- TIFF : Sin complementos
- Otros particulares: PSD

# Imagenes vectoriales

Se define como un conjunto de formas (lineas, puntos, etc). Cada una de estas formas está definida mátematicamente

· **Formatos:**

- SVG (Scalable Vector Graphic)
- EPS

· **Especificos:**

- DWG 
- DXF

· **Formato mezcla:**

- PDF (Portable Document Format)

```Imagen ráster -------(Vectorizar)-------> Imagen vectorial```
```Imagen vectorial -------(Rasterizar)-------> Imagen ráster```

Rasterizamos una imagen, cuando pasamos de una imagen vectorial a una imagen raster (mapa de bits).

Vectorizar es pasar de un mapa de bits (imagen ráster) a formato vectorial.


### Ejercicio vectorización

Vamos a tomar la imagen del cuadro del león de Rosa Bonheur. Esta es la imagen rasterizada original:

![leon](https://content3.cdnprado.net/imagenes/Documentos/imgsem/19/1998/19984271-9cb6-476d-8655-f012e1fec1bf/0468ba4c-65e8-436e-a267-f76147971ea0_832.jpg)

[Fuente - Museo del prado](https://www.museodelprado.es/coleccion/obra-de-arte/el-cid/19984271-9cb6-476d-8655-f012e1fec1bf)

1. Abrimos INKSCAPE
2. Archivo --> Propiedades del documento --> Tamaño personalizado --> Unidades en PX (Píxeles) --> 600 ancho - 1000 alto
3. Cerramos la pestaña
4. Añadimos la imagen de internet
- Archivo --> Importar
- Arrastrar la imagen
- Copiar y pegar
5. Click derecho en la imagen 
6. Vectorizar mapa de bits

![khjk](https://github.com/Mikeey666/1er-trimestre/blob/main/Captura%20de%20pantalla%20de%202021-10-20%2012-47-33.png?raw=true)

**Explicación del cuadro de vectorizar**

Existen varias opciones. Lo primero es decidir si el programa hará una o varias pasadas. Con una unica pasada, *SIEMPRE* obtendremos una imagen en blanco y negro (que podemos colorear después.)

1. Una única pasada.

- Corte de luminosidad: Junta todos los píxeles más oscuros que umbral.
- Detección de bordes: Revisa el contraste entre píxeles.
- Cuantización de colores: Agrupa zonas similares. 

2. Varias pasadas

Nos permite hacer una imagen vectorial más comlpeja, con varios grises o colores. Esto necesita más capacidad de proceso.

**Leon 1**

Después de importar el león, vamos a ajustar el lienzo. Para ello vamos a propiedades de documento y en tamaño vamos a ajustar pagina o contenido. Seleccionamos la imagen y pulsamos el botón "Ajustar página a contenido o selección"

**Vectorizamos el león con las siguientes características:**

· Múltiples pasadas - Colores - 8 pasadas

- Borramos el ráster
- Guardamos como león1.svg
- Subimos al github

![leon](https://raw.githubusercontent.com/Mikeey666/1er-trimestre/f3913d60d18c1f406b84ae00ab75e093953859aa/leon1.svg)

**Segunda prueba del león**

![leon2](https://raw.githubusercontent.com/Mikeey666/1er-trimestre/fc7096470449552af0e947d4297178f650a4989f/leon2.svg)



**León 01**

16 x 20 px
