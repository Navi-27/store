# Practica Basica de MVC con PHP 
Practica basica MVC usando PHP (sin framework) basado en el tutorial de [JuanMaRuizH] (https://github.com/JuanMaRuizH/simple-mvc-php-example)
Con ayuda del ingeniero [Richard maurello] (https://www.linkedin.com/in/richardmaurellor?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BLDvwxG2YT9O4vCS9FyK%2B3A%3D%3D)


## Configuración de la base de datos
Primero crearemos una tabla para usarla de base.

La tabla que se consulta puede crearse con el script:

```
CREATE TABLE `products` (
  `cod` int(11) NOT NULL,
  `short_name` varchar(20) NOT NULL,
  `pvp` decimal(5,2) NOT NULL,
  `nombre` varchar(100) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

Para añadir productos a la tabla ```products``` puedes utilizar el script:

```
INSERT INTO `products` (`cod`, `short_name`, `pvp`, `nombre`) VALUES
(1, 'Monitor', '400.00', 'Dell 21 full HD'),
(2, 'Teclado', '9.99', 'Teclado inalámbrico Logitech'),
(3, 'iPad Pro', '900.00', 'Apple iPad Pro 9');
```
