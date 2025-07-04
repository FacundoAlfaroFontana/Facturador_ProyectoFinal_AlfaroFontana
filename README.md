# 📊 Facturador API - Proyecto Final

Este proyecto es un sistema de facturación desarrollado en **Java** con **Spring Boot**. Permite administrar clientes, productos y ventas mediante una **API REST**.

El objetivo es gestionar las operaciones básicas de un comercio, integrando validaciones, conexión a base de datos y pruebas con **Postman**.

---

## 🚀 Funcionalidades principales

- CRUD de clientes y productos.
- Generación de comprobantes con validación de stock y control de precio histórico.
- Obtiene la fecha de comprobante desde una API externa (World Clock) o la genera localmente si la API falla.
- Incluye script SQL para crear la base de datos.
- `.jar` ejecutable para correr la aplicación.
- Colección Postman para probar todos los endpoints.

---

## ⚙️ Tecnologías utilizadas

- Java 17
- Spring Boot
- Maven
- Base de datos relacional (SQL)
- Postman

---

## 📂 Estructura del proyecto

/build
└── FacturacionEntregaProyectoFinalAlfaroFontana.jar

/postman
└── Facturador_Postman_Collection.json

/scripts
└── creacion_tablas.sql


---

## 📌 Requisitos previos

- Tener Java instalado y configurado (`JAVA_HOME`).
- Postman para ejecutar las pruebas (opcional).

---

## ▶️ Cómo ejecutar la aplicación

1. Crear la base de datos usando el script `creacion_tablas.sql`.
2. Ir a la carpeta `/build` y correr:
java -jar FacturacionEntregaProyectoFinalAlfaroFontana.jar

yaml
Copiar
Editar
3. La API quedará disponible en `http://localhost:8080/`.

---

## 🧪 Pruebas con Postman

1. Abrir Postman.
2. Importar `Facturador_Postman_Collection.json`.
3. Ejecutar las solicitudes para probar altas de clientes, productos y comprobantes.

---

## 👤 Autor

**Cristian Facundo Alfaro Fontana**  
Proyecto Final - Programación JAVA  
2025

---
