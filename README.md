# Introducción a Docker y Ejecución de MariaDB en un Contenedor

## ¿Qué es Docker?

Docker es una plataforma que permite desarrollar, enviar y ejecutar aplicaciones dentro de contenedores. Un contenedor es una unidad estándar de software que empaqueta el código y todas sus dependencias, de manera que la aplicación se ejecute de manera rápida y confiable en cualquier entorno computacional.

Los contenedores permiten a los desarrolladores concentrarse en la programación, sin tener que preocuparse por el sistema operativo o la configuración del entorno. Docker hace que sea fácil mover aplicaciones entre entornos de desarrollo, prueba y producción.

### Beneficios de Docker:
- **Portabilidad**: Docker permite ejecutar aplicaciones de manera consistente en diferentes entornos, desde la máquina de desarrollo hasta el servidor de producción.
- **Aislamiento**: Cada contenedor se ejecuta de manera aislada, lo que evita conflictos entre aplicaciones.
- **Eficiencia**: Docker usa menos recursos que las máquinas virtuales tradicionales.

## Instalación de Docker en Windows

Para ejecutar Docker en Windows, sigue estos pasos:

### 1. Descargar Docker Desktop
Visita la página oficial de Docker para Windows y descarga el instalador:
- [Docker Desktop for Windows](https://www.docker.com/products/docker-desktop)

### 2. Instalar Docker Desktop
- Ejecuta el archivo descargado y sigue las instrucciones del instalador.
- Asegúrate de habilitar la opción "Enable WSL 2" (Windows Subsystem for Linux) durante la instalación si no lo tienes ya configurado.
- Docker requerirá que reinicies tu sistema después de la instalación.

### 3. Verificar la Instalación
Una vez instalado Docker, abre una terminal (PowerShell o CMD) y ejecuta el siguiente comando para verificar que Docker está instalado y funcionando correctamente:

```bash
docker --version
