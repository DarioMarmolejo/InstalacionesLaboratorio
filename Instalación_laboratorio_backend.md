# Instalación de laboratorio Dev.

## Descarga de software:

- Visual studio Code.
- Sublime text.
- Git y git bash.
- Dbeaver.
- Docker o Docker Desktop.
- JDK 8,11 o 17.
- Maven.

## Instalación de software (unicamente si no tienen .exe para windows):

### - Docker:
	Ejecutar el .exe de instalacion.
	Reiniciar
	Descargar el kernel einstalar el .msi
	Abrir PowerShell y ejecute este comando para establecer WSL 2 como versión predeterminada al instalar una nueva distribución de Linux:
	wsl --set-default-version 2
	Reiniciar

### - Instalación de JDK java
	Descargar de https://adoptium.net/es/temurin/releases/?version=17
	Descomprimir en alguna carpeta de facil acceso o crear una en el disco c:
	Abrir las variables de entorno(buscar variables de entorno en el buscador de windows)
	Seleccionar el boton de "Variables de entorno"
	En la segunda sección buscar la variable "path" y presionar en editar.
	Seleccionar el boton de "Nueva" y escribir la direccion donde se encuentra la carpeta descomprimida del jdk hasta la carpeta bin que se encuentra dentro de la misma.
	Guardar y verificar

	Abrir una terminal y escribir el comando"java -version"

### - Instalacion de Maven
	(El mismo proceso que con la instalacion de un JDK)

## Extenciones de visual studi code para una api de spring:

- Java extension pack.
- Spring extension pack.
- Lombok


