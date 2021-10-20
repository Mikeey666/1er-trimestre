

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
