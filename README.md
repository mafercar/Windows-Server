# Windows-Server

## Organización de la empresa
La empresa está organizada en tres departamentos los cuales son: Almacén, ventas y marketing. Cada departamento tiene un equipo y dos empleados que solo podrán entrar al equipo que está en su departamento.

En la empresa solo hay una impresora para todos.

Los usuarios solo podrán entrar al sistema de 8:00 a 15:00 de lunes a viernes.

Todo el sistema está en la red 192.168.15.0/24.

## Cambio de la IP y nombre del servidor
Antes de hacer nada en el servidor tenemos que hacer unas configuraciones básicas. Lo primero que haremos es cambiar el nombre del equipo a uno distintivo. También hay que cambiar la IP del servidor a una estática para que el servidor siempre esté accesible y no haya problemas de acceso desde los clientes.
![](https://github.com/mafercar/Windows-Server/blob/master/WS1.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS2.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS3.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS4.png)

## Instalación de Active Directory
Para que nuestro equipo empiece a funcionar como servidor necesitamos un servicio. Los servicioes se agregan desde el enlace de roles. Desde ahí siguiendo los pasos instalaremos el rol de Active Directory.
![](https://github.com/mafercar/Windows-Server/blob/master/WS5.png)
Siguiente hasta llegar a finalizar y esperamos que se instale.
![](https://github.com/mafercar/Windows-Server/blob/master/WS6.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS7.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS8.png)
Le damos a la ventana con la señal de alarma y hacemos lo siguiente.
![](https://github.com/mafercar/Windows-Server/blob/master/WS9.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS10.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS11.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS12.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS13.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS14.png)
## Creación de la unidad organizativa de la empresa
Nuestra empresa tiene tres departamentos en los que hay un equipo y dos empleados en cada uno. Lo primero que tenemos que hacer es crear la unidad organizativa, para ello hacemos clic en herramientas y nos vamos a la gestión de Active Directory. Desde hay hacemos clic derecho sobre servidor(local) y seleccionamos crear una nueva unidad organizativa a la que le daremos el nombre deseado.
![](https://github.com/mafercar/Windows-Server/blob/master/WS15.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS16.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS17.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS18.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS19.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS20.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS21.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS22.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS23.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS24.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS25.png)
Ahora vamos a limitar las horas en las que los usuario pueden iniciar sesión en el sistema.

![](https://github.com/mafercar/Windows-Server/blob/master/WS26.png)
## Instalación de DHCP
Lo siguiente que vamos a hacer es agregar un nuevo rol a nuestro servidor de DHCP. Esto lo hacemos de la misma forma en la que hemos añadido el Active Directory.


![](https://github.com/mafercar/Windows-Server/blob/master/WS27.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS28.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS29.png)
![](https://github.com/mafercar/Windows-Server/blob/master/WS30.png)
