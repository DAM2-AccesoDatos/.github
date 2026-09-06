# 👋 Bienvenidos a la organización de DAM2 Acceso a datos

Este espacio en **GitHub** está pensado para los alumnos y el profesor del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)** del IES Ciudad Escolar. Aquí centralizaremos **proyectos, prácticas, exámenes y recursos** del módulo profesional de 2º curso, Acceso a Datos, aprovechando herramientas colaborativas modernas.

---

## 🎯 Objetivos de este espacio

- Servir de **punto de intercambio de código** entre profesor y alumnos.  
- Gestionar las **prácticas y entregas** a través de ~~Github classroom~~  **classroom50**.  
- Familiarizarse con un **entorno profesional de control de versiones**.  
- Fomentar las **buenas prácticas de programación y trabajo en equipo**.

---

## 📘 Organización de repositorios de clase por RA

- **RA1 (Ficheros)**
<!--  - [Flujos de texto](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Texto) + [Flujos de texto avanzados](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Texto-avanzado.git)
  - [Flujos binarios](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Binarios) + [Flujos binarios avanzados](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Binarios-avanzado.git)
  - [Flujos Binarios Socket (Servidor)](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Binarios-Socket-Servidor)
  - [Flujos Binarios Socket (Cliente)](https://github.com/DAM2-AccesoDatos/RA1-Flujos-Binarios-Socket-Cliente)
  - [Ficheros Acceso Aleatorio](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Acceso-Aleatorio) + [Ficheros Acceso Aleatorio avanzado](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Acceso-Aleatorio-avanzado.git)
  - [Ficheros XML DTD DOM](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Xml-Dtd-Dom)
  - [Ficheros XML XSD DOM](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Xml-Xsd-Dom)
  - [Ficheros JSON](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Json)
  - [Ficheros JSON ampliado](https://github.com/DAM2-AccesoDatos/RA1-Ficheros-Json-ampli)
  -->
- **RA2 (JDBC)**
<!--
  - [JDBC API Nativa](https://github.com/DAM2-AccesoDatos/ra2-jdbc-clase)
  - [Spring JDBC 1](https://github.com/DAM2-AccesoDatos/ra2-spring-jdbc-1)
  - [Spring JDBC 2](https://github.com/DAM2-AccesoDatos/ra2-spring-jdbc-2)
  - [Spring JDBC 3](https://github.com/DAM2-AccesoDatos/ra2-spring-jdbc-3)
-->
- **RA3 (ORM)**
<!--
  - [Hibernate JPA 0](https://github.com/DAM2-AccesoDatos/ra3-orm-hibernate0)
  - [Hibernate JPA 1](https://github.com/DAM2-AccesoDatos/ra3-orm-hibernate1)
  - [Hibernate JPA 1 (avanzado)](https://github.com/DAM2-AccesoDatos/ra3-orm-hibernate1-avanzado) con separación de responsabilidades
  - [Hibernate JPA relaciones (1:1, 1:N, N:M)](https://github.com/DAM2-AccesoDatos/ra3-orm-hibernate-relaciones)
  - [Spring Data JPA (Hibernate) + Consola](https://github.com/DAM2-AccesoDatos/SVA_SPRING_BOOT_CONSOLA_NAVIDAD25)
  - [Spring Data JPA (Hibernate) + API Rest](https://github.com/DAM2-AccesoDatos/SVA_SPRING_BOOT_REST_NAVIDAD25)
  - [Spring Data JPA (Hibernate) + Api Rest (avanzado)](https://github.com/DAM2-AccesoDatos/SVA_SPRING_BOOT_REST_NAVIDAD25_TELEGRAM_BOT) con Telegram bot
-->
- **RA4 (BBDDOO)**
<!--  - [BBDDOO DB4O](https://github.com/DAM2-AccesoDatos/ra4-bbddoo)
-->
- **RA5 (BBDD NoSQL)**

  - Evaluado mediante trabajo grupal y defensa

- **RA6 (Componentes)**

  - Evaluado transversalmente en todos los temas así como durante la FFE (Fase de formación en empresa)

---

## 📝 Operativa en las pruebas de evaluación

Classroom 50 es una herramienta gratuita de código abierto para la distribución y evaluación de tareas de programación en GitHub. Ha sido desarrollada por Fifty Foundation y será la alternativa que usaremos en clase tras la reciente discontinuación de *Github Classroom* en julio de 2026.

Conceptualmente es como el aula virtual del instituto pero optimizado para programación y usando GitHub como plataforma de trabajo colaborativo y de entrega.

Los pasos a seguir durante los procesos de evaluación (exámenes y prácticas evaluables) son los siguientes:

1. El profesor crea una tarea y comparte un enlace de invitación a través del [Aula Virtual del instituto](https://aulavirtual3.educa.madrid.org/ies.ciudadescolar.madrid/course/view.php?id=663).

2. Al aceptar la invitación, a cada alumno se le genera automáticamente un **repositorio privado** personal en la organización de clase en GitHub [DAM2-AccesoDatos](https://github.com/DAM2-AccesoDatos). Solo estará accesible para el alumno y profesor.

3. El alumno debe clonar dicho repositorio en su equipo del aula. De esa forma se descargará una copia local del repo en su ordenador:

    ```bash
    git clone https://github.com/DAM2-AccesoDatos/practica-01-alumno.git
    ```

4. El alumno desarrollará la aplicación solicitada asegurandose de cubrir todos los requisitos funcionales y no funcionales exigidos en el enunciado.
  
5. Se debe ir registrando el avance progresivamente mediante **commits y push**.

6. Es responsabilidad del alumno asegurarse de subir todo al repositorio remoto antes de la fecha límite indicada pues será lo que el profesor calificará.

    > IMPORTANTE: El profesor tiene automatizada la detección del último commit realizado antes de la fecha límite, fijándole un **tag**, a partir del cual realizará la evaluación. Todo commit posterior será ignorado.

7. El profesor calificará y dará feedback sobre el trabajo subido al repositorio (**tag** del último commit válido) bajo una PR (pull request) y también publicará la calificación en el Aula Virtual del instituto.

8. El alumno podrá consultar la calificación y el feedback del profesor en la PR (pull request) del repositorio de GitHub así como la nota en la [sección de calificaciones del Aula Virtual](https://aulavirtual3.educa.madrid.org/ies.ciudadescolar.madrid/grade/report/grader/index.php?id=663).

## 📌 Recursos importantes

- 📚 [Documentación oficial de Git](https://git-scm.com/doc) — referencias rápidas y comandos.  
- 🎓 [GitHub Education / Estudiantes](https://education.github.com/students) — beneficios y guías para estudiantes.
- 🛠️ [Guía rápida de Markdown](https://www.markdownguide.org/basic-syntax/) — cómo formatear archivos README.
- 📘 [Wiki Fifty Foundation Classroom 50](https://github.com/foundation50/classroom50/wiki) - operativa Classroom 50.

## ✅ Normas básicas

- Acepta las invitaciones con tu **cuenta personal de alumno** (no con cuentas genéricas).
- Mantén un **historial de commits claro**: mensajes descriptivos y atómicos. Ve subiendo las modificaciones progresivamente, no todas de una vez. La luz del centro se va cuando menos te lo esperas y sería una pena perder todo el trabajo...
- Respeta las **fechas y horas de entrega** publicadas en cada práctica o examen. Cualquier cambio realizado (commit) posterior **no será tenido en cuenta en la evaluación**. Es responsabilidad del alumno asegurarse de que todo el trabajo esté subido a tiempo.
- No se permite el **plagio** ni la copia de código entre compañeros. Cada alumno debe entregar su propio trabajo. Cualquier indicio de copia será sancionado según la normativa del centro.
