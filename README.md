
                               
                                 
                    
                   
 # Aplicacion WEB -> CREATE-READ-UPDATE-DELETE (CRUD)
 ##                                              Spring Web Mvc + Maven + Tomcat + MySQL
 Para este proyecto se utilizo el IDE Spring Tool Suite, asi que vamos a la pestaña File -> New -> Maven Project y creamos un nuevo proyecto web en maven.
![spring2](https://user-images.githubusercontent.com/41167366/46326840-ab62d900-c5b3-11e8-9557-c609cea20691.png)
Selecionamos un archetype que se encuentra en el repositorio de Maven.

![spring3](https://user-images.githubusercontent.com/41167366/46352730-53f25680-c60f-11e8-862c-1060cb88fd56.png)

 Una vez creado convertimos ese proyecto a Spring.

![spring4](https://user-images.githubusercontent.com/41167366/46353007-fdd1e300-c60f-11e8-9e53-852a7bec0c85.png)

 Ya tenemos el proyecyo en Spring, pero yo agregare las dependencias al archivo POM, las dependencias las podemos encontrar en la siguiente dirección: https://mvnrepository.com/, el archivo queda de la siguiente manera.

![spring5](https://user-images.githubusercontent.com/41167366/46353287-a122f800-c610-11e8-9b4b-f61c4e5cc860.png)
![spring6](https://user-images.githubusercontent.com/41167366/46356613-f282b580-c617-11e8-9db3-1e04707be498.png)
![spring7](https://user-images.githubusercontent.com/41167366/46356614-f282b580-c617-11e8-8ec0-4b76113e69ad.png)
![spring8](https://user-images.githubusercontent.com/41167366/46356732-2c53bc00-c618-11e8-94e5-84e6c736a396.png)


 Creamos la siguiente carpeta con el nombre recursos en el directorio  que se muestra en la imagen y añadimos el siguiente archivo con nombre aplicacion y extension properties que contendra la información para conectarnos a la base de datos.
El archivo debe quedar con la siguiente información.
![spring14](https://user-images.githubusercontent.com/41167366/46358287-8f931d80-c61b-11e8-9238-15a4daa7a5e4.png)
![spring15](https://user-images.githubusercontent.com/41167366/46358562-17792780-c61c-11e8-8420-2776cfb10a5b.png)

Creamos la siguiente carpeta con la siguiente dirección -> src/main/java
![spring16](https://user-images.githubusercontent.com/41167366/46449754-9b2d3400-c742-11e8-8882-9a5e11d72227.png)
![spring17](https://user-images.githubusercontent.com/41167366/46449852-10006e00-c743-11e8-8441-d18ecb1d83dd.png)



