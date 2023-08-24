# GitHub Pages con tema

Pasos seguidos para su creación:

  1. Crear nuevo repositorio público con el siguiente formato (Marcar el *README.md):
     
       ```` tu_nombre_de_usuario.github.io````
     
  2. Crear el archivo:
     
     ````_config.yml````
     
  3. Escribir dentro:

     ```` remote_theme: pages-themes/architect@v0.2.0 ````

     *architect@v0.2.0* es el nombre del tema -> para otros temas ir [aquí](https://pages.github.com/themes/)

  4. Crear el archivo *default.html* en la ruta indicada abajo:
  
    ````_layouts/default.html````
    
  5. Ir al respositorio del tema en cuestión, buscar el archivo *default.html*, copiar su contenido y pegarlo en tu *default.html*.

  6. Ir a *Settings* -> *Pages* -> *Build and deployment* y allí montar la página. En 2 minutos estará lista


>[Link a la GitHub Pages](https://xemicris.github.io/)
