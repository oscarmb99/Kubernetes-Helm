## Caso práctico: Instalar wordpress 

1. Parametrizar el wordpress, indicando dos parámetros: el tipo de servicio y el nombre del blog

Son dos los parámetros que hay que cambiar: service.type y wordpressBlogName

Para instalar wordpress se usa el comando `helm install wordpress bitnami/wordpress --set service.type=NodePort wordpressBlogName=WordpressOscar

2. Comprobación de los objetos creados.


3. Acceso a la aplicación

