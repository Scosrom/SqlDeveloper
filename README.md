# SqlDeveloper
![image](https://github.com/Scosrom/SqlDeveloper/assets/114906778/740ea205-751d-46f6-bd3d-b321a6219085)

<code>Verion 21.2.1</code>

## Pasos de descarga:

1. click en el botón SQL Developer en la pagina de descarga.
   
https://www.oracle.com/tools/downloads/sqldev-downloads-2121.html

![image](https://github.com/Scosrom/SqlDeveloper/assets/114906778/f996e735-f36e-4746-90d0-2f4da6e1ba87)

2. Buscar el sistema operativo, dar click en el enlace de descarga y aparecerá un login para ingresar tus credenciales de Oracle (Si no posees credenciales lo único que tienes que hacer es crear una cuenta en Oracle).

![image](https://github.com/Scosrom/SqlDeveloper/assets/114906778/51c8da8f-6484-45e2-8997-e799dcc44f9b)


### Comandos:

```
cd Descargas

# Convertimos el paquete Red Hat a un paquete de Debian.
sudo alien --scripts -d sqldeveloper-21.2.1-204.1703.noarch.rpm

# Se genera un archivo con el nombre de sqldeveloper_21.2.1-205.1703_all.deb. Para ejecutar este archivo, ejecute la siguiente instrucción:
sudo dpkg --install sqldeveloper_21.2.1-205.1703_all.deb

# Ejecutamos SQL Developer desde el terminal.
sudo /opt/sqldeveloper/sqldeveloper.sh
```


## Crear Icono en el Escritorio


1. nano sqldeveloper.desktop
   
2.Dentro del archivo copiar lo siguiente:

```
[Desktop Entry]
Name=SQL Developer
Exec=/opt/oracle/sqldeveloper/sqldeveloper/sqldeveloper.sh
Icon=/opt/oracle/sqldeveloper/sqldeveloper/icon.png
Terminal=false
Type=Application
Categories=Development;
```
* Exec = Ruta donde esta el script sqldeveloper.sh
* Icon= Ruta donde esta el icono sqldeveloper.

3. Por último, segundo botón y archivo ejecutable.
