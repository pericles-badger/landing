# Landing Page
## Proyecto Bedu

### Pasos
#### 1 Crear archivos y carpetas
  - Carpeta index
  - Carpeta style
  - Carpeta Imagenes
    - Archivos index y style                                                    (index.html en la raíz, style en carpeta style)

#### 2 Crear repositorio en github 
  - git init                                                                     (Inicializa el repo)
  - git add -                                                                    (Pone los archivos en staging)
  - git commit -m "nombre del repositorio"                                       (Nombra el repo)
  - git branch gh-pages                                                          (crea la rama "gh-pages")
  - git checkout gh-pages                                                        (cambia a la rama "gh-pages")
  - Abrir git hub y crear el repo con el nombre que establecimos originalmente   (crea el repo remoto)
  - En git hub: Copiamos la línea con el URL del repo                            (obtenemos la dirección remota del repo)
  - En la terminal local: git remote add origin "pegar url de repo remoto"       (Especifica la dirección remota del repo)
  - git push -u origin gh-pages                                                  (Sube los archivos al repo remoto desde la carpeta gh-pages)

#### 3 Revisar el repo remoto
  - En git hub: Ir al repo remoto
  - Revisar la pestaña actions                                                    (Revisar que se haya completado el proceso del repo -indicador verde-
  - Una vez que tenemos indicador verde: Vamos a settings
  - Seleccionamos "settings" en el menú lateral izquierdo -escritorio-
  - Seleccionamos "pages"
  - hacemos click en el URL proporcionado.

### Para actualizar el repo
  - git add                                                                      (pone las actualizaciones en staging)
  - git commit -m "nombre del repo actualizdo"                                   (Nombra la actualización)
  - git push -u origin gh-pages                                                  (sube la actualización)

