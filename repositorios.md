# Trabajando con repositorios

1. Listar repositorios

Para listar los repositorios se usa el comando `helm repo list`.

2. Añadir repositorios: bitnami

El comando para añadir repositorios (en este caso el de bitnami) se usa el comando

`helm repo add "bitnami" "https://charts.bitnami.com/bitnami"`.

3. Quitar repositorios

Para eliminarlo se usa: `helm repo remove bitnami`.

4. Buscar charts: nginx, wordpress, etc

Para buscar un chart se usa el comando `helm search repo nginx` (en el caso que se quiera buscar nginx).
