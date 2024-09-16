# Análisis de Ventas de Videojuegos
<h2>Tecnologías Utilizadas</h2> <div class="badges-container"> <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" alt="Matplotlib"> <img src="https://img.shields.io/badge/Seaborn-3881E3?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn"> <img src="https://img.shields.io/badge/scikit--learn-5C9CD9?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn"> </div>

## Descripción del Proyecto
El objetivo del análisis es identificar patrones que determinen el éxito de un videojuego, lo que permitirá a la tienda online Ice planificar campañas publicitarias efectivas. El análisis se basa en un dataset que incluye información sobre ventas, plataformas, géneros, reseñas y clasificaciones de la ESRB.

## Objetivos específicos:

- Comprobar si las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Verificar si las calificaciones promedio de los géneros de Acción y Deportes son diferentes.

## Datos Utilizados
El dataset incluye la siguiente información:

- Videojuegos: Título, género, plataforma y año de lanzamiento.
- Reseñas: Calificaciones de usuarios y expertos.
- Ventas: Datos de ventas por región (América del Norte, Europa, Japón y otras).

## Pasos del Análisis
- Lectura de los Datos: Se lee el archivo /datasets/games.csv con la ayuda de la librería pandas.
- Preprocesamiento: Se realiza la limpieza de datos para eliminar valores nulos y corregir posibles inconsistencias en la información.
- Análisis de Datos:
Ventas por Año: Se analiza el número de juegos lanzados por año y las ventas totales por plataforma.
Plataformas Populares: Identificación de las plataformas con mayores ventas y análisis de la evolución de las plataformas que desaparecen.
- Análisis Regional: Se estudian las preferencias de los usuarios según la región.
- Pruebas de Hipótesis: Validación de las siguientes hipótesis:
Las calificaciones promedio de los usuarios son iguales para las plataformas Xbox One y PC.
Las calificaciones promedio son diferentes entre los géneros de Acción y Deportes.

## Resultados
### Juegos Lanzados por Año

<div style="display: flex; justify-content: center; gap: 10px;"> 
  <img src="https://github.com/user-attachments/assets/f1a6f527-3b11-4c6a-b123-728679cc3805" alt="Gráfico de lanzamientos por año" style="width: auto; height: auto;"> 
 
</div>

### Ventas por Plataforma

<div style="display: flex; justify-content: center; gap: 10px;"> 
  <img src="https://github.com/user-attachments/assets/3f9428af-9098-4ae8-a1d9-aca5049fd3ee" alt="Distribución de ventas por plataforma" style="width: 400px; height: auto;">
  <img src="https://github.com/user-attachments/assets/c393c427-b67e-4b29-8daa-c24669eab8cb" alt="Plataformas populares y en declive" style="width: 400px; height: auto;"> 
</div>

### Analisis de ventas por region
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4aa58a0-934d-46bf-97d8-a708294f80fa" alt="Descripción de la imagen">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/85bde78e-a045-42c2-88b7-38533d0aef22" alt="Descripción de la imagen">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fa9edbd8-661b-4f74-9d11-f1f03f7828f3" alt="Descripción de la imagen">
</p>

