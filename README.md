# ObrasAIR-Django
Sistema de informacion para optimizar la gestion de contratacion en el sector de la construccion


<div align="center">

# ObrasAIR

### Donde el talento y las oportunidades se encuentran

Una bolsa de empleo hecha para conectar empresas con las personas que las van a hacer crecer.

</div>

---

## ¿Qué es ObrasAIR?

ObrasAIR es una plataforma donde las empresas publican sus ofertas laborales y los candidatos encuentran trabajo, se postulan con su hoja de vida y siguen el estado de su proceso, todo en un mismo lugar.

## Características

- **Tres tipos de usuario:** Administrador, Representante de empresa y Candidato.
- **Empresas:** registro de empresas y de sus representantes.
- **Ofertas de empleo:** publicación y gestión de vacantes.
- **Postulaciones:** los candidatos se postulan y ven en qué va su proceso.
- **Hoja de vida:** carga de archivos en PDF, DOC o DOCX.

## Instalación manual

1. Descarga el proyecto como archivo ZIP desde el repositorio y descomprímelo donde prefieras.

2. Abre una terminal dentro de la carpeta del proyecto (la que contiene el archivo `manage.py`).

3. Crea un entorno virtual:

   ```bash
   python -m venv venv
   ```

4. Activa el entorno virtual:

   ```bash
   # Windows
   venv\Scripts\activate

   # Linux / macOS
   source venv/bin/activate
   ```

5. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

6. Aplica las migraciones:

   ```bash
   python manage.py migrate
   ```

7. Crea tu usuario administrador:

   ```bash
   python manage.py createsuperuser
   ```

8. Inicia el servidor:

   ```bash
   python manage.py runserver
   ```




