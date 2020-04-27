# Know if you have git

git --version

# Instalando toolbelt

npm i -g vtex

# Iniciar sesion

vtex login contaVTEX

# Confirmar nombre de cuenta y Workspace

vtex whoami

# Crear un workspace

vtex use nome-do-workspace
exam: https://{workspace}--{cuenta}.myvtex.com
live exam: https://wsdevjesus--ecomsurtest.myvtex.com

# Tema

Es un ARREGLO DE BLOQUES.

# Bloques

Hay 4 niveles

- Estilo Semántico (styles)
- Propiedades (props)
- Clases CSS (handles)
- Hijos (children)

# GIT

Lo que hicimos fue clonar el repositorio base de store front desde nuestro github.

Realizamos un cambio, hicimos push en master y creamos una nueva rama "infocard" hicimos un cambio, commiteamos, push y guardamos.

# No olvide enlazar

En todo momento, al abrir el terminal VSCode, puede ejecutar un vtex link y acompañar la evolución de su proyecto en https://{workspace}--{conta}.myvtex.com . Asegúrese de que visualmente la solución es equiparable con lo que se presentó y que no se haya producido ningún error en el enlace.

# Que pasa si no enlaza la tienda

Si te sale el error GRAPHQL solo significa que hay APPS que no tienes instaladas, ojo, además deben ser instaladas en orden:

- vtex.store-sitemap
- vtex.store
- vtex.admin-pages
- vtex.store-graphql

Usando el comando: vtex link {{mas tu app a instalar}}

y si instalas una app en el orden incorrecto, igual puedes desinstalar la app con el comando:

vtex link {{app a desinstalar}}

y volver a instalar todo.

# Debugging de elementos en VTEX IO

Como siempre, puedes usar tu inspector de turno, pero además, al tener bien enlazada la tienda, puedes hacer uso al queryparam "?__inspect". Ejemplo:

https://wsdevjesus--ecomsurtest.myvtex.com/?__inspect
