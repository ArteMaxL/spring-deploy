## Despliegue de app Spring Boot en Heroku

1. Crear archivo `system.properties` en el proyecto con el contenido:
````
java.runtime.version=17
````
2. Crear cuenta em heroku.com y github.com
3. Tener configurado git en el equipo
   1. `git config --global user.name "Su Nombre"`
   2. `git config --global user.email email@example.com`
4. Subir el proyecto GitHub desde IntelliJ IDEA desde la opcion: VCS > Share project on GitHub
5. Desde Heroku crear app y elegir metodo GitHub y buscar el repositorio subido
6. Habilitar deploy automatico y ejecutar el Deploy