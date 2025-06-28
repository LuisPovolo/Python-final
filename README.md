1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

Que es el pip y porque lo actualizamos?
pip (Pip Installs Packages) es una herramienta de línea de comandos que viene incluida con Python y se utiliza para:

Funciones principales:
Instalar paquetes: Descargar e instalar librerías de Python desde el Python Package Index (PyPI)
Desinstalar paquetes: Remover librerías que ya no necesites
Actualizar paquetes: Mantener las librerías actualizadas a sus últimas versiones
Listar paquetes: Ver qué librerías tienes instaladas
Gestionar dependencias: Manejar las relaciones entre diferentes paquetes

es importante actualizar por:
Es muy importante mantener pip actualizado por varias razones clave:

¿Por qué actualizar pip?
1. Corrección de errores y bugs
Las versiones más nuevas solucionan problemas conocidos
Mejoran la estabilidad del sistema de instalación
Evitan fallos durante la instalación de paquetes
2. Mejoras de seguridad
Parches de seguridad críticos
Protección contra vulnerabilidades conocidas
Mejor manejo de certificados SSL/TLS
3. Compatibilidad con paquetes modernos
Algunos paquetes nuevos requieren versiones recientes de pip
Soporte para nuevos formatos de paquetes (como wheels)
Mejor resolución de dependencias
4. Nuevas características
Comandos y opciones mejoradas
Mejor interfaz de usuario
Instalaciones más rápidas y eficientes
5. Mejor manejo de dependencias
Algoritmos mejorados para resolver conflictos
Mejor detección de dependencias circulares
Instalaciones más confiables

