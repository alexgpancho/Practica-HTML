# Impacto de las Tecnologías Web en la Sociedad y los Negocios

Este proyecto es una demostración del impacto de las tecnologías web en la sociedad y los negocios, utilizando HTML5 para crear un sitio web simple y efectivo. El proyecto incluye una página principal y tres páginas secundarias, organizadas con etiquetas semánticas de HTML5 y enlaces de navegación.

## Estructura del Proyecto

- `index.html`: Página principal.
- `sociedad.html`: Impacto de las tecnologías web en la sociedad.
- `negocios.html`: Impacto de las tecnologías web en los negocios.
- `contacto.html`: Página de contacto con un formulario embebido.
- `img/`: Carpeta que contiene imágenes utilizadas en el sitio web.
- `videos/`: Carpeta que contiene video utilizado en el sitio web.
- `README.md`: Este archivo de documentación.

## Proceso de implementación:
- Se realiza el diseño previo de la página usando una web como figma, en este caso al ser sencilla se aprovecho el proceso de maquetado de la web aprendido en clase
- Se procedió a investigar sobre el tema para generar el contenido
- Se generó el repositorio con su carpeta local en los archivos de xampp
- Se realiza el primer commit y se comenzó a generar el código
- Mientras se escribe el código es posible visualizarlo en la dirección: localhost/directorio-del-proyecto
- Se valida la estructura del código desde: https://validator.w3.org/#validate_by_input
- Una vez realizados los cambios se realiza un push en git para subir la información al repositorio

## Fuentes Bibliográficas

1. **HTML5**: 
   - [Referencia de HTML5 en MDN Web Docs](https://developer.mozilla.org/es/docs/Web/HTML)
   - *"HTML5: The Missing Manual" by Matthew MacDonald*
   
2. **Impacto Tecnológico en la Sociedad**: 
   - [Artículo sobre el impacto de la tecnología en la sociedad](https://dialnet.unirioja.es/descarga/articulo/4281033.pdf)
   - *Becerril, J. I., Lassard, A. P. V., Sotomayor, A. L., Ojeda, G. A. O., Sánchez, A. R. D., & Parra, R. T. (2012). La web 2.0: un análisis de su impacto en lo social, político, cultural y económico. Investigación Universitaria Multidisciplinaria: Revista de Investigación de la Universidad Simón Bolívar, (11), 23-34.*
   
3. **Impacto Tecnológico en los Negocios**:
   - [Estudio sobre el impacto de la tecnología en los negocios](https://oldri.ues.edu.sv/id/eprint/12315/1/TG-MAF%20658.15%20A686.pdf)
   - *Argueta Osorio, M. D. J. (2006). El Impacto de las Tecnologías de la Información en los Negocios (Doctoral dissertation, Universidad de El Salvador).*

## Uso de GitHub desde VSCode

### Configuración Inicial

1. **Clonar un Repositorio**:
   - Abre VSCode.
   - Presiona `Ctrl+Shift+P` para abrir la paleta de comandos.
   - Escribe `Git: Clone` y selecciona la opción.
   - Introduce la URL del repositorio de GitHub y selecciona una carpeta local donde clonar el repositorio.

2. **Crear un Nuevo Repositorio**:
   - Crea una carpeta nueva en tu máquina.
   - Abre esa carpeta en VSCode.
   - Abre la terminal integrada (`Ctrl+`).
   - Inicializa un nuevo repositorio de Git con `git init`.
   - Añade los archivos al control de versiones con `git add .`.
   - Realiza tu primer commit con `git commit -m "Initial commit"`.

### Realizar Commits y Sincronizar con GitHub

1. **Realizar Cambios y Hacer Commit**:
   - Realiza cambios en tus archivos.
   - Guarda los cambios.
   - Añade los cambios al área de preparación con `git add .`.
   - Realiza un commit describiendo los cambios con `git commit -m "Descripción de los cambios"`.

2. **Subir Cambios a GitHub**:
   - Asegúrate de haber configurado el repositorio remoto (`git remote add origin URL_DEL_REPOSITORIO`).
   - Sube los cambios con `git push origin master`.

## Información Básica sobre XAMPP

XAMPP es fácil de instalar y contiene MariaDB, PHP y Perl. Es una herramienta potente para desarrollar aplicaciones web localmente. 

### Instalación y Configuración

1. **Descargar XAMPP**:
   - Visita [la página oficial de XAMPP](https://www.apachefriends.org/index.html).
   - Descarga la versión adecuada para tu sistema operativo.

2. **Instalar XAMPP**:
   - Ejecuta el instalador descargado.
   - Sigue las instrucciones en pantalla para completar la instalación.

3. **Colocar Archivos del Proyecto**:
   - Coloca tus archivos del proyecto en la carpeta `htdocs` dentro del directorio de instalación de XAMPP.
   - Accede a tu proyecto en el navegador web visitando `http://localhost/nombre_de_tu_carpeta`.
