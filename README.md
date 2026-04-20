## CRUD de Productos con MVC
Programación Web — Unidad 6: JSP con MVC
Universidad de Santander (UDES) — Ingeniería de Sistemas 2026

## Descripción
Aplicación web Java que implementa el patrón MVC con Servlets como controlador, JSP con EL y JSTL como vista, y clases Java como modelo. Desarrolla un CRUD completo de productos que incluye listado, registro, edición y eliminación con redirección Post/Redirect/Get.

## Prerrequisitos
Java Development Kit (JDK) 17 o superior
Apache Tomcat 10.x
IntelliJ IDEA
Maven 3.8+
Navegador web moderno (Chrome, Firefox)

## Instrucciones de ejecución
Clonar el repositorio y abrir en IntelliJ
Ejecutar mvn clean package en la terminal
Configurar Tomcat: Run → Edit Configurations → + → Tomcat Server → Local
En Deployment agregar el artefacto .war exploded
Ejecutar y abrir http://localhost:8080/mvc-productos/productos


## Funcionalidades implementadas
Listado de todos los productos en una tabla
Registro de nuevo producto con validación de nombre y precio
Edición de producto existente con formulario precargado
Eliminación de producto con diálogo de confirmación
Mensajes de éxito tras cada operación (patrón PRG)
Separación de responsabilidades con patrón MVC (Modelo, Vista, Controlador)

## Capturas de Pantalla
Inventario de productos
<img width="1912" height="914" alt="1inventario" src="https://github.com/user-attachments/assets/058e66e3-637f-46a2-bf74-58084f5a2964" />
Registrar productos
<img width="1912" height="914" alt="2registrar" src="https://github.com/user-attachments/assets/90708ef0-6be5-4dc6-b985-9b224a7bb648" />
Agregar productos
<img width="1912" height="914" alt="3agregado" src="https://github.com/user-attachments/assets/21d7b606-228e-4c6b-acbe-85977e99e76a" />
Editar productos
<img width="1912" height="914" alt="4editar" src="https://github.com/user-attachments/assets/adb0bc3f-cae1-4bcf-8073-6abc56a4e3cd" />
Eliminar productos
<img width="1912" height="914" alt="5productoeliminado" src="https://github.com/user-attachments/assets/ad78e9cc-403d-4e29-a535-0df396ea2086" />

