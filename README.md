# Bluuweb_CursoBootstrap5
Curso: Fundamentos de Bootstrap 5 [ Sass incluido + Guía con códigos ] https://www.youtube.com/watch?v=1kNwZbRiVcQ

Requisitos:
    Visualstudiocode
    nodejs
    live Server. Extensión de VSC
    Live SAS Compiler. Extensión de VSC
    Tema e iconos VSC. Sugiere Dobri

22-sep-2022. 17:15. Lo dejo en el minuto 46:00. Empieza a construir el interior de las tarjetas

23.Sep.2022. 12:34
    Flexbox, Posicionamiento de elementos

    Instalar bootstarp para personalizar con sass
        instalar nodejs
        npm -i bootstrap -v 5.2.1
        en el directorio del proyecto mkdir sass
        dentro de sass crear el archivo custom.scss para todas las modificaciones en las variables de bootstrap
        Instalar en VSC la extensesión Live Sass Compiler. Confirar el valor de Savepath para que el css resultante vaya al directorio css del proyecto
        Quitar el link al CDN de bootstrap y poner al local

        

23.Sep.2022 22:39. Terminada la prsonalización de bootsrap.
    Va a eliminar las lineas no usadas de css
    instalar globalmente:
         sudo npm i -g purgecss
    el script para reducir elcss se pone en package.json dentro de la llave scripts:
        "build": "purgecss --css css/custom.css --content index.html -o css/reducido.css"
        ejecutar npm run build
        cambiar el link en index.html


Parece bueno como referencia básica:
https://www.tutorialesprogramacionya.com/bootstrap5ya