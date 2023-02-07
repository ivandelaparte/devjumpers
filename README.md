GITHUB - Ejercitación final (Paso a paso)

--------------------------------------------------------------------------------------------------
REPOSITORIO DEVJUMPERS:

    1- En la página de github, creo el nuevo repositorio en el que voy a trabajar.

    2- Usando "git clone + link del repositorio", creo en mi equipo una copia del repositorio vacío.

    3- Con "cd + nombre del repositorio", accedo a la carpeta desde la consola.


README:

    4- Con el comando "touch README.txt", creo el archivo "Read me".


COMMIT Y PUSH INICIAL:

    5- Utilizo "git status" para checkear que el archivo se haya creado en el lugar correcto.

    6- Uso "git add", "git commit" y "git push" para subir a la nube el commit inicial.


IGNORAR ARCHIVOS:

    7- Con "touch privado.txt" creo el fichero privado y, con "mkdir privada", creo la carpeta privada.

    8- A través del editor de código, creo el archivo ".gitignore", dentro de él coloco las rutas de los archivos que quiero que git ignore.


AÑADIR FICHERO 1.txt:

    9- Creo el fichero 1 utilizando "touch 1.txt", y lo pusheo al repositorio en Github.


CREAR UNA RAMA v0.2:

    10- Creo la nueva rama y me traslado a ella utilizando "git checkout -b v0.2". 
    ACLARACIÓN: En este paso creo que olvidé pushear la nueva rama, no sé cómo llegué al resultado. Posteriormente volví a intentar este paso en otro repositorio y esta vez lo hice correctamente.


AÑADIR FICHERO 2.txt:

    11- Con "touch 2.txt", creo el fichero 2 en la nueva rama, pusheo los cambios al repositorio remoto.


MERGE DIRECTO:

    12- Utilizo "git checkout main" para trasladarme nuevamente a la rama principal.

    13- Uso "git merge v0.2" para unificar las ramas.


MERGE CON CONFLICTO:

    14- Utilizo el comando "echo 'Hola' >> 1.txt" para agregar el texto al fichero, luego lo pusheo.

    15- Me muevo a la otra rama con "git checkout v0.2".

    16- Vuelvo a utilizar el comando echo pero ahora con un contenido distinto: "echo 'adiós' | tee 1.txt" (Este comando lo busqué por mi cuenta, no sé si es correcto pero funcionó), luego pusheo

    17- Me posiciono en la rama principal con "git checkout main".

    18- Realizo el "git merge v0.2".


LISTADO DE RAMAS:

    19- Utilizo "git branch --merged" para asegurarme de que el merge de haya realizado correctamente.


ARREGLAR CONLICTO:

    20- Con el editor de cógido, me quedo con ambas líneas 'Hola' y 'Adiós' en el fichero 1, realizo el commit y pusheo.


BORRAR RAMA:

    21- Elimino la rama v0.2 que ya no voy a utlizar con "git branch -d v0.2".

LISTADO DE CAMBIOS:
    
    * 71c1f39 (HEAD -> main, origin/main) Añado algunos pasos a la lista del readme.
    * f49d08b Elimino la rama v0.2
    * 2f9fb2c Soluciono un error
    *   b6cb0cf Realizo el merge habiendo solucionado el conlficto.
    |\
    | * 149c8ed (origin/v0.2) Añado el texto al archivo 2.txt en la rama v0.2
    * | 0141311 Añado texto a 1.txt, corrijo errores menores y divido los pasos del
    readme por actividad.
    |/
    * 9eaec30 Se realizó un merge entre la rama main y la rama v0.2
    * 420414b Creación de la nueva rama v0.2 y el archivo 2.txt
    * 45434a4 Creación de archivo 1.txt
    * f89e5a3 Creación de .gitignore
    * 87a3743 Pequeño cambio en el archivo readme para facilitar la lectura
    * df893b7 commit inicial
    * 92c30a7 Creación de archivo README

CREAR UNA TABLA:

| NOMBRE | GITBHUB |
| -- | -- |
| Franco Formigo | [francobenjaminformigo](https://github.com/francobenjaminformigo) |
| Leandro Cuevas | [leandro-cuevas](https://github.com/leandro-cuevas) |
| Armando Torres Quintana | [ArmaTQ](https://github.com/ArmaTQ) |
| Camila Calegari | [camicalegari](https://github.com/camilacalegari) |
| Diego Gómez | [Dielu85](https://github.com/Dielu85) |
