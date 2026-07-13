EJECUCIÓN LOCAL DE EMERGENCIA
PORTAFOLIO DE CIUDADANÍA RESPONSABLE

Utilice este procedimiento únicamente si el enlace público de la página no funciona.

Este proyecto está desarrollado con HTML, CSS y JavaScript.
No requiere compilación, instalación de dependencias ni configuración de una base de datos.


============================================================
MÉTODO 1: ABRIR DIRECTAMENTE EL ARCHIVO HTML
============================================================

1. DESCARGAR EL PROYECTO

1. Abra este repositorio en GitHub.
2. Presione el botón verde que dice:

   Code

3. Seleccione:

   Download ZIP

4. Espere a que termine la descarga.

El archivo descargado tendrá un nombre parecido a:

nombre-del-repositorio-main.zip

Normalmente se guardará en la carpeta:

Descargas


2. DESCOMPRIMIR EL PROYECTO

1. Abra el Explorador de archivos de Windows.
2. Entre en la carpeta:

   Descargas

3. Busque el archivo ZIP descargado.
4. Haga clic derecho sobre el archivo.
5. Seleccione:

   Extraer todo...

6. Presione:

   Extraer

IMPORTANTE:
No se debe ejecutar la página mientras los archivos todavía estén dentro del ZIP.


3. VERIFICAR LOS ARCHIVOS

Dentro de la carpeta extraída deben aparecer los siguientes elementos:

index.html
styles.css
script.js
assets
documentos

La estructura debe conservarse así:

proyecto/
├── index.html
├── styles.css
├── script.js
│
├── assets/
│   └── producto-ia.jpeg
│
└── documentos/
    └── ciudadania-responsable-inicial.pdf

No se deben mover, eliminar ni cambiar de nombre los archivos o carpetas.


4. ABRIR LA PÁGINA

1. Busque el archivo:

   index.html

2. Haga doble clic sobre él.
3. La página se abrirá en el navegador predeterminado.

Si Windows pregunta con qué programa desea abrirlo, seleccione uno de estos navegadores:

Mozilla Firefox
Google Chrome
Microsoft Edge

No debe abrirse con Word, Bloc de notas o un editor de código para visualizar la página.


============================================================
MÉTODO 2: EJECUTAR MEDIANTE UN SERVIDOR LOCAL
============================================================

Este método se recomienda si al abrir index.html directamente no aparecen correctamente el PDF, el video o algún otro elemento.


------------------------------------------------------------
OPCIÓN A: VISUAL STUDIO CODE CON LIVE SERVER
------------------------------------------------------------

REQUISITOS

Tener instalado:

Visual Studio Code


PROCEDIMIENTO

1. Abra Visual Studio Code.
2. Seleccione:

   File
   Open Folder

3. Seleccione la carpeta descomprimida del proyecto.
4. En el panel izquierdo, busque:

   index.html

5. Haga clic derecho sobre index.html.
6. Seleccione:

   Open with Live Server

La página se abrirá en una dirección parecida a:

http://127.0.0.1:5500/index.html


SI NO APARECE "OPEN WITH LIVE SERVER"

1. Abra la sección:

   Extensions

2. Busque:

   Live Server

3. Instale la extensión creada por Ritwick Dey.
4. Vuelva a hacer clic derecho sobre index.html.
5. Seleccione:

   Open with Live Server

No es necesario modificar el código.


------------------------------------------------------------
OPCIÓN B: SERVIDOR LOCAL CON PYTHON
------------------------------------------------------------

Utilice esta alternativa si Python ya está instalado en el equipo.

1. Abra la carpeta descomprimida del proyecto.
2. Haga clic en la barra superior donde aparece la dirección de la carpeta.
3. Escriba:

   cmd

4. Presione Enter.

Se abrirá una terminal ubicada dentro de la carpeta del proyecto.

5. Escriba:

   python -m http.server 8000

Si el comando anterior no funciona, pruebe:

   py -m http.server 8000

6. Presione Enter.
7. Abra Firefox, Chrome o Edge.
8. Escriba en la barra de direcciones:

   http://localhost:8000

La página debería abrirse automáticamente.

Para detener el servidor:

1. Vuelva a la terminal.
2. Presione:

   Ctrl + C


============================================================
PROBLEMAS COMUNES
============================================================

1. LA PÁGINA APARECE SIN DISEÑO

Compruebe que index.html y styles.css estén dentro de la misma carpeta.

No mueva únicamente index.html al escritorio.

La estructura debe mantenerse así:

index.html
styles.css
script.js
assets/
documentos/


2. LA IMAGEN NO APARECE

Compruebe que exista el archivo:

assets/producto-ia.jpeg

El nombre debe ser exactamente:

producto-ia.jpeg


3. EL PDF NO APARECE

Compruebe que exista el archivo:

documentos/ciudadania-responsable-inicial.pdf

También puede abrir el PDF directamente entrando en la carpeta documentos y haciendo doble clic sobre el archivo.


4. EL VIDEO NO SE REPRODUCE

El video requiere conexión a internet.

Si el reproductor integrado falla, utilice el enlace directo ubicado debajo del video.

También puede abrirlo directamente desde:

https://www.youtube.com/watch?v=Li2jifjbCuU


5. EL NAVEGADOR MUESTRA UNA VERSIÓN ANTERIOR

Actualice la página con:

Ctrl + F5


6. LA PÁGINA NO ABRE AL HACER DOBLE CLIC

Pruebe uno de estos métodos:

- Abrir index.html con Firefox.
- Abrir index.html con Google Chrome.
- Abrir index.html con Microsoft Edge.
- Ejecutar el proyecto mediante Live Server.
- Ejecutar el proyecto mediante Python.


============================================================
RESUMEN RÁPIDO
============================================================

1. Presionar Code.
2. Seleccionar Download ZIP.
3. Ir a Descargas.
4. Hacer clic derecho sobre el ZIP.
5. Seleccionar Extraer todo.
6. Abrir la carpeta extraída.
7. Hacer doble clic sobre index.html.
8. Si algo falla, ejecutar con Live Server o Python.
9. Si el video falla, abrirlo directamente en YouTube.


============================================================
INFORMACIÓN DEL PROYECTO
============================================================

Autor: Gerardo Freire
Carrera: Ingeniería Electrónica
Universidad: Universidad San Francisco de Quito
Curso: PASEC
Organización: Refugio Vuelve y Viduka
Población o entidad: Perros rescatados de situaciones de abandono o maltrato
Año: 2026
