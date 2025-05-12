# 📊 Proyecto de Análisis de Datos en Qlik Sense

Este repositorio contiene un proyecto completo de análisis de datos desarrollado en **Qlik Sense Cloud**, dividido en tres etapas clave: extracción, transformación y visualización. El objetivo es mostrar un pipeline de datos organizado y documentado, con enfoque en buenas prácticas.

---

## 🧱 Estructura del proyecto

proyecto retail Qlik/

├── 0. configuracion/ # archivo txt con variables globales

├── 1. datos externos/ # archivo Excel con datos ajenos a la conexion de MySQL (no esta porque su peso es mayor al soportado para poder adjuntarlo aquí en github, pero podran verlo desde Qlik)

├── 2. QVDs/ # archivos .qvd, dentro de la carpeta desarrollo (tampoco están, ya que su peso excede el permitido)

├── 3. QVS/ # archivos .qvs, dentro de la carpeta desarrollo

├── 4. Imagenes/ # imagenes de como quedaron las diferentes hojas del dashboard

├── 5. Documentación/ # un archivo pdf donde explico brevemente el proceso de elaboración de una aplicación analítica por capas

---

## ⚙️ Tecnologías utilizadas

- **Qlik Sense Cloud**
- Scripts QlikView (`.qvd` & `.qvs`)
- Modelado de datos (ETL)
- Dropbox (control de versiones de scripts)
- Visual Studio Code (control, revision y edicion de los archivos .qvs)

---

## 📥 Extracción

En esta etapa se conectan y cargan los datos crudos desde fuentes externas (MySQL & Excel, que no esta por su tamaño github no me permite subirlo). Se aplican primeras validaciones básicas de formato.

---

## 🔄 Transformación

Aquí se limpian y relacionan los datos para dejarlos listos para análisis. Se desnormalizan las tablas con el fin de lograr el modelo de datos "estrella". Ademas, se crean los campos y tablas necesarias para mejorar la visualizacion, como el calendario maestro

---

## 📈 Visualización

La app analítica principal incluye dashboards interactivos con KPIs y gráficos relevantes. Se crearon variables y elementos maestros que facilitan la modularizacion con el fin de sentar las bases de un proyecto escalable, al igual que se vienen respetando las buenas practicas en las dos fases anteriores (extraccion-transformacion)

---

## 🗂 Documentación

El archivo .pdf tiene un breve resumen de la forma de trabajo mediante las 3 capas y que se hace en cada una de ellas

---

## 🎥 Enlace a Qlik 

Con este enlace podras ver las diferentes hojas del dashboard: 🔗 [Dashboard-Qlik](jupidigital.us.qlikcloud.com/catalog?space_filter=681e90850d939e8066b88d0e)  

(me estuvo dando problemas, si no pudiste visualizarlo correctamente, no dudes en contactarme a mi gmail, zoddagj@gmail.com, estare agradecido de ser notificado, asi tambien de recibir comentarios y sugerencias)

---

## 👨‍💻 Autor

**Gianmarco**  
Bootcamp de Análisis de Datos – *Jupi Digital* (2025)  
🔗 [LinkedIn](www.linkedin.com/in/gianmarcozodda) 

---

> Este proyecto fue desarrollado como parte del proceso de formación en análisis de datos. Está enfocado en la organización del pipeline, la claridad visual y la trazabilidad de datos en Qlik Sense. Gracias a Jupi Digital por guiarme en el proceso y por brindarme herramientas y conocimientos valiosos
