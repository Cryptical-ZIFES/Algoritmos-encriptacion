# Diseño y análisis de un algoritmo criptográfico basado en hashes - ZIFES

En la actualidad, la criptografía se hace presente en la mayoría de las actividades realizadas en un dispositivo electrónico. Una de sus mayores contribuciones se puede observar en el desarrollo de protocolos avanzados que proporcionan servicios criptográficos de alta seguridad y eficacia desde los aspectos de la vida privada y comercial.
Este repositorio es una clara muestra de ello. En el presente trabajo se maneja un sistema de encriptado y desencriptado adaptado para cualquier tipo de archivos para asegurar los requisitos de seguridad en las comunicaciones, cuya complejidad computacional sea idónea para proteger archivos ante presuntos ataques criptográficos, así como mermar su vulnerabilidad frente a futuros sistemas computacionales de amplia capacidad.

## Requisitos del sistema:

Es importante leer los requisitos mínimos y recomendados del sistema, ya que de lo contrarío, podría presentar errores en la instalación o en la ejecución del programa.
```
- Sistema Operativo Windows 10 (x64)
- RAM: 4+ gigabytes (GB)
- Espacio en disco duro: 
        1. 0.0877 GB (Algoritmos de encriptado)
        2. 1 GB (Visual Studio Code 2022)
        3. 0.00953 GB (Instalador de Rust) + 0.2/0.3 GB (Rust)
        4. 2.38 GB (Windows 10 SDK)
        5. 5 GB (C++ build tools)
        Total: 8.7677 GB sin utilizar mínimo
```
## Instalación:

Estas instrucciones te ayudarán a obtener la copia del repositorio y para su correcta instalación.

1. 
2.
3.
4.
5.
6.
7.
8.
9.


### Ejemplos del Algoritmo de Encriptado de un archivo:
Consola:
```rust
C:\Algoritmos-encriptacion\Encriptado>`cargo b`
   Compiling codificado_1 v0.1.0 (C:\Algoritmos-encriptacion\Encriptado)
    Finished dev [unoptimized + debuginfo] target(s) in *s
    
C:\Algoritmos-encriptacion\Encriptado>cargo run
        Finished dev [unoptimized + debuginfo] target(s) in *s
             Running `target\debug\codificado_1.exe`
             
Hola usuario introduce el archivo que deseas codificar:
```
Se coloca manualmente el nombre del archivo con su respectiva extensión.

NOTA: El archivo tiene que estar adentro de la carpeta de Encriptado.
```rust
Codificación exitosa tiempo de codificación: * segundos
```
Aparece el archivo encriptado, la manera de diferenciarlos es por medio de la etiqueta `Crzipfes_` al principio del nombre del archivo.
### Ejemplos del Algoritmo de Desencriptado de un archivo:

```rust
C:\Algoritmos-encriptacion\Desencriptado>cargo b
   Compiling codificado_1 v0.1.0 (C:\Algoritmos-encriptacion\Desencriptado)
    Finished dev [unoptimized + debuginfo] target(s) in *s
    
C:\Algoritmos-encriptacion\Desencriptado>cargo run
        Finished dev [unoptimized + debuginfo] target(s) in *s
             Running `target\debug\codificado_1.exe`
Hola usuario introduce el archivo que deseas codificar:
```
Se coloca manualmente el nombre del archivo con su respectiva extensión
NOTA: El archivo tiene que estar adentro de la carpeta de Encriptado.

```rust
Codificación exitosa tiempo de codificación: * segundos
```


## ¿Cómo ejecutarlo?


```

## Built With


## License



## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
