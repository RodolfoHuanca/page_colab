TechStore - Tienda de Componentes de PC

Landing page moderna para tienda de componentes de computadoras gaming y profesional. Proyecto educativo para aprender Git y GitHub en equipo usando HTMLy CSS para la elaboración del proyecto.

# Equipo de Desarrollo

- Integrante 1(Chambilla Cutipa Adilson Silvano): Header + Hero Section (Presentación principal)
- Integrante 2(Huanca Ramirez Kieberlyn Rodolfo): Productos Section (Categorías y catálogo)
- Integrante 3(Mamani Flores Denis Wilmer): Ofertas + Por qué elegirnos
- Integrante 4(Llanos Mamani Eddy Armando): Contacto + Footer

# Estructura del Proyecto

Page_colab/

│

├── index.html

├── CSS/

│ └── styles.css

└── README.md

\# Página principal

\# Estilos CSS

**Instrucciones de GitHub para cada Integrante**

**Paso 1: Configuración Inicial (Solo el líder del equipo)**

El líder crea el repositorio y estructura inicial:

bash

_\# Crear carpeta del proyecto_

mkdir page_colab

cd page_colab

_\# Inicializar Git_

git init

_\# Crear estructura de carpetas_

mkdir css

_\# Crear archivos base_

_\# (copiar index.html y styles.css base proporcionados)_

_\# Primer commit_

git add .

git commit -m "feat: estructura inicial del proyecto TechStore"

_\# Conectar con GitHub_

git remote add origin \[URL-DEL-REPOSITORIO\] git branch -M main

git push -u origin main

**Paso 2: Cada Integrante Clona el Repositorio**

Todos los integrantes ejecutan:

bash

_\# Clonar el repositorio_

git clone \[<https://github.com/RodolfoHuanca/page_colab.git\>]

cd page_colab

_\# Verificar que todo esté correcto_

git status git log

**Paso 3: Workflow para Cada Integrante**

**INTEGRANTE 1 - Header + Hero Section**

bash

_\# Crear rama para tu sección_

git checkout -b feature/header-hero

_\# COMMIT 1: Agregar estructura HTML_

_\# (copiar código del COMMIT 1 de Integrante 1)_

git add index.html

git commit -m "feat: agregar estructura HTML del header y hero section tecnológico"

_\# COMMIT 2: Estilos del navbar responsive # (agregar CSS del COMMIT 2 a styles.css)_ git add css/styles.css

git commit -m "style: implementar navbar con efectos neón y responsive"

_\# COMMIT 3: Estilos del hero con animaciones # (agregar CSS del COMMIT 3 a styles.css)_

git add css/styles.css

git commit -m "style: agregar hero section con grid animado y efectos visuales"

_\# Subir cambios_

git push origin feature/header-hero

_\# Ir a GitHub y crear Pull Request_

**INTEGRANTE 2 - Productos Section**

bash

_\# Asegurarse de estar actualizado_

git checkout main git pull origin main

_\# Crear tu rama_

git checkout -b feature/productos

_\# COMMIT 1: Estructura de productos_

git add index.html

git commit -m "feat: agregar sección de productos con cards detalladas"

_\# COMMIT 2: Estilos del grid_

git add css/styles.css

git commit -m "style: implementar grid de productos con badges y overlays"

_\# COMMIT 3: Efectos y animaciones_

git add css/styles.css

git commit -m "style: agregar efectos hover y animaciones de entrada a productos"

_\# Subir cambios_

git push origin feature/productos

_\# Crear Pull Request en GitHub_

**INTEGRANTE 3 - Ofertas + Por qué elegirnos**

bash

_\# Actualizar main_

git checkout main git pull origin main

_\# Crear rama_

git checkout -b feature/ofertas-beneficios

_\# COMMIT 1: HTML de ofertas y beneficios_

git add index.html

git commit -m "feat: agregar secciones de ofertas relámpago y beneficios"

_\# COMMIT 2: Estilos de ofertas_

git add css/styles.css

git commit -m "style: implementar diseño de ofertas con temporizadores"

_\# COMMIT 3: Estilos de beneficios_

git add css/styles.css

git commit -m "style: agregar cards de beneficios con efectos hover 3D"

_\# Subir_

git push origin feature/ofertas-beneficios

_\# Crear Pull Request en GitHub_

**INTEGRANTE 4 - Contacto + Footer**

bash

_\# Actualizar_

git checkout main git pull origin main

_\# Crear rama_

git checkout -b feature/contacto-footer

_\# COMMIT 1: Estructura HTML_

git add index.html

git commit -m "feat: agregar formulario de contacto y footer completo"

_\# COMMIT 2: Estilos del formulario_

git add css/styles.css

git commit -m "style: implementar diseño del formulario de contacto con validación visual"

_\# COMMIT 3: Estilos del footer_

git add css/styles.css

git commit -m "style: agregar footer con gradientes y efectos en redes sociales"

_\# Subir_

git push origin feature/contacto-footer

_\# Crear Pull Request en GitHub_

# Proceso de Review y Merge

- Después de hacer , ir a GitHub

push

- Click en **"Pull Requests"** → **"New Pull Request"**
- Seleccionar tu rama y agregar descripción
- Otro integrante revisa el código
- Click en **"Merge Pull Request"**
- El siguiente integrante debe hacer antes de empezar

git pull origin main

# Convenciones de Commits

Usar prefijos descriptivos:

\- Nueva funcionalidad o sección

feat:

\- Cambios de estilos/CSS

style:

\- Corrección de errores

fix:

\- Cambios en documentación

docs:

\- Mejoras de código

refactor:

**Ejemplos:**

feat: agregar sección de productos destacados style: implementar efectos neón en el navbar fix: corregir responsive del hero en mobile