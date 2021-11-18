# Dataset-Limon-Tahiti

En el presente repositorio se encuentra un dataset destinado a la detección de bultos de Limón Tahití, el dataset cuenta con un total de 725 imágenes, distribuidas en 3 carpetas. La primera de ellas es "train" donde se encuentra un 90% de las imágenes, seguidamente la carpeta "valid" con un 5% y, finalmente, "test" con otro 5%. La única clase presente se denominó como: Bulto.

Cada carpeta cuentan con las imágenes preprocesadas (tamaño: 416x416 y orientada a un solo sentido) y su respetivo .txt donde se encuentra la ubicación, la cantidad de bultos, entre otros factores. Cabe resaltar que el formato establecido para este dataset es el de YOLO Darknet.

Por último, este dataset ya cuenta el proceso de data augmentation, donde se estableció la siguiente configuración:

  - Rotación entre -8 y +8 grados
  - Luminosidad entre -20 y 20 porciento
  - Difuminación de 0.75px
  - Ruido de 4% de pixeles
  - Cortes de 12 cajas con 6% de tamaño cada una
  - Se aplicó el mosaico
