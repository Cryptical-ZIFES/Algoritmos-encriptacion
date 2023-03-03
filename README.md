# Diseño y análisis de un algoritmo criptográfico basado en hashes - ZIFES

En la actualidad, la criptografía se hace presente en la mayoría de las actividades realizadas en un dispositivo electrónico. Una de sus mayores contribuciones se puede observar en el desarrollo de protocolos avanzados que proporcionan servicios criptográficos de alta seguridad y eficacia desde los aspectos de la vida privada y comercial.

Este repositorio es una clara muestra de ello. En el presente trabajo se maneja un sistema de encriptado y desencriptado adaptado para cualquier tipo de archivos para asegurar los requisitos de seguridad en las comunicaciones, cuya complejidad computacional sea idónea para proteger archivos ante presuntos ataques criptográficos, así como mermar su vulnerabilidad frente a futuros sistemas computacionales de amplia capacidad.

## Requisitos del sistema:

Es importante leer los requisitos mínimos y recomendados del sistema, ya que de lo contrarío, podría presentar errores en la instalación o en la ejecución del programa.
```
- Sistema Operativo Windows 10,11 (x64)
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

1. Descargar este repositorio por el método de clonar `Git (HTTPS)` o descargar como `.ZIP` para después extraerlo en la ubicación deseada.

En caso de tener instalado Visual Studio, saltar los siguientes pasos:

        - Descargar el instalador del programa [Visual Studio Community 2022](https://visualstudio.microsoft.com/es/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&cid=2030&passive=false)
        
        - Abrir el instalador, ir al apartado de Componentes individuales y buscar/seleccionar los siguientes archivos: 
        -
        -
        -
        -

2. 
3.
4.
5.
6.
7.
8.
9.

### ¿Cómo ejecutarlo?


### Ejemplos del Algoritmo de Encriptado de un archivo:
Consola CMD o Windows PowerShell:
```rust
C:\Algoritmos-encriptacion\Encriptado>cargo b
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
Introduce la contrasena de tu archivo:
```
Se coloca manualmente la contraseña para encriptar y más tarde desencriptar.

NOTA: Es fundamental guardar esta contraseña, ya que en caso de olvidarla no se podrá recuperar y desencriptar el archivo :( .

```rust
Codificación exitosa tiempo de codificación: * segundos
```
Aparece el archivo encriptado, la manera de diferenciarlos es por medio de la etiqueta `Crzipfes_` al principio del nombre del archivo.

### Ejemplos del Algoritmo de Desencriptado de un archivo:
Consola CMD o Windows PowerShell:
```rust
C:\Algoritmos-encriptacion\Desencriptado> cargo b
    Finished dev [unoptimized + debuginfo] target(s) in * s

C:\Algoritmos-encriptacion\Desencriptado> cargo run
    Finished dev [unoptimized + debuginfo] target(s) in * s
     Running `target\debug\decodificado.exe`
     
Hola usuario que archivo quieres desencriptar:
```
Se coloca manualmente el nombre del archivo con su respectiva extensión.

NOTA: El archivo tiene que estar adentro de la carpeta de Desencriptado.
```rust
Introduce tu contasena:
```
Se coloca manualmente la contraseña para desencriptar.
```rust
Desencriptado exitoso tiempo de desencriptado: * segundos
```
Aparece el archivo desencriptado, la manera de diferenciarlos es por medio de la etiqueta Crzipfes_ , ya que el nuevo archivo regresa a su nombre original.




```

## Built With


## License



## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
