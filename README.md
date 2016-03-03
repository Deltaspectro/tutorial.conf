### Instalacion

##Descargar el archivo tutoria.conf
>Abre el archivo con tu editor de texto favorito, una vez hecho esto deves de modificar lo siguiente:

```
DocumentRoot <Directorio en donde se encuentra tu proyecto>/<Nombre del proyecto>/public>

<Directory <Directorio en donde se encuentra tu proyecto>/<Nombre del proyecto>/public>
```

##Crea un nuevo archivo de configuracion
>desde la terminal crear un nuevo documento de texto en la siguiente ruta: 
```
/etc/apache2/site-avaliable/
```

#Ejemplo 
```
nano /etc/apache2/sites-avaliable/tutorial.conf
```

>y pegar el contenido del archivo modificado 

##Dar de alta el archivo de configuracion

- Desde la terminal escribir "a2ensite nombredelarchivo.conf"
- activar modo reescritura "a2enmod rewrite"

##Editar la lista de host

```
nano /etc/hosts

127.0.0.1       <Servername>
```

