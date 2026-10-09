1. Analiza
git status
git add README.md
git commit -m "Actualiza documentación"
git push
Explica qué ocurre en cada instrucción.

# Solo se sube los cambios de README.md al repositorio en el caso de que ya este configurado
git status revisa el estado de los archivos a subir
git add README.md prepara solo README.md o los cambios en el
git commit sube los cambios
git push envia los cambios al repositorio

2. Identifica qué falta
# Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

# git commit -m "Nombre" 

# Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

# fork y clone para crear una copia del repositorio localmente

# Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
Indica qué operación utilizarías y explica por qué.
Registra este cambio en un quinto commit con un mensaje descriptivo y súbelo a github.

# git pull, para actuaizar cambios en el repositorio al local