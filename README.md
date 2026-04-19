DOY0101-EP1-Proyecto-DevOps
Estrategia de Ramificación: Trunk-Based Development
Elegimos Trunk-Based Development para este encargo. A diferencia de GitFlow, esta estrategia fomenta la integración continua al implementar ramas de corta duración, lo que nos permite agilizar el despliegue y evitar conflictos en los merges. Es la metodología más eficiente para nuestro equipo, ya que aumenta la trazabilidad del código y agiliza el flujo colaborativo en la nube.

Estructura del Proyecto
/ (Raíz)
├── .github/workflows/ci.yml  # Pipeline de CI/CD
├── README.md                 # Documentación
└── [Código del Microservicio]
Convenciones de Commits
Utilizamos los siguientes prefijos para estandarizar el historial:
feat: Para nuevas funcionalidades o cambios.
fix: Para corrección de errores.
docs: Para cambios exclusivos en documentación.

Estrategias de Revisión
Todo cambio debe ser realizado en una rama feature/ o hotfix/. Para integrar código a develop, se debe abrir un Pull Request que obligatoriamente debe ser revisado y aprobado por el otro integrante del equipo.

Declaración de uso de IA
Para este proyecto utilizamos herramientas de IA para estructurar el pipeline de GitHub Actions y redactar borradores de la documentación técnica. Las reflexiones finales fueron redactadas manualmente.

Conclusiones y Reflexiones Individuales
Reflexión de Kevin:
Esta primera evaluación me enseñó que el desarrollo DevOps no es solo técnico, sino que tiene una base en la comunicación. Trabajar junto a Valeria me permitió ver lo importante que son los Pull Requests como una herramienta de revisión y aprendizaje mutuo, más que como un paso administrativo. Enfrentar los conflictos al hacer merge me obligó a ser más ordenado con mis commits y a coordinar cada cambio, lo que mejoró nuestro resultado final comparado a nuestros trabajos del semestre pasado.

Reflexión de valeria:
Mi desafío principal del encargo fue mantener el orden en el flujo de trabajo. Hubo momentos donde nos confundimos con las ramas, pero esto me ayudó a comprender con mayor detalle el uso de la terminal y como git gestión los errores. Esta experiencia me ayudó a valorar la automatización (CI/CD) no solo como un requisito, sino como una necesidad real para evitar complicaciones o errores humanos a futuro.
