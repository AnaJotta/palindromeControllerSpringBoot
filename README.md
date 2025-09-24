# 📖↔️📖 palindromeControllerSpringBoot
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![GitHub last commit](https://img.shields.io/github/last-commit/AnaJotta/palindromeControllerSpringBoot)

API REST en **Spring Boot** que permite verificar si una cadena es palíndromo, devolverla invertida, y realizar operaciones relacionadas.

---

## 🛠️ Características

- **Verificar palíndromo**: Determina si un texto es palíndromo, ignorando mayúsculas, espacios, puntuación, etc.
- **Invertir texto**: Devuelve la versión invertida de la cadena proporcionada.
- **Uso de DTOs**: Implementación de Objetos de Transferencia de Datos para separar el modelo de entrada y salida.
- **Pruebas unitarias**: Incluye tests para validar el comportamiento de los endpoints.

---

## ✅ Requisitos

- Java 17 o superior.
- Maven (o Gradle) para gestión de dependencias.
- Spring Boot como framework principal.

---

## ⚙️Instalación

- 1. Clona el repositorio:

   ```bash
   git clone https://github.com/AnaJotta/palindromeControllerSpringBoot.git
   cd palindromeControllerSpringBoot

- 2. Compila e inicia la aplicación:
bash
Copiar código
./mvnw spring-boot:run

La aplicación estará disponible en http://localhost:8080.

---

## 🔚 Endpoints principales

GET	/palindrome/{texto}	Verifica si el texto es palíndromo.
POST	/palindrome/reverse	Devuelve el texto invertido en JSON.

---

## 👏 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar la aplicación, por favor sigue estos pasos:
- Realiza un fork de este repositorio.
- Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
- Realiza tus cambios y haz commit de ellos (git commit -am 'Añadir nueva característica').
- Sube tus cambios a tu fork (git push origin feature/nueva-caracteristica).
- Abre un pull request describiendo tus cambios.


