# npm-producer-demo-app

Requieres node.

// Crear package.json -> Con cuestionario
> npm init

// Crear package.json con default values -> Solo autor
> npm init --yes

// Configuracion npm
> npm set init.author.email "wombat@npmjs.com"
> npm set init.author.name "ag_dubs"
> npm set init.license "MIT"

"dependencies": these packages are required by your application in production
"devDependencies": these packages are only needed for development and testing

// campos requeridos de package.json 
{
  "name": "my-awesome-package",
  "version": "1.0.0"
}

There are two ways to install npm packages: locally or globally. You choose which kind of installation to use based on how you want to use the package.

If you want to use it as a command line tool, something like the grunt CLI, then you want to install it globally. On the other hand, if you want to depend on the package from your own module using something like Node's require, then you want to install locally.


// Instalar un npm local
> npm install <package_name>

// Instalar y guardar las dependencias local
> npm install <package_name> --save

// Instalar y guardar en las dependencias de desarrollo local
> npm install <package_name> --save-dev

// Instalar paquete globalmente
> npm install -g <package_name>

// Desinstalar paquete global
npm uninstall -g jshint

// Actualizar los modulos
> npm update

// Listar modulos desactualizados
> npm outdated

// Agregar usuario npm
> npm adduser

// Publicar los paquetes
> npm publish

// Actualizar version npm
> npm version <patch, minor, mayor>



