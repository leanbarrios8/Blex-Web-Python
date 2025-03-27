#Proyecto gestion web y monedas DJango y Python

Descripcion:
Implementación de recursos para creación de usuarios en web Blex

#Requisitos
- Python 3.8 o superior
- pip (gestor de paquetes de Python)
- Virtualenv (opcional pero recomendado)

Pasos:

1. Clona el repositorio:

	Descargar archivo RAR de repositorio en tu ordenador

2. Instala las dependencias:

    	pip install -r requirements.txt
   

3. Realiza las migraciones de la base de datos:

    	python manage.py makemigrations
    	python manage.py migrate

4. Ejecuta el servidor de desarrollo:

    	python manage.py runserver

5. Abre tu navegador y navega a `http://127.0.0.1:8000/`.