## Caso práctico: Instalar wordpress 

1. Parametrizar el wordpress, indicando dos parámetros: el tipo de servicio y el nombre del blog

Son dos los parámetros que hay que cambiar: service.type y wordpressBlogName

Para instalar wordpress se usa el comando `helm install wordpress bitnami/wordpress --set service.type=NodePort,wordpressBlogName=WordpressOscar`

2. Comprobación de los objetos creados.

Se puede comprobar de varias formas:
- Con el comando `helm status wordpress`
- Visualizando qué hay en kubernetes con `kubectl get all`

3. Acceso a la aplicación
Para acceder a la aplicación hay que poner en el navegador la IP de minikube y el puerto que se le haya asignado.
