# Laravel 9 con Platilla AdminLTE

## Comenzando 馃殌

_Sigue las siguientes instruscciones para clonar este repositorio en tu m谩quina local y poder trabajar desde el principio con la plantilla AdminLTE en Laravel 9._

### Pre-requisitos 馃搵

Para clonar este repositorio, debes tener instalado un servidor Apache, PHP y MSQL (Wamp, Xampp, Mamp o Lamp) y los gerenciadores de dependencias para PHP (Composer) y para NodeJs (Npm).

Antes de comenzar verifica si tienes composer con cualquiera de los siguientes comandos en tu terminal.
```
composer --version 
composer -v
```
Si no lo tienes instalado lo pueden instalar siguiendo la documentaci贸n oficial en:  
https://getcomposer.org/doc/00-intro.md

Verifica tambien la version de NPM en la terminal con
```
npm --version
```
Si no lo tienes instalado lo pueden instalar siguiendo la documentaci贸n oficial en:  
https://www.npmjs.com/get-npm

Verifica las versiones de cada uno de ellos

Versi贸n PHP - 8.0  
Versi贸n Mysql - 5.7.34  
Versi贸n Composer - 2.3.5  
Versi贸n NPM - 8.15.0  

### Instalaci贸n 馃敡

_Sigue las siguientes instrucciones para clonar el repositorio_

_Clone el repositorio_

```
git clone https://github.com/jorgehernandezch/Laravel-9-AdminLTE.git
```

_Instale todas las dependencias del Proyecto con_

```
composer install
```

_Actualize las dependencias de Composer con_

```
composer update
```

_Como el proyecto tiene dependencias en JS instalelas con_

```
npm install
```

_Actualize las dependencias de NPM con_

```
npm update
```

_Copie el Archivo .env.example en un archivo nuevo .env con_

```
cp .env.example .env
```
_Configure la base de datos y las demas variables de entorno en el archivo .env_

_Genere una nueva Key para el protecto con_

```
php artisan key:generate
```

_Corra las migraciones del proyecto con_

```
php artisan migrate
```

_Corra los seeder del proyecto con_

```
php artisan db:seed
```
_Corra el proyecto con_

```
php artisan serve
```

_Si todo est谩 correcto puede acceder al proyecto en la direcci贸n http://localhost:8000_ con el Usuario admin@admin.com - Admin


---
[Jorge Edo. Hern谩ndez](https://github.com/jorgehernandezch)  
_Ingeniero y Desarrollador Web_
