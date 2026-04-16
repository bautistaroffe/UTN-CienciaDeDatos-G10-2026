# Clasificación Multiclase de Exoplanetas - UTN Ciencia de Datos (Grupo 10)

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning capaz de clasificar exoplanetas en diferentes categorías (Terrestres, Supertierras, Mini-Neptunos y Gigantes Gaseosos) utilizando datos de observaciones astronómicas de la NASA. 

Originalmente planteado como un estudio de habitabilidad, el enfoque se ha pivotado hacia una **clasificación multiclase** para cumplir con los requisitos académicos de la cátedra, evitando variables binarias y profundizando en la ingeniería de datos y el análisis físico-estelar.

## Estructura del Repositorio
* `Data/`: Contiene el dataset original y los archivos procesados tras el ETL.
* `Notebooks/`: Jupyter Notebooks con el análisis exploratorio (EDA), limpieza y entrenamiento de modelos.
* `Docs/`: Documentación del proyecto e informes de entrega.
* `src/`: Scripts de Python auxiliares para limpieza y visualización.

## Dataset
Se utiliza el **NASA Exoplanet Archive Data**, que incluye variables críticas como:
* **Físicas:** Radio (`pl_rade`), Masa (`pl_bmasse`), Densidad.
* **Orbitales:** Período orbital (`pl_orbper`), Temperatura de equilibrio (`pl_eqt`).
* **Estelares:** Metalicidad (`st_met`), Masa estelar (`st_mass`), Temperatura efectiva (`st_teff`).

## Hoja de Ruta (Sprints)
1. **Sprint 0:** Configuración del entorno y selección del dataset (Finalizado el 15/04/2026).
2. **Sprint 1:** ETL y generación de la variable objetivo mediante Ingeniería de Datos.
3. **Sprint 2:** Análisis Exploratorio de Datos (EDA) y validación de hipótesis.
4. **Sprint 3:** Selección de algoritmos y entrenamiento de modelos multiclase.
5. **Sprint 4:** Interpretación de resultados y Data Storytelling final.

## Integrantes del Grupo 10 (Curso 5K4)
* Roffe Apra, Bautista 
* Belli, Marcos Ignacio 
* Alfonso, Francisco 
* Pereira Duarte, Manuel 
* Yorio, Santino Baltazar 
* Escudero, Jeremías 
* Bossi, Augusto 
* Lovera, Federico 

## Cómo utilizar este repositorio
1. Clonar el repositorio: `git clone https://github.com/[USUARIO]/[NOMBRE-REPO].git`
2. Instalar dependencias: `pip install -r requirements.txt` (próximamente)
3. Ejecutar los notebooks en la carpeta `Notebooks/` siguiendo el orden numérico.

---
© 2026 - Universidad Tecnológica Nacional (UTN)
