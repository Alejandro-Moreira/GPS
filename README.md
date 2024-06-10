# GPS
Este proyecto es una aplicación Ionic que rastrea la geolocalización del usuario y almacena los datos en Firestore Database. También está alojado en Firebase Hosting.

### Requisitos Previos
Node.js y npm
Ionic 
Firebase 
Un proyecto Firebase
### Pasos para Crear la Aplicación
Configurar el Proyecto Ionic
Crear un nuevo proyecto Ionic
* ionic start geolocation-app blank --type=angular
* cd geolocation-app
![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/29d982f0-da76-4acd-970e-6c1a9b2bfdc4)

Agregar los plugins necesarios
* npm install @ionic-native/core @ionic-native/geolocation @ionic-native/native-geocoder
* npm install @angular/fire firebase
* ionic cap sync
![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/4f628e09-b311-4078-b78d-2368e966cb5b)

Configurar Firebase
Iniciar sesión en Firebase 
* firebase login
Inicializar Firebase 
* firebase init
* Elige Firestore para la base de datos.
* Elige Hosting para el despliegue.
* Selecciona tu proyecto Firebase.
* Elige la ubicación predeterminada para Firestore.
Configurar Firestore y el Entorno
Agregar la configuración de Firebase a los archivos de entorno
![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/52a43abb-0ed5-43e9-8862-0db409648e24)

<br>
![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/ac29b45d-bcce-4dbe-8c58-71896fbaac72)

Compilar y Desplegar
* ionic build
* firebase deploy

![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/4fb2ece8-6881-4be7-be66-80e432a35c9b)
<br>

![image](https://github.com/Alejandro-Moreira/GPS/assets/117743484/38b16a6e-5b9b-463a-9f5b-d912a92676c3)
