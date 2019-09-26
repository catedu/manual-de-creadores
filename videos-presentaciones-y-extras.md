Si te fijas en FILES verás un archivo que se llama *book.json* si eres curioso **te hemos puesto el siguiente código** \{"plugins": ["youtube", "accordion", ... esto permite añadir ciertos códigos
#Vídeos
Por ejemplo nos interesa embeber el siguiente vídeo de Youtube: https://www.youtube.com/watch?v=JXamK7Lbp4I

Pues el código es el siguiente:

![](/assets/2019-09-26 11_38_46.jpg)

Y queda así:

{%youtube%}https://www.youtube.com/watch?v=JXamK7Lbp4I{%endyoutube%}

#Presentaciones

Es ideal para hacer videotutoriales de forma rápida y muy editable. Recomendamos Google y poner su código embebido

Ver apartado 6.- [Video tutoriales](/video_tutoriales.md) 6.1.-[Presentación de Google](/presentacin_de_google.md) 6.2.-[Como conseguir el código embed](/como_conseguir_el_cdigo_embed_de_presentaciones_de_google.md)

#Acordeon
Si pones el siguiente código:

\%accordion% Solución %accordion%

Aquí pongo mi solución
bla, bla, bla, imágenes, vídeos ...

\%/accordion%

Este es el resultado:

%accordion% Solución %accordion%

Aquí pongo mi solución
bla, bla, bla, imágenes, vídeos ...

%/accordion%

#Tablas
Si pones este código:

\| Orden       | MotorA | MotorB |
\|-------------|--------|--------|
\| Velocidad   | 10     | 11     |
\| Dirección 1 | 8      | 12     |
\| Dirección 2 | 9      | 13     |

El resultado es:

| Orden       | MotorA | MotorB |
|-------------|--------|--------|
| Velocidad   | 10     | 11     |
| Dirección 1 | 8      | 12     |
| Dirección 2 | 9      | 13     |
