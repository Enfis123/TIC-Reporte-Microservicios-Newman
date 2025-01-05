# Reporte de Pruebas Automatizadas con Newman y Postman

Este repositorio contiene un reporte detallado de las pruebas automatizadas realizadas sobre los servicios RESTful de la aplicación de agendamiento. Las pruebas se ejecutaron utilizando [Newman](https://github.com/postmanlabs/newman), la CLI oficial de Postman, junto con el reporteador avanzado **htmlextra**.

## 📋 Descripción del Proyecto
El proyecto incluye un conjunto de pruebas automatizadas diseñadas para validar los endpoints de microservicios de una arquitectura basada en principios de Domain-Driven Design (DDD). Estas pruebas abarcan validaciones de:
- **Códigos de estado HTTP.**
- **Estructura y contenido de las respuestas.**
- **Tiempo de respuesta y desempeño.**
- **Scripts de validación personalizados.**

El reporte generado en formato HTML proporciona una vista interactiva y detallada de las pruebas ejecutadas.

## 📂 Contenido del Repositorio
- **`mi_coleccion.json`**: La colección exportada desde Postman que contiene todas las solicitudes y pruebas configuradas.
- **`mi_entorno.json`**: El archivo de configuración del entorno, con valores como URLs y credenciales.
- **`reporte-pruebas.html`**: El reporte generado por **htmlextra**, que incluye los resultados de todas las pruebas.
- **`README.md`**: Este archivo, con instrucciones y detalles del repositorio.

## 🛠️ Herramientas Utilizadas
Las siguientes herramientas fueron utilizadas para la ejecución y generación de reportes:
- **Postman:** Para la configuración de las pruebas.
- **Newman:** Para la ejecución de las pruebas en línea de comandos.
- **htmlextra:** Para la generación de un reporte detallado e interactivo en HTML.

## 📊 Detalles del Reporte
El reporte HTML incluye:
1. **Resumen General:**  
   Una visión general del estado de las pruebas (total de pruebas ejecutadas, aprobadas y fallidas).
   
2. **Resultados de las Pruebas:**  
   - **Endpoint:** La URL probada.  
   - **Método:** GET, POST, PUT, DELETE, etc.  
   - **Código de Estado:** Validación del código esperado.  
   - **Tiempo de Respuesta:** Estadísticas de rendimiento para cada solicitud.  
   - **Ejecución de Scripts:** Visualización de los scripts configurados en Postman, como validaciones de respuesta.  

3. **Detalles de Errores:**  
   Reporta fallas en las pruebas con descripciones claras, como códigos de estado incorrectos o datos inesperados en la respuesta.

4. **Cuerpo de la Solicitud y Respuesta:**  
   Se incluye información completa sobre las solicitudes realizadas y las respuestas recibidas.

## 🚀 Cómo Visualizar el Reporte
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tuusuario/tu-repositorio.git
