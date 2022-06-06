# Uso de File Storage en Azure
En este repositorio tenemos una demostración del uso de File Storage en Azure.
Esta demostración constará en como subir archivos, conectarla con la computadora y crear directorios (carpetas).

![Microsoft-Azure-File-Storage](https://github.com/DagonNR/File-Storage/blob/main/images/Microsoft-Azure-File-Storage.jpg)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.

---

## Importante
- Los File Storage de Azure cobran, dependiendo de cuanto se almacena en ellos.
- Es necesario crear una "Cuenta de almacenamiento" para poder hacer un "File Storage".

---

## Pasos a seguir
- Lo primero es dentro de [Microsoft Azure](https://portal.azure.com), es crear una "Cuenta de almacenamiento", si ya tienes una ya creada, la puedes usar.
- Entonces te vas al recurso de "Cuenta de almacenamiento", y vas al apartado de "Recursos compartidos de archivos".
![P1](https://github.com/DagonNR/File-Storage/blob/main/images/P1.PNG)

- Ahora vamos a clicar en "+ Recurso compartido de archivos", entonces se nos desplegara un menú en la parte lateral de la pantalla.
- Dentro de este menú nos pedirá un "Nombre" y un "Nivel", el nombre puede ser lo que sea, y en el nivel se refiere a como funcionará.
- Después de llenar estos campos, le damos clic en "Crear"
![P2](https://github.com/DagonNR/File-Storage/blob/main/images/P2.PNG)

- Entonces nos mandará al recurso de "File Storage", y nos aparecerá algo como esto.
![P3](https://github.com/DagonNR/File-Storage/blob/main/images/P3.PNG)

- Ahora vamos a clicar en "Cargar".
- Se nos desplegará un menú en la parte lateral derecha de la pantalla.
- Aquí podremos cargar los archivos que necesitemos.
![P4](https://github.com/DagonNR/File-Storage/blob/main/images/P4.PNG)

- Ahora para conectarse con la computadora, existen varias formas, en este caso lo haremos mediante el "PowerShell".
- Para empezar dentro del recurso de "File Storage", en el apartado de "Información general", vamos a clicar en "Conectar".
- Se nos desplegará un menú en la parte lateral derecha de la pantalla.
![P5](https://github.com/DagonNR/File-Storage/blob/main/images/P5.PNG)

- Si bajamos un poco en dicho menú encontraremo un código el cual copiaremos completo.
![P6](https://github.com/DagonNR/File-Storage/blob/main/images/P6.PNG)

- Ahora toca abrir el "PowerShell" (esto en el caso de tener sistema operativo de Windows, si se tiene macOs o Linux, se haría desde su respectiva terminal).
![P7](https://github.com/DagonNR/File-Storage/blob/main/images/P7.PNG)

- Entonces ya dentro del "PowerShell", pegaremos el código que copiamos antes, y daremos "Enter"
- Y si salió bien nos saldrá un mensaje que dirá "credencial agregada correctamente"
![P8](https://github.com/DagonNR/File-Storage/blob/main/images/P8.PNG)

- Ahora para agregar un "Directorio", dentro del recurso de "File Storage", en el apartado de "Información general", vamos a clicar en "Agregar directorio".
- Nos pedriá un nombre, cuando lo pongamos, le damos clic en "Aceptar".
- Y ya se nos creará nuestro "Directorio", o sea una carpeta dentro del "File Storage".
![P9](https://github.com/DagonNR/File-Storage/blob/main/images/P9.PNG)
