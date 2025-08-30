# Home About Django

Este es un proyecto básico de Django que incluye dos páginas principales: Home y About.

## Estructura del proyecto

```
home_about_django/
├── django_base/         # Configuración principal de Django
├── pages/               # Aplicación con vistas Home y About
├── templates/           # Plantillas HTML (_base, home, about)
├── db.sqlite3           # Base de datos SQLite
├── manage.py            # Script de gestión de Django
├── requirements.txt     # Dependencias del proyecto
```

## Instalación

1. Clona el repositorio o descarga los archivos.
2. Crea un entorno virtual (opcional pero recomendado):
	```powershell
	python -m venv .venv_home
	.venv_home\Scripts\Activate.ps1
	```
3. Instala las dependencias:
	```powershell
	pip install -r requirements.txt
	```

## Uso

1. Ejecuta las migraciones:
	```powershell
	python manage.py migrate
	```
2. Inicia el servidor de desarrollo:
	```powershell
	python manage.py runserver
	```
3. Accede a las páginas en tu navegador:
	- Home: [http://localhost:8000/](http://localhost:8000/)
	- About: [http://localhost:8000/about/](http://localhost:8000/about/)

## Estructura de URLs y vistas

- `pages/urls.py`: Define las rutas para Home y About.
- `pages/views.py`: Contiene las vistas basadas en clase para cada página.
- `templates/`: Contiene las plantillas HTML.

## Autor

Proyecto de ejemplo para curso de Django.
