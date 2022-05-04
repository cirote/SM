# SM
Instrucciones para instalación de proyectos en la SM

## Instalar Laravel

```
git clone git-proyecto .
```

## Instalar paquetes

```
composer install
```

## Actualizar .env

```
cp .env.example .env
```

Actualizar datos de la base, nombre de la aplicación y coneccion al sistema de logueo. 

## Generar clave
```
php artisan key:generate
```

## Realizar migracion
```
php artisan migrate
```

## Actualizar directorio en el panel


## Actualiar url rewrite en el panel

## Modificar permisos de ficheros
```
chmod 777 storage/ -R && chmod 777 bootstrap/ -R
```
