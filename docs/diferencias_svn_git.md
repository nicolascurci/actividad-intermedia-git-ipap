# 4. Principales diferencias entre Subversion (SVN) y Git

| Característica          | Subversion (SVN)                             | Git                                               |
|-------------------------|----------------------------------------------|---------------------------------------------------|
| **Tipo de sistema**     | Centralizado                                 | Distribuido                                       |
| **Repositorio principal** | Único repositorio central                 | Cada usuario tiene una copia local completa       |
| **Trabajo offline**     | Limitado (requiere conexión para operaciones básicas) | Completo (commits, ramas, historial sin conexión) |
| **Velocidad**           | Más lento en operaciones complejas          | Rápido (almacenamiento local eficiente)          |
| **Manejo de ramas**     | Complejo (ramas "pesadas")                  | Sencillo (ramas "livianas")                       |
| **Fusiones**            | Conflictos frecuentes                       | Mecanismo avanzado de fusión                      |
| **Colaboración**        | Dependencia del servidor central            | Trabajo independiente + sincronización posterior  |
| **Historial**           | Lineal (dependiente del servidor)           | Completo (local, con reescritura flexible)        |

**Resumen**:  
- ⚙️ **SVN**: Ideal para proyectos pequeños con flujo de trabajo simple y control centralizado.  
- 🚀 **Git**: Recomendado para proyectos colaborativos, distribuidos y con necesidad de flexibilidad (ramas/fusiones).  
- 🔄 **Migración**: Hoy la industria favorece Git (GitHub/GitLab/Bitbucket), pero SVN sigue siendo útil en entornos empresariales tradicionales.