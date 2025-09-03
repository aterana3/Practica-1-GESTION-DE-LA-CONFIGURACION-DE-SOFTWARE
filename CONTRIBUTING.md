## 🌿 Convención de Nombres de Ramas

Usamos una convención de nombres de ramas **semántica** para clarificar el propósito de cada cambio y mejorar la trazabilidad.

**Formato:**

```
<tipo>/<descripción-corta-en-tiempo-presente>
```

**Ejemplos:**

```
add/crear-endpoint-asistencia
fix/arreglar-error-login-profesor
update/mejorar-filtro-citas
refactor/reestructurar-modelos-usuarios
```

**Tipos Permitidos:**

* `add/` – Nueva funcionalidad (endpoints, modelos, serializadores, etc.)
* `update/` – Mejoras en características existentes
* `refactor/` – Reestructuración de código sin cambios en el comportamiento
* `delete/` – Eliminación de código no utilizado o obsoleto
* `fix/` – Corrección de errores
* `docs/` – Actualizaciones de documentación (README, docstrings, etc.)
* `style/` – Formateo de código o linting (sin cambios en la lógica)

---

## 💬 Convención de Mensajes de Commit

Seguimos un formato de mensajes de commit **semántico y descriptivo** para mantener el historial del proyecto claro y fácil de mantener.

**Formato:**

```
<Tipo>: <descripción corta en tiempo presente>
```

**Ejemplos:**

```
Add: Crear endpoint para asistencia de estudiantes
Fix: Resolver error de validación en el login de profesores
Update: Mejorar la paginación en la lista de estudiantes
Refactor: Extraer la lógica de notificaciones a un servicio separado
Docs: Agregar guía de uso para el endpoint de calificaciones
Style: Aplicar formato black a las vistas de asistencia
```

**Tipos Válidos:**

* `Add:` – Nuevas funcionalidades
* `Update:` – Mejoras en funcionalidades existentes
* `Refactor:` – Cambios estructurales o internos sin impacto en el comportamiento
* `Delete:` – Eliminación de código o archivos
* `Fix:` – Corrección de errores
* `Docs:` – Actualización de documentación
* `Style:` – Ajustes de formato y estilo
