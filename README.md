# libro
1. Crear un repositorio nuevo con el nombre libro.
2. Clonar el repositorio.
>
`$ git clone git@github.com:Reyvaj14/libro.git`
3. Comprobar el estado del repositorio.
>
`$ git status`
4. Crear un fichero indice.txt con el siguiente contenido:
- Capítulo 1: Introducción a Git
- Capítulo 2: Flujo de trabajo básico
- Capítulo 3: Repositorios remotos
5. Comprobar de nuevo el estado del repositorio.
>
`$ git status`
6. Añadir el fichero.
>
`$ git add indice.txt`
7. Volver a comprobar una vez más el estado del repositorio.
>
`$ git status`
8. Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro” y ver el estado del repositorio.
>
`$ git commit -m "Añadido índice del libro"`
9. Cambiar el fichero indice.txt para que contenga lo siguiente:
- Capítulo 1: Introducción a Git
- Capítulo 2: Flujo de trabajo básico
- Capítulo 3: Gestión de ramas
- Capítulo 4: Repositorios remotos
10. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.
>
`$ git commit -m "Añadido capítulo 3 sobre gestión de ramas"`
11. Crear la carpeta capítulos y crear dentro de ella el fichero capitulo1.txt con el siguiente texto.
- Git es un sistema de control de versiones.
12. Hacer un commit de los cambios con el mensaje “Añadido capítulo 1.”
>
`$ git commit -m "Añadido capítulo 1."`
13. Crear el fichero capitulo2.txt en la carpeta capítulos con el siguiente texto.
- El flujo de trabajo básico con Git consiste en: 1- Hacer cambios en el repositorio. 2- Añadir los cambios. 3- Hacer un commit de los cambios.
14. Añadir los cambios.
>
`$ git add .`
15. Hacer un commit de los cambios con el mensaje “Añadido capítulo 2.”
>
`$ git commit -m "Añadido capítulo 1."`
16. Crear el fichero capitulo3.txt en la carpeta capítulos con el siguiente texto.
- Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultánea en ellas.
17. Añadir los cambios.
>
`$ git add .`
18. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3.”
>
`$ git commit -m "Añadido capítulo 3."`
19. Añadir al final del fichero indice.txt la siguiente línea:
- Capítulo 5: Conceptos avanzados
20. Hacer un commit de los cambios con el mensaje “Añadido capítulo 5 al índice.”.
>
`$ git commit -m "Añadido capítulo 15 al índice."`
21. Crear una nueva rama bibliografia
>
`$ git branch bibliografia`
22. Crear el fichero capitulos/capitulo4.txt y añadir el texto siguiente
23. Hacer un commit con el mensaje “Añadido capítulo 4.”
>
`$ git commit -m "Añadido capítulo 4."`
24. Cambiar a la rama bibliografia.
>
`$ git checkout bibliografia`
25. Crear el fichero bibliografia.txt y añadir la siguiente referencia
- Chacon, S. and Straub, B. Pro Git. Apress.
26. Hacer un commit con el mensaje “Añadida primera referencia bibliográfica.”
>
`$ git commit -m "Añadida primera referencia bibliográfia."`
27. Fusionar la rama bibliografia con la rama master.
>
`$ git merge bibliografia`
28. Mostrar el repositorio incluyendo todas las ramas.
29. Eliminar la rama bibliografia.
>
`$ git branch -d bibliografia`
30. Crear la rama bibliografia.
>
`$ git branch bibliografia`
31. Cambiar a la rama bibliografia.
>
`$ git checkout bibliografia`
32. Cambiar el fichero bibliografia.txt para que contenga las siguientes referencias:
- Scott Chacon and Ben Straub. Pro Git. Apress.
- Ryan Hodson. Ry’s Git Tutorial. Smashwords (2014)
33. Hacer un commit con el mensaje “Añadida nueva referencia bibliográfica.”
>
`$ git commit -m "Añadida nueva referencia bibliográfca."`
34. Cambiar a la rama master.
>
`$ git checkout main`
35. Cambiar el fichero bibliografia.txt para que contenga las siguientes referencias:
- Chacon, S. and Straub, B. Pro Git. Apress.
- Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.
36. Hacer un commit con el mensaje “Añadida nueva referencia bibliográfica.”
>
`$ git commit -m "Añadida primera referencia bibliográfia."`
37. Fusionar la rama bibliografia con la rama master.
>
`$ git merge bibliografia`
38. Resolver el conflicto dejando el fichero bibliografia.txt con las referencias:
- Chacon, S. and Straub, B. Pro Git. Apress.
- Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.
- Hodson, R. Ry’s Git Tutorial. Smashwords (2014)
39. Hacer un commit con el mensaje “Resuelto conflicto de bibliografía”.
>
`$ git commit -m "Resuelto conflicto de bibliográfia."`