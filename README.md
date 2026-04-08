# Sistema de Gestión Legal

## Descripción
Este proyecto consiste en un sistema de gestión legal con los siguientes módulos:

- **Login**: Autenticación de usuarios.
- **Expedientes**: Gestión de casos y documentos legales.
- **Aseguradoras**: Registro y gestión de compañías de seguros.
- **Tipo de Casos**: Clasificación de los diferentes tipos de casos legales.
- **Licenciado (Abogado)**: Gestión de abogados y asignación de casos.

El proyecto incluye diseño de base de datos, diagramas ER, normalización hasta 3FN, vistas SQL y una API REST mínima implementada con Flask.



---

## Diseño de la Base de Datos
- El diseño físico de la BD se encuentra en `BD/script.sql`.  
- Se incluyen todas las tablas necesarias para los módulos mencionados.  
- La base de datos se encuentra normalizada hasta **3FN**.  

---

## Diagramas ER
- Los diagramas de entidad-relación se encuentran en `diagramas/diagrama_ER.png`.  
- Permiten visualizar las relaciones entre tablas y los tipos de datos.


---

## API REST con Flask
La API mínima permite:  
1. **Crear nuevos registros**  
2. **Consultar información**

Archivos principales:  
- `api_flask/app.py` → Código principal de Flask  
- `api_flask/requirements.txt` → Dependencias necesarias  
- `api_flask/README.md` → Documentación de endpoints  

**Ejemplo de uso:**

```bash
# Instalar dependencias
pip install -r api_flask/requirements.txt

# Ejecutar la API
python api_flask/app.py
