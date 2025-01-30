# TaskMaster 

## La herramienta que no sabias que necesitabas, Gestiona y Crea tareas de forma clara y precisa




1. [Características](#Caracteristicas)
2. [Comandos](#Comandos)
   1. [Tarea individual](#Individual)
   2. [Tarea Grupal](#Grupal)
3. [¿Cómo obtenerlo?](#Obtener)
4. [Licencia](#Licencia)

        bash:
            git clone https://github.com/delegator/taskmaster.git 
      

# Caracteristicas
- **Crear tareas individuales o grupales:** Permite crear tareas para ti mismo o asignar tareas a un equipo.
- **Asignar tareas a miembros del equipo:** Asigna tareas específicas a los miembros del equipo y establece fechas de vencimiento.
- **Gestionar el progreso de las tareas:** Con vistas intuitivas, podrás ver en qué estado están las tareas y realizar un seguimiento del progreso.
- **Compartir información en tiempo real:** Gracias a la sincronización en la nube, todos los cambios se actualizan instantáneamente para todos los usuarios.

---
# Comandos

Para crear una tarea, usa el siguiente comando:

### Individual
```bash
taskmaster create:

    --title "Diseñar la interfaz de usuario" 
    --description "Crear un diseño intuitivo para la interfaz de usuario ." 
    --due "2025-02-10" 
    --priority "alta" 

```

### Grupal

Si deseas crear una tarea para tu equipo, usa el siguiente comando:

```bash
taskmaster create:

    --title "Desarrollar la funcionalidad de notificaciones" 
    --description "Crear una funcionalidad para enviar notificaciones a los usuarios cuando se les asignen nuevas tareas." 
    --due "2025-03-01" 
    --priority "alta" 
    --team "Desarrollo, Marketing, Soporte" 
```

## ¿Cómo Instalarlo?

Para obtener y ejecutar TaskMaster en tu entorno local, sigue estos pasos:

### 1. Clona el repositorio desde GitHub:

Abre una terminal y ejecuta el siguiente comando para clonar el repositorio en tu máquina local:

```bash
git clone https://github.com/tu-usuario/taskmaster.git

```

### 2. Crea un entorno virtual y actívalo:
Después de clonar el repositorio, crea un entorno virtual para aislar las dependencias del proyecto:

```bash
python -m venv env
```

### 3 activa el entorno virtual. Dependiendo de tu sistema operativo, utiliza uno de los siguientes comandos:

En macOS/Linux:
 ```bash
source daw/binban/activate
```

En Windows:
 ```bash
binban\Scripts\activate
 ```

### 4. Instala las dependencias necesarias desde requirements.txt:
Con el entorno virtual activado, instala todas las dependencias necesarias ejecutando el siguiente comando:

```bash
pip install -r requir.txt
```


## Licencia

Este proyecto está bajo la **Licencia TEJON**. Puedes ver los detalles completos de la licencia a continuación.

---

**TEJON License**

**Copyright (c) 2025 DELEGATOR**

Se concede permiso, de forma gratuita, a cualquier persona que obtenga una copia de este software y de los archivos de documentación asociados (el "Software"), para **utilizar el Software sin restricciones**, incluyendo, pero no limitándose a, los derechos para usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender copias del Software, y para permitir a las personas a quienes se les proporcione el Software hacerlo, sujeto a las siguientes condiciones:

- El **aviso de derechos de autor** y este **permiso** se incluirán en todas las copias o partes sustanciales del Software.

**EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO**, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITÁNDOSE A LAS GARANTÍAS DE COMERCIABILIDAD, APTITUD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES O TITULARES DEL DERECHO DE AUTOR SERÁN RESPONSABLES POR CUALQUIER RECLAMO, DAÑO O OTRA RESPONSABILIDAD, YA SEA EN UNA **ACCION DE CONTRATO**, **AGRAVIO** O DE OTRO TIPO, QUE SURJA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO O CUALQUIER OTRA ACCIÓN EN EL SOFTWARE.

---

# Proyecto

## Tabla de Dependencias

| Dependencia         | Versión | Descripción                                       |
|--------------------|---------|-------------------------------------------------|
| Django            | 4.2.0   | Framework principal para el desarrollo web.    |
| djangorestframework | 3.14.0  | Biblioteca para crear APIs RESTful con Django. |
| django-filter     | 23.1    | Filtros avanzados para consultas en APIs REST. |
| gunicorn         | 20.1.0  | Servidor WSGI para desplegar aplicaciones Django. |
| psycopg2         | 2.9.6   | Conector de base de datos para PostgreSQL.     |
| Pillow           | 10.0.0  | Biblioteca para el manejo de imágenes en Python. |
| whitenoise       | 6.0.0   | Gestión de archivos estáticos para producción. |
| pytest           | 7.4.2   | Herramienta para realizar pruebas automatizadas. |
| pytest-django    | 4.5.2   | Complemento de pytest para proyectos Django.  |
| celery           | 5.3.4   | Gestión de tareas en segundo plano (background). |
| redis            | 5.0     | Backend para el manejo de tareas de Celery. |

---

## Enlaces
- [Repositorio Cosmos](https://github.com/DLEGATOR/CALCULADORA.git)
- [Tejon](https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Badger-badger.jpg/1200px-Badger-badger.jpg)


## Notas

**Trabajo realizado por delegator**

---


