Task Manager

Este es un sistema de gestión de tareas desarrollado con Django.

Requisitos previos

Antes de ejecutar este proyecto, asegúrate de tener instalado:

Python 3.10+

Django 5.1+

Un entorno virtual configurado (opcional pero recomendado)

Instalación

Clona el repositorio

git clone https://github.com/tu_usuario/taskmanager.git
cd taskmanager

Crea y activa un entorno virtual (opcional pero recomendado)

python -m venv venv
source venv/bin/activate  # En Windows usa: venv\Scripts\activate

Instala las dependencias

pip install -r requirements.txt

Configura la base de datos

python manage.py migrate

Crea un superusuario (opcional, para acceder al panel de administración)

python manage.py createsuperuser

Ejecuta el servidor

python manage.py runserver

Accede a la aplicación

Portal de usuario: http://127.0.0.1:8000/tasks/

Panel de administración: http://127.0.0.1:8000/admin/

Configuración adicional

Si necesitas cambiar la configuración de la base de datos o autenticación, edita el archivo settings.py.

Autenticación

Registro: /tasks/register/

Login: /tasks/login/

Logout: /tasks/logout/

Funcionalidades

Crear, editar y eliminar tareas

Marcar tareas como completadas

Sistema de autenticación con Django Authentication

Autor

Erick Rosero

Contacto: correo@ejemplo.com

