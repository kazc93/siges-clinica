# SIGES Clínica Medi

Sistema web de gestión para la clínica Medi: registro de pacientes, agendamiento de citas e historial clínico en un solo lugar.
Estado: en planificación. Todavía no tiene código; el repositorio contiene la estructura y la documentación.

**Objetivo.** Centralizar la información de pacientes, citas e historial clínico, evitando citas encimadas y protegiendo la confidencialidad del historial.
**Arquitectura.** Aplicación web de tres capas, organizada como un monolito modular en Django (patrón MVT) y desplegada en AWS.
**Tecnologías.** Python y Django, PostgreSQL, Git y GitHub, AWS (EC2, RDS y S3).
**Estructura.** apps/ (autenticacion, pacientes, citas, historial_clinico y administracion), templates/, static/, docs/, config/.
**Ramas y commits.** Rama principal main, protegida. El trabajo se hace en ramas feature/*, fix/*, docs/* y hotfix/*. Los commits usan los prefijos feat, fix, docs, test, refactor y chore.

**Preparar el ambiente (cuando exista el código):**
1. Clonar el repositorio.
2. Crear y activar un entorno virtual de Python.
3. Instalar las librerías con pip install -r requirements.txt.
4. Copiar .env.example como .env y llenar los valores.
5. Ejecutar python manage.py migrate y luego python manage.py runserver.

**Roles.** Product Owner, Scrum Master, dos desarrolladores Django y QA.