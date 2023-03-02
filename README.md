# My Awesome App

¡Bienvenido a mi aplicación! Esta es una aplicación en donde se pueden administrar usuarios a través de un CRUD (Create, Read, Update and Delete). Esta aplicación fue creada con Vite y React.

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:5174](http://localhost:5174) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the dist folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!


## Tecnologías
▪	Vite
▪	React
▪	Axios
▪	react-hook-form

## Instalación
Clona este repositorio en tu computadora local.
Abre una terminal y navega a la carpeta del proyecto.
Ejecuta el siguiente comando para instalar las dependencias:

### `npm install`

Una vez que se hayan instalado las dependencias, puedes correr la aplicación con el siguiente comando:

### `npm run dev`


## Contribuir
Si quieres contribuir a este proyecto, por favor sigue los siguientes pasos:

Haz un fork de este repositorio.
Crea una nueva rama con tus cambios:

### `git checkout -b my-feature`

Haz tus cambios y haz un commit:

### `git commit -m "mi mensaje de commit"`

Haz un push a tu rama:

### `git push origin my-feature`

Abre un Pull Request y describe tus cambios.

## ¡Gracias por contribuir!

<br>

## Algunas Características de mi App 

Consumo de API: https://users-crud.academlo.tech/swagger/, se utiliza para consultar, crear, eliminar y actualizar dichos usuarios.

Creación de un componente llamado “UserCard” donde se listan todos los usuarios, mostrando su nombre, apellido, email y fecha de nacimiento. Adicional contiene dos bonotes, uno para eliminar, el cuál ejecutará un “delete” en la API para eliminar el usuario seleccionado. Y uno para editar, el cual pondrá toda la información del usuario seleccionado en “FormUsers”. 

Creación de un componente llamado “FormUsers”, este es un formulario en donde se ubican los inputs para llenar los siguientes datos: nombre (“first name”), apellido (“last name”), email (“email”), contraseña(“password”), fecha de nacimiento (“birthday”).

Al hacer submit, se realiza una petición “post” para crear el nuevo usuario. En caso de que haya algún usuario para editar, la petición sería de tipo “put” para editarlo.


<br>

## ¿Quieres ver mi app despleagada?
Visita <a href="https://crud-users-app-ct.netlify.app/" target="_blank">Crud Users</a>.