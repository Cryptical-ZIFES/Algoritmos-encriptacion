# Diseño y análisis de un algoritmo criptográfico basado en hashes - ZIFES

En la actualidad, la criptografía se hace presente en la mayoría de las actividades realizadas en un dispositivo electrónico. Una de sus mayores contribuciones se puede observar en el desarrollo de protocolos avanzados que proporcionan servicios criptográficos de alta seguridad y eficacia desde los aspectos de la vida privada y comercial.

Este repositorio es una clara muestra de ello. En el presente trabajo se maneja un sistema de encriptado y desencriptado adaptado para cualquier tipo de archivos para asegurar los requisitos de seguridad en las comunicaciones, cuya complejidad computacional sea idónea para proteger archivos ante presuntos ataques criptográficos, así como mermar su vulnerabilidad frente a futuros sistemas computacionales de amplia capacidad.

## Requisitos del sistema:

Es importante leer los requisitos mínimos completos y recomendados del sistema, ya que de lo contrarío, podría presentar errores en la instalación o en la ejecución del programa.

Requisitos mínimos:
```
- Sistema Operativo Windows 10 o 11 (x64)
- RAM: 4GB+ (gigabytes)
- Espacio libre en el disco duro: Minimo 10 GB
```
## Instalación:

Estas instrucciones te ayudarán a obtener la copia del repositorio para su correcta instalación.

1. Descargar este repositorio por el método de clonar `Git (HTTPS)` o descargar como `.ZIP` para después extraerlo en la ubicación deseada.

En caso de tener instalado Visual Studio, saltar los siguientes pasos:

   - Descargar el instalador del programa [Visual Studio Community](https://visualstudio.microsoft.com/es/thank-you-downloading-visual-studio/?sku=Community&channel=Release&version=VS2022&source=VSLandingPage&cid=2030&passive=false).
        
   - Abrir el instalador, en Cargas de trabajo, localizar `Desarrollo para el escritorio con C++`, después ir al apartado de Componentes individuales y buscar el siguiente archivo: `Windows 10 SDK` `Windows 11 SDK` (dependiendo del sistema operativo). Aproximadamente 9.89 GB.

2. Descargar e instalar el archivo [rustup installer](https://rustup.rs/).
3. Abrir Visual Studio y descargar la extensión `rust-analyzer`.
4. Abrir la consola y checar la versión de Rust con el comando: `rustc --version` (En caso de que este desactualizado, con el comando `rustup update` puedes actualizarla).
5. Reiniciar la computadora para guardar los cambios.
6. Abrir el repositorio o carpeta del proyecto en Visual Studio, verificando si no hay un error a la hora del inicio automático del plug-in. En el caso de que aparezca el error `Error: Linker ‘Link.exe’ Not Found” in Rust` se deberá regresar al paso 1.2, ya sea para comprobar/reparar los archivos dañados o instalar los faltantes.

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
