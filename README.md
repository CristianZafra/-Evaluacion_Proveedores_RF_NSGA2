# Evaluación de Proveedores con Enfoque Híbrido: Random Forest + NSGA-II

Este repositorio contiene un cuaderno interactivo que implementa una **evaluación multicriterio del desempeño de proveedores** combinando:

-  **Random Forest** para predecir el desempeño global de los proveedores.
-  **NSGA-II (Non-dominated Sorting Genetic Algorithm II)** para generar un **frente de Pareto** con múltiples criterios clave como costo, calidad y puntualidad.

---

## Objetivos

- Entrenar un modelo predictivo del desempeño usando Random Forest.
- Aplicar optimización evolutiva para obtener una clasificación eficiente de proveedores.
- Visualizar el frente de Pareto y listar los proveedores más representativos.

---

##  Datos requeridos

El archivo CSV debe contener las siguientes columnas:

- `Proveedor`
- `Costo_total`
- `Calidad`
- `Entrega_oportuna`
- `Nivel_servicio`
- `Sostenibilidad`
- `Flexibilidad`
- `Desempeno_global` *(variable objetivo estimada)*

> Puedes usar el archivo de ejemplo:  
>  [proveedores_hibrido_simulado.csv](https://...)

---

##  ¿Cómo usar este proyecto?

1. **Clona este repositorio:**

```bash
git clone https://github.com/tuusuario/Evaluacion_Proveedores_Hibrido.git
