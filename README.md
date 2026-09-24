# Sistema de Gestion de Inventario - Techstore

## 1. Descripción del Proyecto
Este sistema permite la **gestión integral de ventas e inventarios** optimizando el control de existencias en tiempo real. Fue diseñado para mejorar la eficiencia operativa en *Techstore*.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [ ] Documentacion tecnica completada

## 3. Módulos del Sistema
| Modulo | Descripcion | Estado |
| --- | --- | --- |
| Autenticacion | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturacion | Generacion de comprobantes de pago | Pendiente |

## 4. Ejemplo de Codigo Fuente
```python
def verificar_stock(cantidad):
    if cantidad > 0:
        return "Producto Disponible"
    else:
        return "Sin Stock"
        
## 5. Enlaces Útiles
- [Ver Arquitectura del Sistema](docs/arquitectura.md)
- [Ver Casos de Uso Hospitalarios](docs/arquitectura/casos-de-uso.md)
- [Ver Diagrama de Secuencia de Login](docs/arquitectura/secuencia-autenticacion.md)
- [Ver Arquitectura del Sistema](docs/arquitectura.md)
- [Ver Manual de Usuario](docs/manual_usuario.md)
- [Ver Especificación de API](docs/api_endpoints.md)
- [Ver Guía de Despliegue](docs/despliegue.md)
- [Ver Políticas de Seguridad](docs/seguridad.md)
- [Ver Historial de Cambios (CHANGELOG)](CHANGELOG.md)
- [Repositorio Oficial en GitHub](https://github.com/gaps3600/documentacion-sistema-v1-)