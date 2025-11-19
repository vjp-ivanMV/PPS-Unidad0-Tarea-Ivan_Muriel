# Introducción a la Tarea

Bienvenido a la documentación de esta actividad. El objetivo principal de este proyecto es registrar y explicar todos los pasos técnicos involucrados en la configuración de un entorno de desarrollo y despliegue completo.

Este sitio, generado estáticamente mediante **MkDocs**, sirve como evidencia y guía del proceso, abarcando desde la gestión del código fuente hasta su automatización y despliegue en entornos de contenedores y nube.

---

## 📚 Índice de Contenidos

A continuación encontrarás los módulos que componen la documentación, ordenados cronológicamente según el flujo de trabajo realizado:

### 1. [Gestión de Versiones con Git](git.md)

Detalle de la configuración inicial del entorno, creación del repositorio, gestión de claves SSH y operaciones básicas de control de versiones.

### 2. [Automatización con GitHub Actions](gitActions.md)

Explicación de la *pipeline* de Integración Continua (CI). Se documenta cómo se ha configurado el flujo de trabajo (`workflow`) para que construya automáticamente el sitio web ante cada actualización del código.

### 3. [Publicación en GitHub Pages](gitPages.md)

Descripción del proceso de Despliegue Continuo (CD). Detalla cómo se ha configurado el repositorio para alojar y servir la documentación estática generada previamente por las Actions.

### 4. [Despliegue Local con Docker](docker.md)

Guía sobre la creación de un contenedor **NGINX** utilizando volúmenes (*bind mounts*). Este apartado demuestra cómo servir la documentación en un entorno local aislado mediante Docker.

### 5. [Conclusiones](conclusiones.md)

Reflexión personal sobre los desafíos encontrados, las competencias adquiridas y la importancia de la automatización en el desarrollo de software moderno.
