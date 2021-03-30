# ing-lab-4

## Trabajo Practico Nro 1

### __2- Crear un repositorio local y agregar archivos__

* Crear un repositorio local en un nuevo directorio.

    ![](assets/paso2.png "Creacion del repositorio local")

* Agregar un archivo Readme.md, que contenga tu nombre y un link a tu CV. Tu cv será otro archivo en el mismo formato, en la misma carpeta.
    * [Readme.md](https://github.com/franciscolmos/TP1-Sistemas-de-control-de-versiones#francisco-augusto-olmos-bossa)
    * [Mi Curriculum Vitae](https://github.com/franciscolmos/TP1-Sistemas-de-control-de-versiones/blob/master/CV.md#francisco-augusto-olmos-bossa)
* Crear los commits de cada caso y proveer mensajes descriptivos.

    ![](assets/punto2.png "se crean y agregan archivos al repo local, se commitea")

### __3- Crear un repositorio remoto__

* Crear un nuevo repositorio en dicha página (vacío)

    * [Repositorio del TP1](https://github.com/franciscolmos/TP1-Sistemas-de-control-de-versiones)

    ![](assets/creacionRepo.png "Creacion del repositorio remoto")
* Asociar el repositorio local creado en el punto 2 al creado en github.
* Subir los cambios locales a github.

    ![](assets/pushPaso3.png "link del repo local al remoto y push del commit")

### __4- Familiarizarse con el concepto de Pull Request__

* Crear un branch local y agregar cambios a dicho branch
    * [Pull Request](https://github.com/franciscolmos/TP1-Sistemas-de-control-de-versiones/blob/master/PR.md)

     ![](assets/branchs.png "Creacion del branck dev")

* Subir el cambio a dicho branch y crear un pull request.
    ![](assets/PR1.png "Creacion del PR con el cambio del agregado del archivo PR.md")

    ![](assets/PR2.png "Creacion del PR con el cambio del agregado del archivo PR.md")

    ![](assets/PR3.png "Creacion del PR con el cambio del agregado del archivo PR.md")

    ![](assets/PR4.png "Creacion del PR con el cambio del agregado del archivo PR.md")

* Completar el proceso de revisión en github y mergear el PR al branch master.

     ![](assets/PR6.png "Se mergea el PR")

### __5- Mergear código con conflictos__

*   Clonar en un segundo directorio de tu equipo el repositorio creado en github.
*   En el clon inicial, modificar el CV.md cambiando algunas lineas.
*   Hacer commit y subir el cambio a master a github.
*   En el segundo clon también realizar cambios en las mismas líneas que se modificaron en el otro directorio.
*   Intentar subir el cambio, haciendo un commit y push. Mostrar el error que se obtiene.

    ![](assets/conflicto1.png "Se intenta pushear a master desde el segundo clon y se genera un conflicto porque ya se pusheo desde el clon original y se modifico el mismo archivo en la misma linea")

    ![](assets/conflicto.png "Se muestra el conflicto generado, el incoming change es el cambio que esta en el remoto, y el head es el cambio que tengo en mi local")

*   Resolver los conflictos del código.
*   Explicar las versiones LOCAL, BASE y REMOTE.
    * [LOCAL, BASE, REMOTO](https://github.com/franciscolmos/TP1-Sistemas-de-control-de-versiones#local-base-remoto)      
*   Pushear el cambio mergeado.

     ![](assets/conflicto3.png "Se resuelve el conflicto y se pushea los cambios")

### __6- Algunos ejercicios online__

*   Entrar a la página https://learngitbranching.js.org/
*   Completar los ejercicios Introduction Sequence

    ![](assets/completoGitBranching.png "Se resuelte el modulo Secuencia introductoria de Learn Git Branching")

