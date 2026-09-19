# Hola Mundo

<div align="center">

<img src="https://img.shields.io/badge/Python-3.12%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.12+" />
<img src="https://img.shields.io/badge/Django-6.1.1-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django 6.1.1" />
<img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />

</div>

Una pequeña aplicación web desarrollada con Django para mostrar una página inicial tipo "Hola, Mundo!" con una estructura sencilla y lista para crecer.

## ✨ Características

- Proyecto base con Django 6.1.1
- Estructura modular con la app `pages`
- Plantilla inicial para la vista principal
- Base de datos SQLite por defecto
- Preparado para ampliarse con nuevas vistas, modelos y formularios

## 🧩 Estructura del proyecto

```text
hola-mundo/
├── django_base/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── pages/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates/
│   └── home.html
├── db.sqlite3
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 Requisitos

- Python 3.10 o superior
- Pip
- Entorno virtual recomendado

## ⚙️ Instalación

1. Clona este repositorio:

```bash
git clone <url-del-repositorio>
cd hola-mundo
```

2. Crea y activa un entorno virtual:

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta las migraciones:

```bash
python manage.py migrate
```

5. Inicia el servidor de desarrollo:

```bash
python manage.py runserver
```

Abre tu navegador en:

```text
http://127.0.0.1:8000/
```

## 🌐 Rutas principales

- Página principal: `/`
- Panel de administración: `/admin/`

## 🛠️ Comandos útiles

```bash
python manage.py createsuperuser
python manage.py makemigrations
python manage.py migrate
python manage.py test
```

## 📌 Nota

Este proyecto es una base ideal para comenzar con Django y añadir nuevas funcionalidades como autenticación, CRUD, formularios o una landing page más avanzada.

---

<div align="center">

Hecho con ❤️ y Django.

</div>
