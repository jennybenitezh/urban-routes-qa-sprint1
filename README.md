> 💡 **Nota:** Este proyecto fue desarrollado como parte de mi formación en **QA Engineering en TripleTen**, aplicando técnicas de diseño y ejecución de pruebas de regresión, así como documentación estandarizada de errores.

---

## 📌 Descripción del Proyecto
**Urban Routes** es una aplicación web de transporte que calcula rutas, tiempos de viaje y tarifas para diversos medios de transporte (auto propio, a pie, taxi, bicicleta, scooter y transporte compartido). 

La interfaz cuenta con:
* Campos de ubicación: **"Desde"** (Punto A) y **"Hasta"** (Punto B).
* Tres modos de ruta: **Óptimo**, **Flash** y **Personal**.
* Selección de tipos de transporte.

Como **QA Engineer**, el objetivo de este Sprint 1 fue realizar las **pruebas de regresión** de la aplicación utilizando la plantilla de casos de prueba preestablecida, validar los resultados esperados frente a los reales e identificar y reportar todos los errores (bugs) encontrados para asegurar la calidad.

---

## 🎯 Objetivos y Tareas Realizadas
- [x] **Ejecución de Casos de Prueba:** Ejecución paso a paso de las pruebas de regresión en la última versión de **Google Chrome**.
- [x] **Evaluación de Estados:** Asignación del estado correspondiente (`Aprobada`, `No aprobada`, `Omitida`) a cada caso de prueba.
- [x] **Reporte y Documentación de Bugs:** Creación de reportes detallados para cada falla detectada con su severidad adecuada (*Bloqueador, Crítico, Grave, Menor, Trivial*).
- [x] **Trazabilidad:** Vinculación directa entre el ID del caso de prueba fallido y el ID del informe de error.

---

## 📊 Resumen de Ejecución (Métricas del Sprint)

| Métrica | Cantidad |
| :--- | :---: |
| **Total de Casos de Prueba Ejecutados** | 24 |
| 🟢 **Casos Aprobados (Passed)** | 19 |
| 🔴 **Casos No Aprobados (Failed)** | 5 |
| 🐛 **Total de Bugs Reportados** | 5 |

---

## 📁 Estructura del Repositorio

```text
├── README.md                          <- Descripción general y resumen del proyecto
├── Casos_de_Prueba_Urban_Routes.xlsx  <- Matriz de pruebas y reportes de errores
└── /evidencias                        <- Capturas de pantalla de los bugs
