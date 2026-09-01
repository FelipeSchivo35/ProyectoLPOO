# CircuitBreaker
Proyecto de la materia LPOO
# Integrantes del Grupo:

Felipe Schivo

# Descripción Corta del Videojuego:

EY-K es un juego de plataformas 2D ambientado en una fábrica automatizada abandonada
. El jugador controla a un pequeño robot de mantenimiento que debe atravesar distintos sectores para llegar al núcleo central y restaurar el sistema
. La experiencia destaca por una mecánica de batería que se drena gradualmente, afectando la velocidad de movimiento y potencia de salto del robot hasta causar su derrota por falta de carga
. A diferencia de otros clásicos, el enfoque está en la evasión de enemigos invulnerables y la precisión para sobrevivir antes de que se agote la energía

# Tecnologías Principales
Lenguaje: Java 21.0.6

Framework: LibGDX 1.13.5

Persistencia de Datos (planeado): MariaDB y MariaDB Connector/J para el registro de usuarios, puntajes y estadísticas de partida

Plataformas de Desarrollo Objetivo: Escritorio.
Herramientas Adicionales: Tiled para el diseño de niveles, Git/GitHub para control de versiones y Scene2D para la interfaz de usuario

[Esta seria la propuesta completa](https://github.com/FelipeSchivo35/ProyectoLPOO/wiki/Propuesta-%E2%80%90-Circuit-Breaker)

# Instrucciones Básicas de Compilación y Ejecución

Para ejecutar el proyecto **CircuitBreaker**, es necesario contar con Java 21 y clonar el repositorio.

## 1. Requisitos

Antes de comenzar, instalar:

* **Java JDK 21**
* **Git**

El proyecto utiliza **LibGDX 1.13.5** y Gradle para la compilación.

## 2. Clonar el repositorio

Abrir una terminal y ejecutar:

```bash
git clone https://github.com/FelipeSchivo35/ProyectoLPOO.git
```

Luego ingresar a la carpeta del proyecto:

```bash
cd ProyectoLPOO
```

## 3. Compilar el proyecto

El proyecto incluye el Gradle Wrapper, por lo que no es necesario instalar Gradle manualmente.

En Windows:

```bash
gradlew.bat build
```

En Linux o macOS:

```bash
./gradlew build
```

## 4. Ejecutar el juego

Para ejecutar la versión de escritorio del juego:

En Windows:

```bash
gradlew.bat lwjgl3:run
```

En Linux o macOS:

```bash
./gradlew lwjgl3:run
```

Esto iniciará el videojuego **EY-K** en una ventana de escritorio.

## 5. Ejecución desde un IDE

También es posible importar el proyecto en un IDE compatible con Gradle, como IntelliJ IDEA.

Una vez importado el proyecto, utilizar la configuración de ejecución correspondiente al módulo `lwjgl3`.


