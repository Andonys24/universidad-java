# Universidad Java

Repositorio central que reúne ejercicios prácticos y mini proyectos basados en la serie del curso **Universidad Java**. Una compilación progresiva de ejemplos y soluciones de código para aprender Java desde cero hasta temas avanzados.

> ⚠️ **Aclaración:** Este repositorio contiene ejercicios y código implementado basado en el curso "Universidad Java" de Udemy. El contenido y estructura del curso son propiedad del instructor original. Este repositorio es únicamente para propósitos educativos y de práctica personal.

## 📚 Módulos y Repositorios

### Módulos 01-10: Fundamentos Básicos
**Repositorio:** [java-fundamentos-basicos](https://github.com/Andonys24/java-fundamentos-basicos)

Aprende los fundamentos esenciales de Java:
- Introducción a Java y primer programa
- Variables, tipos de datos y constantes
- Manejo y manipulación de cadenas
- Entrada de datos con Scanner
- Operadores aritméticos, lógicos y relacionales
- Estructuras de decisión (if/else, switch)
- Ciclos (for, while, do-while)
- Arreglos unidimensionales
- Matrices bidimensionales
- Funciones y métodos

---

### Módulos 11-12: POO y Colecciones
**Repositorio:** [java-poo-colecciones](https://github.com/Andonys24/java-poo-colecciones)

Profundiza en Programación Orientada a Objetos y Colecciones:
- Programación Orientada a Objetos: clases, objetos y encapsulamiento
- Herencia, polimorfismo y abstracción
- Interfaces y clases abstractas
- Colecciones: List, Set y Map
- Manejo de excepciones (try-catch-finally)
- Argumentos variables y JavaBeans
- Ciclo for-each y operaciones con colecciones

---

### Módulo 13: I/O y Persistencia en Archivos
**Repositorio:** [java-io-persistencia-archivos](https://github.com/Andonys24/java-io-persistencia-archivos)

Domina el manejo de archivos y persistencia de datos:
- Creación, lectura y escritura de archivos de texto
- Uso de `java.io` y `java.nio.file`
- Escritura incremental con FileWriter
- Persistencia básica en archivos CSV
- Ejemplo práctico: Máquina de Snacks con persistencia
- Separación por capas: Dominio, Servicio, Presentación

---

### Módulo 14: Conexión con MySQL - Zona Fit JDBC
**Repositorio:** [zona-fit-jdbc-base](https://github.com/Andonys24/zona-fit-jdbc-base)

Sistema de gestión de gimnasio con Java y MySQL:
- Conexión a base de datos MySQL con JDBC
- Implementación del patrón DAO (Data Access Object)
- Operaciones CRUD completas (Create, Read, Update, Delete)
- Uso de PreparedStatement para prevenir SQL Injection
- Gestión de variables de entorno con java-dotenv
- Manejo robusto de excepciones SQL
- Separación por capas: Conexión, Datos, Dominio, Presentación
- Validación de entrada del usuario
- Menú interactivo de consola

**Tecnologías:** Java 21, MySQL 8.0+, Maven, JDBC

---

### Módulo 15: Zona Fit con Spring Boot y JPA
**Repositorio:** [zona-fit-spring-boot](https://github.com/Andonys24/zona-fit-spring-boot)

Sistema de gestión de gimnasio con Spring Boot y MySQL:
- Framework Spring Boot para desarrollo ágil
- Spring Data JPA para acceso a datos automático
- Hibernate como ORM (Object-Relational Mapping)
- Arquitectura en capas: Model, Repository, Service, Presentation
- Inyección de dependencias automática
- Gestión automática de transacciones
- Uso de Lombok para reducir boilerplate
- CommandLineRunner para aplicación de consola
- Logging con SLF4J + Logback

**Tecnologías:** Java 21, Spring Boot 3.4.5, Spring Data JPA, MySQL 8.0+, Maven, Lombok

---

### Módulo 16: Zona Fit con GUI Swing
**Repositorio:** [zona-fit-interfaz-swing](https://github.com/Andonys24/zona-fit-interfaz-swing)

Sistema de gestión de gimnasio con interfaz gráfica Swing:
- Interfaz gráfica moderna con Swing
- Modo oscuro automático con FlatLaf
- Spring Boot integrado con GUI de escritorio
- Spring Data JPA para persistencia de datos
- Arquitectura en capas: Model, Repository, Service, GUI
- Tabla de clientes con funcionalidad interactiva
- Formulario Swing con validación
- Operaciones CRUD desde interfaz gráfica
- Eventos y listeners en componentes Swing
- Integración con MySQL

**Tecnologías:** Java 21, Spring Boot 3.5.5, Spring Data JPA, Swing, FlatLaf, MySQL 8.0+, Maven, Lombok, IntelliJ IDEA

**Nota importante:** Este proyecto utiliza archivos `.form` de IntelliJ IDEA y requiere esta IDE para funcionar correctamente.

---

### Módulo 17: Zona Fit con Interfaz Web (JSF/Spring Boot)
**Repositorio:** [zona-fit-interfaz-web-basica](https://github.com/Andonys24/zona-fit-interfaz-web-basica)

Sistema de gestión de gimnasio con interfaz web moderna:
- Aplicación web con Spring Boot integrado
- JSF (Jakarta Faces) con PrimeFaces para componentes UI
- Interfaz web moderna y responsive con PrimeFlex
- DataTable dinámico para gestión de clientes
- Modales para agregar y editar clientes
- Confirmación de acciones con ConfirmDialog
- Mensajes de notificación con Growl
- Spring Data JPA para persistencia de datos
- Arquitectura en capas: Model, Repository, Service, Controller (JSF)
- AJAX automático en componentes PrimeFaces
- Tema oscuro Vela de PrimeFaces
- Acceso desde navegador web en localhost:8080/index.xhtml

**Tecnologías:** Java 21, Spring Boot 3.5.5, JSF, PrimeFaces 13+, JoinFaces, PrimeFlex, Spring Data JPA, MySQL 8.0+, Maven, Lombok

---

## 🎯 Cómo usar este repositorio

1. Cada módulo tiene su propio repositorio independiente.
2. Recomendamos seguir los módulos en orden (01 → 02 → 03 → ... → 13).
3. Clona el repositorio del módulo que desees estudiar:
   ```bash
   git clone https://github.com/Andonys24/[nombre-repositorio].git
   ```

## 📖 Recursos

- **Curso base:** Universidad Java (Udemy)
- **Lenguaje:** Java JDK 8+
- **IDE recomendado:** Visual Studio Code
- **Extensiones VS Code:** Extension Pack for Java

## 🤝 Contribuciones y Aclaraciones

Este es un proyecto educativo personal basado en el curso "Universidad Java".

---

⭐ Si estos repositorios te resultan útiles, considera darles una estrella