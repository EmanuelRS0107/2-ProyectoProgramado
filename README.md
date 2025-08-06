 Hellen Adriana Lobo Rodríguez  
 Emanuel Rodríguez Sánchez  
Estudiantes de segundo año, Ingeniería en Sistemas  
Curso: Programación IV  

---

 Resumen Ejecutivo

Este proyecto es una aplicación de escritorio desarrollada en Java con interfaz gráfica Swing, pensada para gestionar clientes, vehículos, servicios y órdenes de trabajo en una academia automotriz ficticia. El sistema simula una base de datos utilizando archivos `.txt` y `.csv` para almacenar y recuperar información.

Durante el desarrollo se aplicaron conceptos clave de la programación orientada a objetos como clases, herencia, polimorfismo, interfaces, colecciones genéricas y manejo de excepciones. También se utilizaron buenas prácticas con Git para control de versiones.

La aplicación permite registrar, consultar, modificar y eliminar datos desde una interfaz amigable y sencilla. Su propósito principal es educativo, para aplicar de forma práctica los conocimientos del curso.

---

 Objetivo General

Desarrollar una aplicación de escritorio en Java que permita gestionar clientes, vehículos, servicios y órdenes de trabajo para una academia automotriz, aplicando principios de programación orientada a objetos.

 Objetivos Específicos

- Diseñar una estructura modular organizada por paquetes.
- Crear una interfaz gráfica con Swing fácil de usar.
- Usar archivos `.txt` para simular persistencia de datos.
- Incluir operaciones CRUD en cada módulo.
- Utilizar GitHub para el control de versiones.
- Manejar errores mediante excepciones y validaciones.

---

 Descripción del Problema

Muchas academias automotrices manejan sus procesos de forma manual o desorganizada, lo que genera pérdida de datos y duplicidades. Este proyecto busca resolver eso con una solución sencilla que permita administrar información básica sin depender de una base de datos.

---

 Desarrollo del Sistema

- **Lenguaje:** Java  
- **Interfaz gráfica:** Swing  
- **Persistencia:** Archivos `.txt` y `.csv`  
- **Estructura:** Organizado en paquetes: `clientes`, `vehículos`, `servicios`, `facturación`, etc.  
- **Funcionalidades:** CRUD en cada módulo, mensajes personalizados, validación de errores.  
- **Control de versiones:** Git y GitHub  

Se utilizó una clase encargada del manejo de archivos y se creó una interfaz gráfica sencilla con menús y botones intuitivos para facilitar el uso por parte del usuario.

---

 Resultados y Conclusiones

Se cumplieron los objetivos planteados:

- Aplicación de POO en un proyecto real
- Estructura organizada por paquetes
- Uso de archivos para simular almacenamiento
- Interfaz funcional con Swing

### Dificultades enfrentadas:

- Métodos mal llamados o inexistentes en algunas clases
- Archivos con mal formato generaban errores al cargar
- Algunos mensajes incorrectos entre módulos
- Errores al adaptar paneles y conectar archivos

Pese a estos problemas, se logró entregar un sistema funcional, estable y con las operaciones básicas completas.

---

 Recomendaciones Futuras

- Agregar login para diferentes roles de usuario
- Generar e imprimir facturas desde las órdenes
- Conexión con una base de datos real (como MySQL)
- Validaciones más estrictas para evitar errores del usuario
- Búsquedas avanzadas y reportes personalizados
