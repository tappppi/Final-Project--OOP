# Final Project - Object-Oriented Programming

## Instituto Superior de Estudios Técnicos
### Tecnicatura Superior en Análisis, Desarrollo y Programación de Aplicaciones

## Object-Oriented Programming - Final Project

This repository contains the Final Project for the Object-Oriented Programming course. The goal of this project is to develop an application with a visual interface for the "Caminemos el Trayecto" Institute to manage its courses, instructors, and students.

### **Project Objectives:**
- Propose and manage courses, including prerequisites and maximum enrollment.
- Register and authenticate users (instructors, students, administrators).
- Manage course states: Proposed, Enabled, Completed, Closed, and Canceled.
- Student enrollment with prerequisite validation.
- Manage default passwords and allow users to change them.
- Admin management of users, including blocking and disabling accounts.
- **Data persistence** using object serialization with the `Serializable` interface.

### **Project Structure:**
- **Model:** Contains the classes representing the core entities of the system, such as:
  - `Administrador`
  - `Alumno`
  - `Curso`
  - `Instituto`
  - `Profesor`
  - `Usuario`
  
- **Exceptions:** Handles errors and exceptional situations that may arise during application use. Includes:
  - `DatosIncorrectosException`
  - `UsuarioNoEncontradoException`

- **Views:** Contains the files related to the user interface of the system. Includes:
  - `Login.form`
  - `Login`
  - `Visual_Administrador.form`
  - `Visual_Administrador`
  - `Visual_Alumno.form`
  - `Visual_Alumno`
  - `Visual_Profesor.form`
  - `Visual_Profesor`
  - **Popups:**
    - `Gestion_CambiarEstadoUsuario.form`
    - `Gestion_CambiarEstadoUsuario`
    - `Visual_AgregarUsuario.form`
    - `Visual_AgregarUsuario`
    - `Visual_CambiarContraseña.form`
    - `Visual_CambiarContraseña`
    - `Visual_FinalizarCurso.form`
    - `Visual_FinalizarCurso`
    - `Visual_GestionDeCursos.form`
    - `Visual_GestionDeCursos`
    - `Visual_GestionUsuario.form`
    - `Visual_GestionUsuario`
