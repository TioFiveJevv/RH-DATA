# RH-DATA
ESTE ES EL PROYECTO DE GRUPO NUMERO 6, RH DATA: GESTOR DE DEPARTAMENTO DE RECURSOS HUMANOS.

---

# 🚀 RH DATA – Gestor del Departamento de Recursos Humanos

### Grupo 6

> **Fecha de entrega:** 20 de enero de 2026
> **Valor:** 10 puntos
>
> Este documento consolida la idea inicial del proyecto (Semana 1) y define el alcance, requerimientos y compromiso de desarrollo del sistema RH DATA (Semana 2).

---

## 1. Ficha del Equipo (Info Semana 1)

| Nombre del Estudiante         | Rol Principal                    | GitHub/GitLab User |
| ----------------------------- | -------------------------------- | ------------------ |
| Griffin Manuell Germán        | Backend (Lógica y Base de Datos) | @griffin-german    |
| Jordy Eugenio Vásquez Vásquez | Fullstack / Líder del Proyecto   | @jordyvasquez      |
| Esliany Lima                  | Frontend / QA                    | @eslianylima       |

---

## 2. Definición del Negocio

### 🏢 La Empresa (Cliente)

El sistema **RH DATA** está dirigido a **cualquier empresa que posea una organización administrativa medianamente amplia y cuente con un Departamento de Recursos Humanos**, independientemente del sector al que pertenezca.

No se limita a una sola empresa específica, sino que está diseñado para adaptarse a organizaciones que manejan procesos formales de:

* Reclutamiento y selección de personal

* Gestión de empleados

* Control de pasantías

* Administración básica del talento humano

* **Tipo de empresa:** Empresas pequeñas y medianas con estructura organizacional definida

* **Sector:** Multisectorial (comercial, servicios, industrial, educativo, entre otros)

---

### ⚠️ El Problema

En muchas empresas con estructuras organizativas más amplias, la gestión del personal suele realizarse mediante documentos físicos, hojas de cálculo aisladas o sistemas poco integrados, lo que genera:

* Desorganización de la información.
* Dificultad para centralizar datos de empleados y candidatos.
* Falta de seguimiento adecuado en procesos de reclutamiento y pasantías.
* Pérdida de tiempo en búsquedas manuales.
* Riesgo de errores administrativos.

Estas dificultades afectan directamente la eficiencia del Departamento de Recursos Humanos y la toma de decisiones gerenciales.

---

### 💡 La Solución Propuesta

**RH DATA** es una aplicación de escritorio diseñada para **cualquier empresa que cuente con un Departamento de Recursos Humanos**, permitiendo centralizar, organizar y gestionar de forma eficiente toda la información relacionada con el personal.

El sistema proporciona una solución digital práctica y flexible que facilita el registro, consulta y control de candidatos, pasantes y trabajadores, adaptándose a diferentes tipos de organizaciones con estructuras administrativas más amplias.
Su diseño prioriza la facilidad de uso, la organización de la información y el apoyo a los procesos internos del área de Recursos Humanos.

---

## 3. Alcance del Proyecto (Scope)

El proyecto se desarrollará en un período académico de **11 semanas**, por lo que se define un alcance claro y realista.

### ✅ Dentro del Alcance (MVP)

1. Sistema de inicio de sesión con control de acceso.
2. Gestión de usuarios del sistema.
3. Registro y administración de postulantes.
4. Gestión de entrevistados con estados y observaciones.
5. Módulo de mejores postulantes.
6. Módulo de pasantes con control automático de horas.
7. Registro de postulantes aprobados.
8. Gestión básica de trabajadores:

   * Asistencia
   * Permisos
   * Amonestaciones
9. Sistema de búsqueda rápida.
10. Alertas visuales por exceso de permisos o amonestaciones.

---

### 🚫 Fuera del Alcance

1. Módulo de nómina y pagos.
2. Integración con sistemas contables o financieros.
3. Aplicación web o móvil.
4. Uso en red o multiempresa.
5. Integración con plataformas externas.
6. Reportes financieros avanzados.

---

## 4. Stack Tecnológico

* **Lenguaje de Programación:** Python
* **Framework Frontend:** Tkinter
* **Framework Backend:** Python (aplicación local)
* **Base de Datos:** SQLite
* **Herramientas Extra:**

  * Visual Studio Code
  * GitHub
  * Draw.io / PlantUML

---

## 5. Requerimientos

### ⚙️ Requerimientos Funcionales (RF)

| ID    | Título                | Descripción Breve                                   | Prioridad |
| ----- | --------------------- | --------------------------------------------------- | --------- |
| RF-01 | Autenticación         | Acceso mediante usuario y contraseña.               | Alta      |
| RF-02 | Gestión de Usuarios   | Crear y administrar usuarios del sistema.           | Alta      |
| RF-03 | Postulantes           | Registrar datos personales, académicos y laborales. | Alta      |
| RF-04 | Entrevistas           | Evaluar candidatos con estados y notas.             | Alta      |
| RF-05 | Mejores Postulantes   | Almacenar candidatos destacados.                    | Media     |
| RF-06 | Pasantes              | Control automático de horas de pasantía.            | Alta      |
| RF-07 | Postulantes Aprobados | Registro previo a contratación.                     | Alta      |
| RF-08 | Trabajadores          | Control de asistencia, permisos y sanciones.        | Alta      |
| RF-09 | Búsqueda              | Consulta rápida por campos.                         | Media     |
| RF-10 | Alertas               | Alertas visuales automáticas.                       | Media     |

---

### 🛡️ Requerimientos No Funcionales (RNF)

1. **Seguridad:** Acceso restringido a usuarios autorizados.
2. **Interfaz:** Diseño claro, intuitivo y fácil de usar.
3. **Disponibilidad:** Funcionamiento local sin internet.
4. **Usabilidad:** Orientado a usuarios con conocimientos informáticos básicos.





