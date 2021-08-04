Esta es una web ficticia que desarrollé para un servicio de diseño gráfico, en este caso reemplacé el CSS en las secciones que estuve trabajando por archivos SCSS.
Como compilador utilicé la herramienta LIVE SASS de Visual Studio Code en lugar de los paquetes Node moon y Watch CSS.
Los @import están todos en el archivo "custom.scss" en la carpeta "scss"

- Cambié el nombre antiguo de la página por uno nuevo.
- Eliminé imágenes innecesarias que me olvidé de quitar.
- Cambiado el logo en todas las páginas.
- Actualicé los favicons.
- Creé variables para las fuentes.
- Creé una variable para los colores azules y azules claros (para los :hover) que se repiten por toda la web.
- Creé un mixin @marpad en _variables.scss para setear el padding y margin a 0 en todos los lugares que lo necesitaba.
- Creé un each para decorar los bordes de las cajas de servicios.html con el color principal haciendo uso de este mismo a través de la variable creada anteriormente.
- Modifiqué y mejoré estéticamente la página de servicios.html con su respectivo @each

Utilicé .gitignore para no subir al repositorio las carpetas: 
- node_modules
- vscode

Y los archivos: 
- package.json
- package-lock.json

Para esta entrega integré las recomendaciones de mejora de la tutora Dahiana en la tercer pre entrega final:
1) Integrar los enlaces funcionales a las redes sociales en el navbar.
2) En la sección de servicios al momento de pasar sobre el botón "Ver más" tiene una pequeña animación.
3) En la sección de contacto una de las cajas quedaba más grande que las demás porque el texto era muy largo, acorté el texto.

Al ser un sitio ficticio no tiene redes sociales, por ello los enlaces en los iconos de las mismas te lleva a la web oficial. Lo mismo con el número de WhatsApp falso que sale en contacto.html