# 💪 Prácticas y Ejercicios de Análisis de Datos

<div align="center">

![MySQL](https://img.shields.io/badge/MySQL-Relacional-lightgrey?style=for-the-badge&logo=mysql)

</div>

Repositorio de ejercicios prácticos para desarrollar habilidades en análisis de datos, bases de datos y herramientas de ciencia de datos. Este espacio agrupa ejercicios, casos prácticos y soluciones de problemas reales utilizando diferentes tecnologías.

## 🎯 Propósito

- Aplicar conceptos teóricos en situaciones prácticas y casos de uso reales
- Reforzar el aprendizaje mediante ejercicios resueltos y comentados
- Desarrollar habilidades de resolución de problemas en análisis de datos
- Crear un portafolio consolidado de casos prácticos y técnicas
- Servir como referencia para futuros proyectos y análisis

## 📚 Estructura del Repositorio

```
Practicas y ejercicios/
├── README.md                           # Este archivo
├── MYSQL/                              # 🗄️ Ejercicios de Bases de Datos SQL
│   ├── SQL.md                          # Documentación de ejercicios SQL
│   ├── Analisis_con_MySQL.sql         # Ejercicios de alumnos titulados
│   ├── caso_practico.sql              # Análisis de tienda de alimentos
│   ├── Pixar.sql                      # Importación y consultas de CSV
│   ├── pixar_films.csv                # Datos de películas de Pixar
│   └── sql_Riaz.sql                   # Modelo completo de inventario
├── PYTHON/                             # 🐍 (Próximamente)
├── PANDAS/                             # 📊 (Próximamente)
├── MATPLOTLIB/                         # 📈 (Próximamente)
├── NUMPY/                              # 🔢 (Próximamente)
└── R/                                  # 📉 (Próximamente)
```

---

## 📁 Módulos Actuales

### 🗄️ **SQL - Gestión de Bases de Datos**

**Carpeta**: [`MYSQL/`](./MYSQL/)

Colección de ejercicios prácticos de SQL con MySQL para desarrollar habilidades en gestión de bases de datos, consultas avanzadas y análisis de datos.

**📄 Archivos incluidos:**

1. **Analisis_con_MySQL.sql** - Base de datos de alumnos titulados
   - Creación de tablas relacionadas con 50 registros de ejemplo
   - Práctica de integridad referencial y Foreign Keys
   - Habilidades: creación de tablas, inserción de datos, relaciones

2. **caso_practico.sql** - Análisis de negocio para tienda
   - 6 consultas analíticas para inteligencia empresarial
   - Identificación de clientes valiosos, productos populares, temporadas altas
   - Habilidades: JOINs complejos, GROUP BY, agregaciones, análisis de datos

3. **Pixar.sql** - Importación y análisis de datos
   - Carga de datos desde `pixar_films.csv` con películas reales de Pixar
   - Consultas de filtrado, búsqueda de patrones y agrupación
   - Habilidades: LOAD DATA INFILE, importación CSV, valores nulos, LIKE

4. **sql_Riaz.sql** - Modelo relacional completo
   - Diseño de 7 tablas para gestión de inventario y ventas
   - Sistema completo con Empleados, Clientes, Productos, Pedidos e Inventario
   - Habilidades: diseño relacional, múltiples relaciones, normalización

**Ver documentación completa:** [MYSQL/SQL.md](./MYSQL/SQL.md)

---

## **Ejercicios de MySQL**

**Archivo**: [`Analisis_con_MySQL.sql`](./Analisis_con_MySQL.sql)

### Descripción
Ejercicios prácticos aplicando conceptos de MySQL con una base de datos de estudiantes titulados que incluye:
- Tabla `info_titulados`: 101 registros con información académica
- Tabla `alumnos`: 101 registros con datos personales
- Relación mediante llave foránea para practicar JOINs

### Ejercicios Incluidos
- ✅ **Consultas básicas**: SELECT con filtros y condiciones
- ✅ **Agregaciones**: COUNT, SUM, AVG, MIN, MAX
- ✅ **Agrupamiento**: GROUP BY y HAVING
- ✅ **Joins**: INNER JOIN, LEFT JOIN con múltiples condiciones
- ✅ **Ordenamiento**: ORDER BY con criterios complejos
- ✅ **Análisis estadístico**: Promedios, rankings, distribuciones

### Casos de Análisis
- Estudiantes titulados por año y universidad
- Promedios académicos por carrera
- Distribución geográfica de universidades
- Rankings de mejores estudiantes
- Análisis de datos relacionales con JOINs

---

## 🏪 **Caso Práctico: Tienda de Alimentos Congelados**

**Carpeta**: [`congelados_sql/`](./congelados_sql/)

### Descripción
Caso práctico completo de una tienda de alimentos congelados que busca optimizar sus operaciones y maximizar las ventas. Incluye diseño de base de datos completa y análisis estratégico de negocio.

### **📄 sql_Riaz.sql** - Estructura de Base de Datos
**Base de datos completa** con 7 tablas relacionadas:

- **👥 Empleados**: Gestión de personal de la tienda
- **🛍️ Clientes**: Base de datos de clientes
- **🏭 Proveedores**: Información de proveedores
- **📦 Productos**: Catálogo completo con precios
- **💰 Ventas**: Registro de todas las transacciones
- **📋 Pedidos**: Gestión de pedidos y entregas
- **📊 Inventario**: Control de stock y existencias

### **📈 caso_practico.sql** - Análisis de Optimización

**Análisis estratégicos** para la toma de decisiones:

- ✅ **Clientes más valiosos**: TOP 5 clientes por volumen de compras
- ✅ **Productividad empleados**: Ranking de empleados por ventas generadas
- ✅ **Productos populares**: TOP 3 productos más vendidos por cantidad
- ✅ **Análisis de proveedores**: Proveedores con productos más exitosos
- ✅ **Temporada alta**: Identificación del mes con mayor facturación
- ✅ **Fidelidad de clientes**: Frecuencia de compra y gasto promedio

---

## 📅 Próximos Módulos

| Tecnología | Estado | Descripción |
|-----------|--------|-------------|
| **Python** 🐍 | 🔄 Próximamente | Fundamentos de programación y análisis con scripts |
| **Pandas** 📊 | 🔄 Próximamente | Manipulación y análisis de datos con DataFrames |
| **Matplotlib** 📈 | 🔄 Próximamente | Visualización de datos y creación de gráficos |
| **NumPy** 🔢 | 🔄 Próximamente | Computación científica y operaciones numéricas |
| **R** 📉 | 🔄 Próximamente | Análisis estadístico y visualización avanzada |

---

## 🚀 Cómo Usar Este Repositorio

### Para principiantes en SQL
1. Comienza con [`MYSQL/SQL.md`](./MYSQL/SQL.md) para entender qué contiene cada archivo
2. Ejecuta `Analisis_con_MySQL.sql` para practicar operaciones básicas
3. Continúa con `Pixar.sql` para aprender importación de datos
4. Termina con `caso_practico.sql` para ver análisis real de negocios

### Para usuarios avanzados
- Modifica las consultas existentes y experimenta
- Combina conocimientos de múltiples archivos
- Crea nuevas tablas y relaciones propias
- Desarrolla casos de uso personalizados

### Estructura general de estudio
```
SQL Básico → SQL Avanzado → Análisis de Datos → Visualización → ML/IA
   (MySQL)      (Casos)      (Pandas/Python)   (Matplotlib)   (R/NumPy)
```

---

## 📚 Requisitos Generales

- **MySQL 5.7+** para ejercicios SQL
- **Python 3.8+** para ejercicios futuros de Python
- Cliente SQL (MySQL Workbench, DBeaver, etc.)
- IDE o editor de texto (VS Code, PyCharm, etc.)

---

## 📝 Notas Importantes

- Todos los ejercicios están completamente comentados
- Algunos archivos incluyen datos de ejemplo listos para usar
- Este es un repositorio en crecimiento constante

---

## 🎓 Metodología

Este repositorio sigue una **metodología progresiva**:
- ✅ **Básico**: Conceptos fundamentales y operaciones simples
- ✅ **Intermedio**: Combinación de técnicas y casos más complejos
- ✅ **Avanzado**: Análisis completo, optimización y mejores prácticas

---

**Último actualizado**: Diciembre 2025
- Limpieza y transformación de datasets
- Estadística descriptiva e inferencial

### **Proyectos Integrados** *(Planificado)*
- Análisis completo desde MySQL hasta Python
- Visualización de resultados
- Reportes automatizados

---

## Metodología

1. **Problema definido**: Cada ejercicio tiene un objetivo claro
2. **Solución paso a paso**: Código comentado y explicado
3. **Validación**: Verificación de resultados
4. **Documentación**: Explicación del proceso y conclusiones

---

*Para apuntes teóricos consultar: [`MySQL/`](../MySQL/) y [`Analisis_Python/`](../Analisis_Python/)*