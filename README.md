# 📱 MiAppCrudFirebase

<p align="center">
  <a href="#english">🇬🇧 English</a> |
  <a href="#español">🇪🇸 Español</a>
</p>

---

## English

![Android Studio](https://img.shields.io/badge/Android-Android%20Studio-3DDC84?logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-ffca28?logo=firebase&logoColor=black)
![Material Design](https://img.shields.io/badge/UI-Material%20Components-6200EE?logo=materialdesign&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20production-green)

> 🔄 This project is part of a dual implementation (**Web + Android**) connected to Firebase, maintaining the same authentication logic and data persistence.  
> Both projects share the same **Firestore** database, ensuring data persistence and consistency between **Web and Android**.

<br/>

---

## 🚀 Project Description

**MiAppCrudFirebase** is a native Android application designed to **register, authenticate, and manage users associated with professions**.  
Users can authenticate using **alias + password** and perform secure **CRUD operations** on available entities using **UID** as a unique identifier.

The application is **fully functional, modular, and scalable**, following best practices in structure and featuring a modern interface based on **Material Design**.

<br/>

---

## 📷 Screenshots

<table align="center">
  <tr>
    <td align="center"><b>Sign Up</b></td>
    <td align="center"><b>Professions CRUD</b></td>
    <td align="center"><b>Login</b></td>
  </tr>
  <tr>
    <td><img src="./screenshots/Registro.png" alt="Sign up screen" width="260"/></td>
    <td><img src="./screenshots/Crud.png" alt="Professions CRUD" width="260"/></td>
    <td><img src="./screenshots/Login.png" alt="Login screen" width="260"/></td>
  </tr>
</table>

<br/>

---

## 🔐 Core Features

- User registration with **alias, name, and password**
- Login with validation and **UID-based session persistence**
- **Professions CRUD**
  - Create, read, update, and delete professions
- **Users CRUD**
  - Create, read, update, and delete users
  - Profession assignment via **Spinner**
  - Create a new profession directly from the Spinner
- Dynamic profession loading from **Firestore**
- Visual validations using `TextInputLayout.setError()`
- Modular architecture: `activities`, `adapters`, `models`, `utils`, `firebase`
- **UID-protected app**: each user can only access their own data

<br>
  
---

## 📂 Project Structure
```
MiAppCrudFirebase/
├── app/src/main/java/com/nilson/miappfirebase/
│   ├── activities (Splash, Login, Register, CRUDs...)
│   ├── adapters (UsuarioAdapter, ProfesionAdapter...)
│   ├── models (Usuario.java, Profesion.java...)
│   ├── firebase (FirebaseAuthManager, FirebaseRefs...)
│   ├── utils (Validaciones, constantes...)
├── res/layout (todos los XML)
├── .gitignore
├── README.md
```

<br>

---

## 🛠️ Technologies Used

- **Android Studio (Java)**
- **Firebase Authentication**
- **Cloud Firestore**
- **Material Components for Android**
- **ConstraintLayout**
- **RecyclerView**

<br>


## ✅ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/NILSONCURSODAM/crud-usuarios-firebase-Android-Studio.git
2. Open the project in **Android Studio**.

3. Create a **Firebase** project and download `google-services.json`:
   - Place it inside `app/`.

4. Sync the project with **Gradle**.

5. Run on an **emulator or physical device**.

<br>


## 📌 Requirements

- Updated **Android Studio**
- Firebase configured with **Authentication** and **Firestore**
- **Google Play Services** and internet connection
<br>
  

## 📚 Key Learnings

- Full integration of **Firebase Authentication** and **Firestore**
- **UID-based data isolation**
- **Scalable modular architecture** in Android Studio
- Professional **form validation** and state handling
- Advanced usage of **Spinner, RecyclerView, MaterialButton, and TextInputLayout**

<br>


## 🤝 Author

**Nilson Ochoa Martínez**  
Junior Web & Mobile Developer  
📍 Alicante, Spain  
💼 [LinkedIn](https://www.linkedin.com/in/nilsonochoa-dev/)  
📧 nilson-ochoamartinez@hotmail.com  

<br>

## ⭐ License
This project is free for **educational purposes**.  
If used as a base, attribution to the author is appreciated.


<br>
<br>
<br>
<br>
<br>
<br>

## Español 

![Android Studio](https://img.shields.io/badge/Android-Android%20Studio-3DDC84?logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-ffca28?logo=firebase&logoColor=black)
![Material Design](https://img.shields.io/badge/UI-Material%20Components-6200EE?logo=materialdesign&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En%20producción-green)

> 🔄 Este proyecto forma parte de una implementación doble (Web + Android) conectada a Firebase, manteniendo la misma lógica de autenticación y persistencia de datos.  
> Ambos proyectos comparten la misma base de datos en **Firestore**, permitiendo persistencia y consistencia de datos entre **Web y Android**.

<br>

## 🚀 Descripción del Proyecto

**MiAppCrudFirebase** es una app Android nativa diseñada para registrar, autenticar y gestionar usuarios asociados a profesiones.  
Permite a los usuarios autenticarse con **alias + contraseña** y realizar operaciones **CRUD** sobre las entidades disponibles, todo de forma segura y privada mediante **UID**.

La app es totalmente funcional, modular y escalable, siguiendo buenas prácticas de organización y con una interfaz moderna basada en **Material Design**.

<br>

## 📷 Capturas de Pantalla

<table align="center">
  <tr>
    <td align="center"><b>Registro</b></td>
    <td align="center"><b>CRUD Profesiones</b></td>
    <td align="center"><b>Login</b></td>
  </tr>
  <tr>
    <td><img src="./screenshots/Registro.png" alt="Pantalla de Registro" width="260"/></td>
    <td><img src="./screenshots/Crud.png" alt="CRUD de Profesiones" width="260"/></td>
    <td><img src="./screenshots/Login.png" alt="Pantalla de Login" width="260"/></td>
  </tr>
</table>

<br/>


## 🔐 Funcionalidades principales

- Registro de usuarios con **alias, nombre y contraseña**
- Inicio de sesión con validación y persistencia por **UID**
- CRUD de profesiones:
  - Crear, ver, editar y eliminar profesiones
- CRUD de usuarios:
  - Crear, ver, editar y eliminar usuarios
  - Asignación de profesiones mediante **Spinner**
  - Creación de nueva profesión directamente desde el Spinner
- Carga dinámica de profesiones desde **Firestore**
- Validaciones visuales con `TextInputLayout.setError()`
- Arquitectura modular y organizada: `activities`, `adapters`, `models`, `utils`, `firebase`
- App protegida por UID: cada usuario solo ve sus propios datos

<br>

## 📂 Estructura del proyecto
```
MiAppCrudFirebase/
├── app/src/main/java/com/nilson/miappfirebase/
│   ├── activities (Splash, Login, Register, CRUDs...)
│   ├── adapters (UsuarioAdapter, ProfesionAdapter...)
│   ├── models (Usuario.java, Profesion.java...)
│   ├── firebase (FirebaseAuthManager, FirebaseRefs...)
│   ├── utils (Validaciones, constantes...)
├── res/layout (todos los XML)
├── .gitignore
├── README.md
```
<br>

## 🛠️ Tecnologías utilizadas

- **Android Studio (Java)**
- **Firebase Authentication**
- **Cloud Firestore**
- **Material Components for Android**
- **ConstraintLayout**
- **RecyclerView**

<br>

## ✅ Cómo usar este proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/NILSONCURSODAM/crud-usuarios-firebase-Android-Studio.git
   ```

2. Abre el proyecto en Android Studio.

3. Crea un proyecto en Firebase y descarga el archivo `google-services.json`:
    - Añádelo a `app/`.

4. Sincroniza el proyecto con Gradle.

5. Ejecuta en un emulador o dispositivo físico.

<br>

## 📌 Requisitos previos

- Android Studio actualizado
- Firebase configurado con Authentication y Firestore
- Google Play Services y conexión a internet

<br>

## 📚 Aprendizajes clave

- Integración completa de Firebase Authentication y Firestore
- Gestión de datos con UID personalizado
- Arquitectura escalable y modular en Android Studio
- Validaciones profesionales y buen manejo del estado
- Uso avanzado de `Spinner`, `RecyclerView`, `MaterialButton` y `TextInputLayout`

<br>

## 🤝 Autor

**Nilson Ochoa Martínez**  
Desarrollador Web & Móvil Junior  
📍 Alicante, España  
💼 [LinkedIn](https://www.linkedin.com/in/nilsonochoa-dev/)  
📧 nilson-ochoamartinez@hotmail.com  

<br>

## ⭐ Licencia

Este proyecto es de uso libre para fines formativos.  
Si lo usas como base, se agradece la mención al autor.
