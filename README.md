Este proyecto contiene dos carpetas, cada una con su compilador adaptado a la etapa solicitada:

1. /compilador_etapa1/
   - Contiene el c1shell.py con solo el análisis léxico y sintáctico clásico.
   - Al procesar c1.in, reconoce tokens pero mostrará error sintáctico si usa '^', '/', 'if', etc.

2. /compilador_etapa2/
   - Contiene el c1shell.py con el análisis léxico + sintáctico extendido.
   - Procesa correctamente '^', '/', 'if', comparadores y strings.

Estructura del proyecto

proyecto_compilador_final_entrega/

├── compilador_etapa1/

   │   ├── c1shell.py

   │   ├── c1.in

└── compilador_etapa2/
 
   ├── c1shell.py
 
   ├── c1.in

----------------------------------------------------
Cómo ejecutar cada etapa (en la terminal de python)
----------------------------------------------------

Para la Etapa 1
---------------
cd "E:\...\proyecto_compilador\compilador_etapa1"
python c1shell.py c1.in c1.out

Verás en pantalla el análisis léxico. 
El archivo c1.out se generará en esa misma carpeta.

Para la Etapa 2
---------------
cd "E:\...\proyecto_compilador\compilador_etapa2"
python c1shell.py c1.in c1.out

Aquí el compilador procesará correctamente
las expresiones con '^', '/', 'if', '[ ]' y strings.
