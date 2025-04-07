<h1 align="center">🏥 Registro Básico de Pacientes en Java</h1>
<p align="center">Proyecto de práctica con Programación Orientada a Objetos</p>

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Finalizado-brightgreen"/>
  <img src="https://img.shields.io/badge/Java-8%2B-red"/>
  <img src="https://img.shields.io/badge/OOP-Fundamentals-blue"/>
  <img src="https://img.shields.io/github/last-commit/samantha09s/Registro-de-Pacientes?style=flat-square"/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=samantha09s.Registro-de-Pacientes" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/VbnUQpnihPSIgIXuZv/giphy.gif" width="400"/>
</p>

---

## Tabla de Contenidos
- [📂 Descripción](#-descripción)
- [🎯 Objetivo del Reto](#-objetivo-del-reto)
- [▶️ Cómo Ejecutar el Programa](#️-cómo-ejecutar-el-programa)
- [🛠️ Mejoras Futuras](#️-mejoras-futuras)
- [📁 Requisitos del Programa](#-requisitos-del-programa)
- [📦 Estructura del Proyecto](#-estructura-del-proyecto)
- [📤 Ejemplo de Salida Esperada](#-ejemplo-de-salida-esperada)
- [📘 Aprendizajes](#-aprendizajes)
- [📄 Licencia](#-licencia)
- [🤝 Conectemos](#-conectemos)

---

## 📂 Descripción
Este proyecto es una introducción práctica a la **Programación Orientada a Objetos en Java**. A través del reto, se busca implementar clases, objetos, atributos y métodos, así como manejar la entrada de datos desde consola utilizando `Scanner`.

---

## 🎯 Objetivo del Reto
Desarrollar un programa en Java que registre los datos de un paciente, utilizando los fundamentos de:
- Clases y Objetos.
- Atributos y Métodos.
- Entrada de datos por consola.

---

## ▶️ Cómo Ejecutar el Programa
1. Clona el repositorio
2. Abre el proyecto en tu IDE favorito (como IntelliJ IDEA o VSCode)
3. Ejecuta `Principal.java`
4. Ingresa los datos cuando se te soliciten

---

## 🛠️ Mejoras Futuras
- [ ] Validación de entradas
- [ ] Persistencia de datos con archivos
- [ ] Menú interactivo para múltiples pacientes

---

## 📁 Requisitos del Programa

### Clase: `Paciente`
Contiene los siguientes **atributos**:
```java
String nombre;
int edad;
String expediente;
```

Incluye el **método**:
```java
public void mostrarInformacion() {
    System.out.println("Nombre: " + nombre);
    System.out.println("Edad: " + edad);
    System.out.println("Expediente: " + expediente);
}
```

### Clase: `Principal`
Contiene el **método `main`**:
- Se crea un objeto de la clase `Paciente`.
- Se capturan los datos por consola usando `Scanner`.
- Se llama al método `mostrarInformacion()` para imprimir los datos.

---

## 📦 Estructura del Proyecto

```
├── Principal.java       // Ejecuta el programa y pide datos al usuario
└── Paciente.java        // Define la clase Paciente con atributos y método mostrarInformacion
```

---

## 📤 Ejemplo de Salida Esperada

```
--- Información del paciente ---
Nombre: Lena Marie
Edad: 25
Expediente: EXP202409
```

---

## 📘 Aprendizajes
- Declaración y uso de clases personalizadas
- Aplicación de métodos públicos
- Manejo de entrada de datos desde consola
- Separación de lógica en archivos independientes para mantener el código limpio y organizado

---

## 📄 Licencia
Este proyecto fue creado con fines educativos dentro del curso de **Programación en Java** por parte de Tecnolochicas FT + BEDU.

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🤝 Conectemos
- [GitHub](https://github.com/samantha09s)
- [LinkedIn](https://www.linkedin.com/in/samanthamunguia/)

---

<p align="center">
Gracias por visitar este repositorio. ¡Sigue explorando y aprendiendo más sobre Java! 💻📚
</p>
