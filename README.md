
# data_analysis
Portafolio de Ejercicios realizados para "Data Analysis with Python Certification" de freecodecamp.org
## Run Locally

Descarga el proyecto

```bash
    git clone https://github.com/Santiago-Figu/data_analysis.git
    cd django-todo_list
```

> [!NOTE]
> Recuerda trabajar en la rama devel

```bash
    git checkout devel
```


Crear el entorno virtual (recomendado)

```bash
    python -m venv venv
```

Activa el entorno virtual (recomendado)

```bash
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate   # Windows
```

> [!NOTE]
> Recuerda actualizar tu pip install (recomendado)

```bash
    python.exe -m pip install --upgradepip
```

Instalar Django y dependencias iniciales

```bash
    pip install 
    numpy
```
> [!NOTE]
> Si lo prefieres puedes usar el archivo requirements.txt

Ejecuta las migraciones iniciales de Django

```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver 0.0.0.0:8000
```

> [!NOTE]
> Es importante crear un usuario en base de datos con las siguientes caracteristicas establecidas en el modelo **User** de la app **users**: 'name', 'lastname', 'username', 'password', 'email', 'cellphone', 'team'

```bash
    jose_admin | jose@algo.com | meoi1234
    admin_test | admin_test@outlook.com | meoi1234
```

Ejecuta el servidor

```bash
    python manage.py runserver 0.0.0.0:8080
```
## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

- **Autor:** [Santiago Figueroa](https://github.com/Santiago-Figu)
- **Correo de contacto:** Sfigu@outlook.com
## Support

Para recibir soporte, contactar por email sfigu@outlook.com.


## Authors

- **Autor:** [Santiago Figueroa](https://github.com/Santiago-Figu)


## Feedback

If you have any feedback, please reach out to us at sfigu@outlook.com


## Documentation

[Curso "Data analysis with python"](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-course)

[freecodecamp Learn](https://www.freecodecamp.org/learn)

[Ejercios](https://github.com/rmotr-curriculum/ds-content-interactive-jupyterlab-tutorial)

