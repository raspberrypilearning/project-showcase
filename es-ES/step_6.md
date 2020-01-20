## Incrustar proyectos

Además de crear enlaces a trinkets como páginas web, también se pueden incrustrar dentro deuna página web.

+ Es posible que prefieras trabajar en modo pantalla completa para tener más espacio:

![captura de pantalla](images/showcase-fullscreen.png)

Presiona la tecla Esc para salir del modo de pantalla completa.

+ Ejecuta (Run) tu trinket y haz clic en el enlace de Cumpleaños Feliz.

+ Haz clic en el menú de trinket y selecciona **embed**. Es posible que tengas que desplazarte hacia abajo si no estás en modo de pantalla completa. Utiliza la barra de desplazamiento de la derecha o la flecha hacia abajo del teclado.

![captura de pantalla](images/showcase-embed-code.png)

+ Selecciona ‘Only show code or result (let users toggle between them)’, que significa “Sólo muestra código o resultado (permitir que los usuarios alternen entre los dos) y copia el código incrustado para el trinket. 

![screenshot](images/showcase-embed.png)

+ Trinket ha creado código HTML para que lo incluyas en tu página web. Éste utiliza una etiqueta `<iframe>` que permite que se pueda incrustrar contenido dentro de una página web.

+ Ahora pega ese código debajo del enlace al trinket de Cumpleaños Feliz:

![captura de pantalla](images/showcase-paste-embed.png)

+ Ejecuta (Run) tu trinket para probarlo. Deberías ver el proyecto de Feliz Cumpleaños incrustrado en la página web. 

![captura de pantalla](images/showcase-embed-output.png)

+ Podría ser que la parte inferior de tu trinket no se vea. Puedes solucionarlo cambiando el valor de la altura (height) en la etiqueta `<iframe>`. 

![captura de pantalla](images/showcase-embed-height.png)

Establece el valor de la altura en **400**. Si realizaste algún cambio en el proyecto de Feliz Cumpleaños es posible que necesites seleccionar un valor diferente.

![screenshot](images/showcase-embed-fixed.png)