# Actividad 022 - Scaffolding

- Para poder realizar este actividad debes haber realizado los cursos previos junto con los videos online correspondientes a la experiencia 11.

## Ejercicio 1: Segundo Proyecto.

- Crear un proyecto llamado ***second_app***. :heavy_check_mark:
- Inicializar *Git*. :heavy_check_mark:
- Primer commit. :heavy_check_mark:
- Crear un ***scaffold*** de *Student* con los campos *name* y *age:integer*. :heavy_check_mark:
- Verificar que el archivo migración contenga los cambios necesarios y correr la migración. :heavy_check_mark:
- Confirmar -en el *Schema*- que la migración haya corrido correctamente. :heavy_check_mark:
- Convertir *Index* de *students* en la página de inicio. :heavy_check_mark:
- Segundo commit. :heavy_check_mark:
- Ingresar 2 estudiantes utilizando *rails console* y el método *create*. :heavy_check_mark:
- Ingresar 1 estudiantes a través de la aplicación. :heavy_check_mark:
- Comprobar que los registros se crearon correctamente. :heavy_check_mark:
- Agregar el *CDN* de una plantilla de *[Bootswatch](https://www.bootstrapcdn.com/bootswatch/)*. :heavy_check_mark:
- Agregar las clases de botones de *Bootswatch* a los *links* de *Show*, *Edit* y *Destroy*. :heavy_check_mark:
![ss-students](https://user-images.githubusercontent.com/18556541/26950351-5558f76e-4c6b-11e7-9572-34eb398209a6.png)
- Tercer commit. :heavy_check_mark:
- Agregar un campo nuevo al modelo *Student* llamado *email* de tipo *string*. :heavy_check_mark:
- Revisar y correr la migración. :heavy_check_mark:
- Ingresar un nuevo estudiante mediante *rails console* (incluir el campo *email*). :heavy_check_mark:
- Modificar el *form* de registro de estudiantes para que permita ingresar el correo. :heavy_check_mark:
- Agregar el campo *email* a los *strong params* en el controlador *students*. :heavy_check_mark:
- Cuarto commit. :heavy_check_mark:
- Crear un nuevo controlador llamado *pages* con la página *landing*. :heavy_check_mark:
- En el método *landing* consultar todos los registros de *Student* y almacenarlos en una variable de instancia *@students* :heavy_check_mark:
- En la vista de *landing* iterar la colección *@students* y listar -en una tabla- todos los estudiantes con su respectivo email. :heavy_check_mark:
- Agregar un *navbar* de *Bootswatch* al layout. :heavy_check_mark:
  > El *navbar* sólo debe contener 2 links: uno a *index* y uno a *landing*.
- Quinto commit. :heavy_check_mark:
- Crear un repositorio en *GitHub*. :heavy_check_mark:
- Añadir el *remote* al repositorio de *GitHub* y hacer *push*. :heavy_check_mark:
- Inicializar proyecto en *Heroku* y hacer *push*. :heavy_check_mark: