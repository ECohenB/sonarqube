# sonarqube
Análisis Estático de Código con SonarQube y Maven en proyecto de java "Validador App"
Grupo 3
integrantes:
Emariana Cohen 
Claudio Figueroa
Oscar Valenzuela

- ¿Qué tipo de errores detectó SonarQube que podrían haber pasado desapercibidos?
  Sonar Qube detecto un error de "Maintainability" y esto se refiere a qué tan fácil es entender, modificar y extender el código. Si el código es complejo, repetitivo o mal estructurado, será difícil de mantener en el tiempo, lo que incrementa el riesgo de errores. En el ejercicio este punto se detectó en el archivo App.java al colocar en el código un usuario y clave de acceso que después se corrigió.
- ¿Qué ventajas tiene el análisis estático respecto al dinámico?
   El análisis estático se realiza sin ejecutar el programa, detecta errores tempranamente , es más rápido y no requiere datos de prueba.
- ¿Cómo impacta SonarQube en la calidad del software antes del despliegue?
  Evita que bugs lleguen a producción, al detectar problemas antes del deploy.
  Impulsa buenas prácticas, gracias a sus reglas automatizadas.
  Mejora la mantenibilidad, mostrando duplicación, deuda técnica y complejidad.
  Aumenta la confianza del equipo y stakeholders, al tener un monitoreo objetivo y constante.
  Se integra con pipelines CI/CD, bloqueando builds si no se cumplen criterios mínimos de calidad.
- ¿Qué políticas o reglas personalizarías según el tipo de proyecto?
  Las políticas o reglas que personalizaría en SonarQube dependerían del tipo y criticidad del proyecto. Por ejemplo, en proyectos críticos o financieros aplicaría reglas estrictas de seguridad, alta cobertura de pruebas (por encima del 80%) y cero errores bloqueantes. En cambio, en proyectos heredados o legacy, comenzaría aplicando solo las reglas más críticas para evitar frenar el desarrollo. Para APIs públicas o microservicios, priorizaría buenas prácticas REST, control de errores, duplicación de código y mantenibilidad. SonarQube permite crear perfiles de calidad personalizados para adaptar estas reglas según el contexto, asegurando un análisis coherente y útil para cada tipo de proyecto.

![image](https://github.com/user-attachments/assets/e853f9c2-9f52-4ad9-8b35-21594a742e74)

![image](https://github.com/user-attachments/assets/d88f06e1-2e86-430c-8f7a-030a0a162b78)


