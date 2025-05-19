# Splash Screen Photo Gallery

Se implementó un Splash Screen para mejorar la experiencia de usuario al iniciar la aplicación y se personalizó el ícono de la app.
1.  Se agregó el plugin oficial de splash screen, necesario para que funcione la pantalla de carga en Android con el comando:
   **cordova plugin add cordova-plugin-splashscreen**

![image](https://github.com/user-attachments/assets/991906d5-febc-45f2-ac07-a4e0cec1f81f)

2.  Se creó una carpeta llamada resources/ en la raíz del proyecto, donde se colocaron dos imágenes base:

    icon.png

    splash.png

    ![image](https://github.com/user-attachments/assets/146f6657-9340-4aab-b436-919b9696c165)

4. Se instaló la herramienta cordova-res

   **npm install -g cordova-res**

   **cordova-res android --copy**
5. Después de ejecutar cordova-res, se crearon las siguientes carpetas con los recursos generados
   
   ![image](https://github.com/user-attachments/assets/4bfe30f4-6ffe-4255-b526-a8eae3728adc)
   
6. Para controlar el comportamiento del splash screen se configuro el archivo config.xml:

   ![image](https://github.com/user-attachments/assets/84c931c0-8c1c-4fd5-bdc0-2718ad26e7dc)

   Esto hace que la pantalla de carga se mostrará durante 3 segundos y se ocultará automáticamente.

## Galería de fotos

![image](https://github.com/user-attachments/assets/b4550470-8f66-48b0-bb52-f1b938813ddd)


## Splash screen

![image](https://github.com/user-attachments/assets/34ae16bf-2530-444d-8549-557235a41446)


## Icono Personlizado

![image](https://github.com/user-attachments/assets/1e79871e-6057-403b-bc3f-9bbfcb5ac49d)










