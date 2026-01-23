# 📱 MiAppCrudFirebase

![Android Studio](https://img.shields.io/badge/Android-Android%20Studio-3DDC84?logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-ffca28?logo=firebase&logoColor=black)
![Material Design](https://img.shields.io/badge/UI-Material%20Components-6200EE?logo=materialdesign&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En%20producción-green)

> 🔄 Este proyecto forma parte de una implementación doble (Web + Android) conectada a Firebase, manteniendo la misma lógica de autenticación y persistencia de datos.

Aplicación Android de gestión de usuarios y profesiones con autenticación integrada mediante Firebase.  
Proyecto CRUD modular y funcional, desarrollado en Java con Android Studio, Firebase Authentication y Firestore.

---

## 🚀 Descripción del Proyecto

**MiAppCrudFirebase** es una app Android nativa diseñada para registrar, autenticar y gestionar usuarios asociados a profesiones.  
Permite a los usuarios autenticarse con **alias + contraseña** y realizar operaciones **CRUD** sobre las entidades disponibles, todo de forma segura y privada mediante **UID**.

La app es totalmente funcional, modular y escalable, siguiendo buenas prácticas de organización y con una interfaz moderna basada en **Material Design**.


---
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

---
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

---

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
---

## 🛠️ Tecnologías utilizadas

- **Android Studio (Java)**
- **Firebase Authentication**
- **Cloud Firestore**
- **Material Components for Android**
- **ConstraintLayout**
- **RecyclerView**

---

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

---

## 📌 Requisitos previos

- Android Studio actualizado
- Firebase configurado con Authentication y Firestore
- Google Play Services y conexión a internet

---

## 📚 Aprendizajes clave

- Integración completa de Firebase Authentication y Firestore
- Gestión de datos con UID personalizado
- Arquitectura escalable y modular en Android Studio
- Validaciones profesionales y buen manejo del estado
- Uso avanzado de `Spinner`, `RecyclerView`, `MaterialButton` y `TextInputLayout`

---

## 🤝 Autor

**Nilson Ochoa Martínez**  
Desarrollador Web & Móvil Junior  
📍 Alicante, España  
💼 [LinkedIn](https://www.linkedin.com/in/nilsonochoa-dev/)  
📧 nilson-ochoamartinez@hotmail.com  

---

## ⭐ Licencia

Este proyecto es de uso libre para fines formativos.  
Si lo usas como base, se agradece la mención al autor.
