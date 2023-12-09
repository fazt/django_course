# Comandos Básicos de Django

# Crear un Proyecto Django
# Inicia un nuevo proyecto de Django con el nombre especificado.
django-admin startproject nombre_proyecto

# Crear una Aplicación
# Crea una nueva aplicación dentro del proyecto de Django.
python manage.py startapp nombre_app

# Crear Migraciones
# Genera archivos de migración basados en los cambios en los modelos.
python manage.py makemigrations

# Aplicar Migraciones
# Aplica las migraciones pendientes al esquema de la base de datos.
python manage.py migrate

# Iniciar el Servidor de Desarrollo
# Inicia el servidor web de desarrollo de Django.
python manage.py runserver

# Crear un Superusuario/Administrador
# Crea un superusuario para acceder al panel de administración.
python manage.py createsuperuser

# Ejecutar Tests Unitarios
# Ejecuta los tests unitarios definidos en tu proyecto.
python manage.py test

# Obtener Ayuda
# Muestra una lista de todos los comandos disponibles en Django.
python manage.py help
