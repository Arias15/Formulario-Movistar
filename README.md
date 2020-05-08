APP WEB MOVISTAR-FUNCIONAMIENTO

1-Levantar el servidor local con Xampp y puedes crear ahi la base de datos MySql

2-Instalar Laravel
3-Copiar el directorio "movistar" a tu entorno de codigo
4-levantar el servidor con  "php artisan serve"
5-Ingresar a localhost ejm "http://localhost:8000/cliente"
6-Visualizar app movistar

-------------------

create database movis;

create table clientes(
	id integer unsigned primary key auto_increment,
    cod_cliente varchar(100), 
	raz_social varchar(100) not null,
    segmento varchar(100) not null,
    sub_seg varchar(100),
    canal varchar(100),
    region varchar(100),
    departamento varchar(100),
    provincia varchar(100),
    ejec_comercial varchar(100),
    jefe_comercial varchar (100),
    fac_agrupada varchar(100),
    tipo_ciente varchar(100)
);

insertamos los datos importandolos de CLIENTE.csv
