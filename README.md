# 🏥 Aplicación de Gestión de Pacientes

## 📄 Información del Proyecto

**📌 Autor:** Juan David Salazar Ortiz  
**📆 Año:** 2024 - 2025  
**📍 Ciudad:** Madrid  
**📚 Asignatura:** Desarrollo de Interfaces - 2do de DAM  
**🏫 Centro:** CPIFP Los Enlaces - Zaragoza 

![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)
![Framework](https://img.shields.io/badge/Spring%20Boot-2.7.2-blue)

## 📖 Sobre el Proyecto

En este proyecto, he trabajado para desarrollar una solución innovadora que facilita la **gestión de pacientes en consultorios médicos pequeños**. Nuestra aplicación permite:

✅ Agendar citas médicas 📅  
✅ Descargar informes y justificantes 📄  
✅ Realizar pagos de servicios 💳  
✅ Acceder a un perfil personalizado 👤  

![Gestión de Citas](https://images.ctfassets.net/63bmaubptoky/rUAaJE-ZpGM5tdbVeScrxrQvx0OThlVVLPuKkW8-SpY/050afca6feecd15118f58c05f0013f45/agendar-citas-ES-Capterra-Header.jpg?w=2200)

---

## 🛠️ Tecnologías Utilizadas

| Lenguaje/Framework | Descripción |
|--------------------|-------------|
| 🖥 **Java** | Backend con Spring Boot |
| 🔍 **H2/MySQL** | Base de datos |
| 🌐 **React.js** | Frontend interactivo |
| 🔗 **API REST** | Comunicación entre frontend y backend |

---

## 📂 Estructura del Proyecto

```mermaid
flowchart TD;
    Backend -->|API REST| Frontend;
    Frontend -->|React.js| UI;
    UI -->|Usuario| Interfaz;
    Backend -->|Base de Datos| MySQL/H2;
```

---

## 🚀 Instalación y Uso

### 1️⃣ Clona el Repositorio
```sh
git clone https://github.com/tu-usuario/app-gestion-pacientes.git
```

### 2️⃣ Configura el Backend
```sh
cd backend
mvn spring-boot:run
```

### 3️⃣ Ejecuta el Frontend
```sh
cd frontend
npm install
npm start
```

---

## 📊 Flujo de Autenticación

```mermaid
sequenceDiagram;
    participant Usuario;
    participant Frontend;
    participant Backend;
    participant DB;
    
    Usuario->>Frontend: Ingresar credenciales;
    Frontend->>Backend: Validación de datos;
    Backend->>DB: Verificar usuario;
    DB-->>Backend: Respuesta;
    Backend-->>Frontend: Autenticación exitosa;
    Frontend-->>Usuario: Acceso concedido;
```

---

## 📌 Diagramas de Gestión de Citas

```mermaid
gantt
    title Gestión de Citas Médicas
    dateFormat  YYYY-MM-DD
    section Reserva de Cita
        Solicitud del usuario :done, 2025-02-10, 1d
        Verificación de disponibilidad :active, after 2025-02-10, 1d
        Confirmación de cita :crit, after 2025-02-11, 1d
    section Atención Médica
        Consulta del paciente :after 2025-02-12, 1d
        Generación de informe :after 2025-02-13, 1d
```

---

## 🎥 Video de Demostración

[![Video de demostración](https://img.youtube.com/vi/572IhCYHIQQ/0.jpg)](https://www.youtube.com/watch?v=572IhCYHIQQ)

---

## 📬 Contacto
📩 Si tienes dudas o sugerencias, contáctanos en: **juandvsalazar@gmail.com**

---

