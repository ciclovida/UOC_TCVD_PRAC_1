# UOC_TCVD_PRAC_1
Repositorio de la práctica 1 de la asignatura "Tipología y Ciclo de Vida de los Datos" del máster de Data Science de la UOC


Extrae los precios de diferentes alimentos de la página web del preciosmundi

Para ejecutar el script es necesario instalar la siguientes bibliotecas:

pip install pandas
pip install requests
pip install lxml
pip install beautifulsoup4
El script se debe ejecutar de la siguiente manera:

python foodPriceScraper.py --startDate 01/11/2017 --endDate 04/11/2017
Donde startDate es la fecha de inicio y endDate es la fecha de fin del intervalo de tiempo que se deseea extraer. Los registros se almacenan en un archivo de tipo CSV.

Actualmente solo extrae el precio mínimo, promedio y máximo de los siguientes alimentos:

Papa
Limon
Aceite
Ajo
Apio
Arroz
Azucar
Cebolla
Huevos
Leche
Pollo
Tomate
Yuca
Zanahoria
