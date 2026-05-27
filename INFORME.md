# Informe Laboratorio 1 - Segundo Parcial
## Creación de repositorios y trabajo colaborativo con Bootstrap

**Asignatura:** Programación Web
**Grupo:** Grupo07
**Proyecto:** Mashka Box - Training Club (Landing Page)
**Fecha de entrega:** 2026-05-26

---

## 1. Datos del grupo

| Integrante | Rol / Sección asignada | Rama de trabajo |
|---|---|---|
| Denis Barragán | Navbar, encabezado (hero) y sección principal | `Denis/navbar-header` |
| David Chiluisa | Tarjetas, contenido central, galería y planes | `David/cards-content` |
| Johan Untuña | Formulario de contacto y pie de página (footer) | `Johan/footer` |

---

## 2. Enlace del repositorio

**Repositorio GitHub:**
https://github.com/wprogramacion2026-svg/landing-page-bootstrap-grupo7

**Comando de clonación:**
```bash
git clone https://github.com/wprogramacion2026-svg/landing-page-bootstrap-grupo7.git
```

---

## 3. Tecnologías utilizadas

- HTML5
- Bootstrap 5.3.3 (CDN)
- Bootstrap Icons 1.11.3 (CDN)
- Git
- GitHub
- Visual Studio Code

**Nota técnica:** Todos los estilos del proyecto se aplicaron exclusivamente con clases de Bootstrap. La carpeta `css/` se mantuvo vacía: no se utilizó CSS local.

---

## 4. Descripción del sitio web

Mashka Box es una landing page para un gimnasio de entrenamiento funcional ubicado en Latacunga, Ecuador. El sitio presenta:

- Barra de navegación responsive con menú colapsable (`navbar-expand-lg`, `navbar-toggler`).
- Sección hero con badge, llamadas a la acción y estadísticas.
- Sección "Nosotros" con tarjetas de valores (comunidad, disciplina, resultados).
- Galería de imágenes con grid responsive de Bootstrap.
- Tarjetas (`card`) de servicios: Musculación, Funcional y Cardio HIIT.
- Sección de beneficios con íconos de Bootstrap Icons.
- Planes de membresía en cinco columnas con plan destacado.
- Tabla comparativa (`table table-dark`) con filas resaltadas.
- Bloque de horarios con `border-start border-warning`.
- Carrusel multimedia (`carousel slide`).
- Sección WhatsApp con `alert alert-success`.
- Sección de ubicación con `list-group` y mapa embebido (`ratio ratio-4x3`).
- Formulario de contacto con `form-control`, `form-select` y validaciones HTML5.
- Footer con tres columnas, redes sociales y línea inferior.
- Botón flotante de WhatsApp (`position-fixed`).

---

## 5. Distribución del trabajo

| Sección del proyecto | Responsable | Componentes Bootstrap utilizados |
|---|---|---|
| Navbar | Denis | `navbar`, `navbar-expand-lg`, `navbar-toggler`, `collapse`, `nav-link`, `btn btn-warning` |
| Hero / Encabezado | Denis | `container`, `display-1`, `badge`, `btn btn-lg`, `row`, `col-md-3` |
| Sección Nosotros | David | `card`, `row`, `col-lg-6`, `img-fluid rounded-4` |
| Galería | David | `row g-3`, `col-md-6`, `rounded-3` |
| Tarjetas Servicios | David | `card h-100`, `card-img-top`, `card-body`, `btn-warning` |
| Beneficios | David | `card`, `row g-4`, `bi bi-*` |
| Planes y Tabla | David | `card`, `badge`, `table table-dark`, `table-hover` |
| Horarios | David | `card border-start border-warning border-4`, `badge` |
| Carrusel Multimedia | David | `carousel slide`, `carousel-inner`, `carousel-control` |
| Sección WhatsApp | Johan | `alert alert-success`, `btn btn-success`, `row g-5` |
| Ubicación | Johan | `list-group list-group-flush`, `ratio ratio-4x3`, `iframe` |
| Formulario contacto | Johan | `form-control form-control-lg`, `form-select`, `form-label`, `card shadow-lg` |
| Footer | Johan | `bg-black`, `row gy-4`, `btn-outline-light rounded-circle`, `link-light` |

---

## 6. Resumen del flujo Git aplicado

1. **Creación del repositorio remoto** en GitHub con el nombre `landing-page-bootstrap-grupo7`.
2. **Inicialización local** con `git init`, primer `git add .` y commit inicial.
3. **Conexión con remoto:** `git remote add origin ...` y `git push -u origin main`.
4. **Clonación por integrantes** con `git clone`.
5. **Creación de ramas individuales:**
   - `Denis/navbar-header`
   - `David/cards-content`
   - `Johan/footer`
6. **Trabajo individual:** cada integrante implementó su sección con clases de Bootstrap.
7. **Commits individuales:** mínimo 3 commits por integrante (ver `git log --oneline`).
8. **Subida de ramas:** `git push -u origin nombre-rama`.
9. **Actualización con `git pull origin main`** antes del merge.
10. **Integración final:** se hicieron merges sucesivos hacia `main`:
    ```
    git merge Denis/navbar-header
    git merge David/cards-content
    git merge Johan/footer
    git push origin main
    ```

---

## 7. Verificación final

- [x] El sitio web funciona correctamente al abrir `index.html`.
- [x] Todas las secciones utilizan únicamente clases de Bootstrap.
- [x] La carpeta `css/` está vacía (sin CSS local).
- [x] El sitio es completamente responsive (probado en móvil, tablet y escritorio).
- [x] La rama `main` contiene la versión integrada final.
- [x] Existen las tres ramas individuales con commits de cada estudiante.
- [x] El repositorio remoto en GitHub está actualizado.

---

## 8. Comandos clave utilizados

```bash
# Clonación
git clone https://github.com/wprogramacion2026-svg/landing-page-bootstrap-grupo7.git

# Crear rama
git checkout -b Denis/navbar-header

# Verificar rama actual
git branch

# Subir cambios
git add .
git commit -m "mensaje del commit"
git push -u origin nombre-rama

# Actualizar antes del merge
git checkout main
git pull origin main

# Merge final
git merge Denis/navbar-header
git merge David/cards-content
git merge Johan/footer
git push origin main

# Historial
git log --oneline
git status
```

---

## 9. Capturas requeridas (anexar al entregar)

1. Repositorio en GitHub mostrando rama `main`.
2. Vista de las ramas individuales (`Denis/navbar-header`, `David/cards-content`, `Johan/footer`).
3. Historial de commits por integrante.
4. Sitio web funcionando en el navegador (escritorio).
5. Sitio web en versión responsive (móvil).
6. Tabla de distribución del trabajo (incluida en este informe, sección 5).

---

**Conclusión:** El grupo completó las 12 actividades del laboratorio aplicando Bootstrap como única herramienta de estilos. Se reforzó el trabajo colaborativo con Git mediante ramas individuales, commits descriptivos, manejo de conflictos y la integración final en la rama `main`.
