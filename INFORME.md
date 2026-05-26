# UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

## Programación Web

### Laboratorio 1: Creación de repositorios y trabajo colaborativo

---

## 1. Datos generales

**Proyecto:** Mashka Box Training Club — Landing page con Bootstrap
**Grupo:** 7
**Repositorio:** https://github.com/wprogramacion2026-svg/landing-page-bootstrap-grupo7
**Fecha de entrega:** 26 de mayo de 2026

### Integrantes

- Dennis Barragán
- David Chiluisa
- Johan Untuña

---

## 2. Descripción del proyecto

Mashka Box Training Club es un sitio web tipo *landing page* para un gimnasio de entrenamiento funcional ubicado en Latacunga, Ecuador. El sitio presenta la marca, los planes de membresía, horarios, galería de instalaciones y un formulario de registro que se conecta a una base de datos MySQL mediante PHP. Para este laboratorio se incorporó **Bootstrap 5.3.3** al proyecto para mejorar la maquetación responsive y aplicar componentes estandarizados.

---

## 3. Distribución del trabajo

| Integrante | Rama | Responsabilidad |
|---|---|---|
| Dennis Barragán | `Denis/navbar-header` | Barra de navegación, encabezado principal, sección hero y botones de acción. |
| David Chiluisa | `David/cards-content` | Tarjetas de servicios/planes, sección central de contenido, distribución de filas y columnas. |
| Johan Untuña | `Johan/footer` | Pie de página con redes sociales, contacto, enlaces de navegación y elaboración del informe. |

---

## 4. Tecnologías utilizadas

- **HTML5** — estructura del documento.
- **CSS3** — estilos personalizados (`css/style.css`).
- **Bootstrap 5.3.3** — sistema de grilla, utilidades y componentes responsive (vía CDN).
- **Bootstrap Icons 1.11.3** — iconografía vectorial (vía CDN).
- **PHP** — script `registrar.php` para el formulario de registro.
- **MySQL** — base de datos `gimnasio_db` (`gimnasio_db.sql`).
- **Git** — control de versiones local.
- **GitHub** — repositorio remoto y colaboración por ramas.

---

## 5. Comandos Git utilizados

```bash
# Clonación del repositorio
git clone https://github.com/wprogramacion2026-svg/landing-page-bootstrap-grupo7.git
cd landing-page-bootstrap-grupo7

# Actualizar main antes de ramificar
git pull origin main

# Crear rama individual (footer)
git checkout -b Johan/footer

# Ciclo de trabajo
git add .
git commit -m "Mensaje descriptivo"

# Subir la rama al remoto
git push -u origin Johan/footer

# Verificación
git branch
git log --oneline
git status
```

---

## 6. Evidencias

> Reemplazar cada marcador `[CAPTURA: ...]` por la imagen correspondiente al momento de entregar el informe.

### 6.1 Repositorio en GitHub con la rama `main`
[CAPTURA: Vista del repositorio en GitHub mostrando la rama main]

### 6.2 Ramas individuales en GitHub
[CAPTURA: Lista de ramas: main, Denis/navbar-header, David/cards-content, Johan/footer]

### 6.3 Historial de commits por integrante

- Dennis Barragán
  [CAPTURA: commits en la rama Denis/navbar-header]

- David Chiluisa
  [CAPTURA: commits en la rama David/cards-content]

- Johan Untuña
  [CAPTURA: commits en la rama Johan/footer]

### 6.4 Sitio web funcionando en el navegador (escritorio)
[CAPTURA: index.html abierto, vista de escritorio con navbar + cards + footer Bootstrap]

### 6.5 Sitio web responsive (vista móvil)
[CAPTURA: DevTools en ancho ~375px mostrando el footer apilado y el menú responsive]

### 6.6 Merge final en `main`
[CAPTURA: git log o vista de GitHub mostrando los merges de las tres ramas en main]

---

## 7. Componentes Bootstrap aplicados al footer

El footer (rama `Johan/footer`) utiliza las siguientes utilidades y componentes de Bootstrap 5.3.3:

- **Sistema de grilla:** `container`, `row`, `col-12`, `col-6`, `col-md-3`, `col-md-5`.
- **Espaciado y layout:** `py-5`, `mt-5`, `mt-4`, `pt-3`, `mb-3`, `gy-4`, `gap-2`.
- **Tipografía y colores:** `bg-dark`, `text-light`, `text-light-emphasis`, `text-warning`, `fw-bold`, `fs-4`, `h6`, `text-uppercase`, `small`.
- **Flexbox utilities:** `d-flex`, `d-inline-flex`, `flex-column`, `flex-md-row`, `justify-content-between`, `justify-content-center`, `justify-content-md-start`, `align-items-center`, `order-1`, `order-md-2`.
- **Componentes:** botones (`btn btn-outline-light btn-sm rounded-circle`) para redes sociales.
- **Bordes y listas:** `border-top`, `border-secondary`, `list-unstyled`, `link-light text-decoration-none`.
- **Iconos:** Bootstrap Icons (`bi bi-facebook`, `bi-instagram`, `bi-whatsapp`, `bi-telephone`, `bi-geo-alt`, `bi-arrow-up-circle`).

---

## 8. Conclusiones

- El uso de ramas individuales permitió que cada integrante avanzara en su sección sin bloquear el trabajo del resto.
- Bootstrap simplificó la maquetación responsive: con un puñado de clases de utilidad se logró un footer de tres columnas en escritorio que se apila correctamente en móviles.
- El flujo `clonar → rama → commits → push → merge a main` quedó interiorizado por los tres integrantes y constituye la base para los siguientes laboratorios.
