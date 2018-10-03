# [SPANISH]

# Filtro bokeh basado en la segmentación fondo/figura 


Diseño de un algoritmo que, dada una imagen sin profundidad de campo, genere un efecto visual similando al filtro bokeh, que realiza un difuminado en función de la distancia. Para ello se realizarán dos grandes pasos diferenciados: el primero será la separación entre el fondo y la figura de una imagen, para tratar de aproximar las relaciones de profundidad entre los distintos elementos de la imagen. Con esta aproximación se aplicará un algoritmo de simulación del filtro bokeh.


# [ENGLISH]

# Background/foreground segmentation-based bokeh effect

This is a web application developed in Python and Django that receives an image (without depth of field information) and tries to generate a blurring effect similar to the bokeh effect from DSLR cameras. This is done in two different steps: the first one tries to estimate the background and foreground elements in the image. After this has been done, the blurring is applied with different coefficients for each level of depth estimated in the first step.

This project was an assignment for a Digital Image Processing subject.

Backend is written entirely on Python 3 and Django, frontend uses Bootstrap and some Javascript/JQuery.
