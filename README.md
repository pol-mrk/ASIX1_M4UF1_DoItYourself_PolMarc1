# ASIX1_M4UF1_DoItYourself_PolMarc
## Regla 1 ##
Primero utilizaremos el selector universal (``*``) para establecer la fuente del texto de la página (``font-family: 'Poppins', sans-serif;``)
## Regla 2 ##
Ahora definiremmos que en el ``body`` de la web no haya **margenes** (``0``) 
## Regla 3 ##
Después, crearemos una clase de nombre "``flex``" para centrar el texto del ``div`` del HTML.
## Regla 4 ##
Seguidamente, posarem una **id** llamada ``header`` que pondrá el *fondo de color negro*, definirá el tamaño a **100vh** insertará la *imagen que queramos* y **centrará** la **posición del texto** y **cubriremos** el **tamaño del texto**
## Regla 5 ##
Ahora pondremos un selector combinado, (formado por el ``id`` que hemos creado anteriormente, y un ``h1``) de color blanco, sin márgenes, con relleno de **0 20%** y un tamaño de fuente de **50px**
## Regla 6 ##
Después, insertaremos un **id** llamado ``main``, y le pondremos el relleno de la *izquierda* y *derecha* de un **20%**
## Regla 7 ##
Seguidamente, crearemos un selector combinado, (formado por el **id** que hemos creado anteriormente y un ``p``) con el tamaño de letra de **20px**.
## Regla 8 ##
Ahora, crearemos otro selector combinado, (formado por el **id** que hemos creado anteriormente y un ``h1``) con el tamaño de letra de **40px**.
## Regla 9 ##
Seguidamente crearemos un selector de tipo ``iframe`` del **100%** de anchura y **400px** de altura.
## Regla 10 ##
Después, crearemos una **clase** llamada ``content``, donde pondremos la fuente del texto del *contenido* (``font-family: 'Poppins', sans-serif;``)
## Regla 11 ##
Más tarde, crearemos un selector de tipo ``img``, donde pondremos el **100%** del tamaño.
## Regla 12 ##
Seguidamente, pondremos una **id** de nombre ``footer`` (pie de página), donde **centraremos** el texto, pondremos color de fondo *negro*, el color de texto será *gris* y el relleno será de **10px**.
## Regla 13 ##
Ahora aplicaremos esta regla para aplicar un fondo semitransparente: ``body::before`` del **100%** del tamaño, con contenido: "", con **100vh** de **mínima altura**, posición **absoluta**, **0** del ``top`` y de la ``izquierda``, color de fondo: ``linear-gradient(#000000, #000000)`` y opacidad de **0,7**.
## Regla 14 ##
Crearemos una ``id`` llamada "``texto``" y le asignaremos un ``z-index`` de **1**.
## Regla 15 ##
Finalmente pondremos el "``mediaquery``" para:
- El selector combinado (``#header h1``) con relleno **0 1%** y tamaño  de fuente: **40px**.
- El selector id (``#main``) con relleno ``izquierdo`` y ``derecho`` del **1%**
- El selector combinado (``#main p``) con tamaño de fuente **16px**
- El selector combinado (``#main h1``) con tamaño de fuente **35px**