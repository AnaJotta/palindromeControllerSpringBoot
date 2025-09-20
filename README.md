# palindromeControllerSpringBoot


API REST en **Spring Boot** que permite verificar si una cadena es palíndromo, devolverla invertida, y realizar operaciones relacionadas.

---

## 🧩 Características

- Verificar si un texto es palíndromo (ignorando mayúsculas, espacios, puntuación, etc.).  
- Devolver la versión invertida del texto.  
- Uso de DTOs para separar modelo de entrada / salida.  
- Tests incluidos para validar comportamiento.

---

## 📁 Estructura del proyecto

palindromeControllerSpringBoot/
│
├── src/
│ ├── main/
│ │ ├── java/… ← código fuente de la aplicación
│ │ └── resources/… ← configuración (application.properties, etc.)
│ └── test/
│ └── java/… ← pruebas unitarias
│
├── .gitignore
├── README.md
└── pom.xml (o build.gradle) ← configuración de construcción / dependencias

## 🚀 Requisitos

- Java 17+  
- Maven (o Gradle)  
- Spring Boot  

## ▶️ Ejecución

Clona el repositorio:
   ```bash
   git clone https://github.com/AnaJotta/palindromeControllerSpringBoot.git
   cd palindromeControllerSpringBoot

Compila y ejecuta:
bash
Copiar código
mvn spring-boot:run
(o ./gradlew bootRun si usas Gradle).

La aplicación estará disponible en http://localhost:8080.

📦 Endpoints principales

GET	/palindrome/{texto}	Verifica si el texto es palíndromo.
POST	/palindrome/reverse	Devuelve el texto invertido en JSON.

🤝 Autor
Ana Jotta — Proyecto de práctica con Spring Boot (La Geekipedia De Ernesto)



