# Django CRUD Básico

Este proyecto es un ejemplo básico de cómo crear un CRUD (Create, Read, Update, Delete) utilizando Django.

## Pasos para Configurar el Proyecto

Sigue estos pasos para configurar y ejecutar el proyecto:

### 1. Clonar el Repositorio

```
git clone <URL_del_repositorio>
cd django-crud-basico
```

### 2. Crear y Activar un Entorno Virtual (Opcional pero Recomendado)

```
python -m venv myenv
source myenv/bin/activate  # En Linux/Mac
myenv\Scripts\activate     # En Windows
```

### 3. Instalar Dependencias

```
pip install -r requirements.txt
```

### 4. Configurar la Base de Datos

- Asegúrate de tener PostgreSQL instalado en tu sistema.
- En el archivo `settings.py`, configura la base de datos en la sección `DATABASES`.

### 5. Aplicar Migraciones

```
python manage.py makemigrations
python manage.py migrate
```

### 6. Ejecutar el Servidor de Desarrollo

```
python manage.py runserver
```

El servidor estará disponible en `http://127.0.0.1:8000/`.

## Funcionalidades del CRUD

- **Crear Nuevo Elemento**: Visita `http://127.0.0.1:8000/new/` para agregar un nuevo elemento.
- **Ver Lista de Elementos**: La lista de elementos estará disponible en `http://127.0.0.1:8000/`.
- **Editar Elemento**: Para editar un elemento, haz clic en el enlace "Editar" junto al elemento en la lista.
- **Eliminar Elemento**: Para eliminar un elemento, haz clic en el enlace "Eliminar" junto al elemento en la lista.

---

