Omnitrix Data Explorer 🧬

Este proyecto es una aplicación web interactiva diseñada para explorar y visualizar el conjunto de datos de alienígenas del universo de Ben 10. Permite a los usuarios cargar un archivo CSV con estadísticas, buscar alienígenas específicos y visualizar sus habilidades y niveles de poder mediante una interfaz moderna.

🚀 Características

Carga de Datos Dinámica: Sistema de lectura de archivos CSV local.

Búsqueda Avanzada: Filtrado por nombre, serie o especie en tiempo real.

Visualización de Estadísticas: Representación visual de atributos como:

Combate y Velocidad.

Durabilidad e Inteligencia.

Atributos Elementales (Fuego, Agua, Electricidad, Magia).

Diseño Responsivo: Interfaz adaptada para dispositivos móviles y escritorio utilizando Tailwind CSS.

Arquitectura de Diagrama: Incluye documentación técnica del flujo de datos en formato LaTeX.

🛠️ Tecnologías Utilizadas

Frontend: HTML5, JavaScript (ES6+), CSS3.

Estilos: Tailwind CSS para un diseño ágil y estético.

Documentación Técnica: LaTeX (TikZ) para el diagrama de flujo del sistema.

Procesamiento de Datos: API de FileReader para manejo de archivos locales.

📂 Estructura del Proyecto

index.html: La aplicación principal que contiene la lógica de filtrado y la UI.

diagrama_flujo.tex: Código fuente del diagrama de flujo técnico.

ben10_aliens_dataset.csv: Base de datos de ejemplo con las estadísticas de los alienígenas.

README.md: Este archivo de documentación.

📖 Instrucciones para GitHub

Para subir este proyecto a GitHub, sigue estos pasos:

Crea un nuevo repositorio en GitHub.

En tu carpeta local, guarda este texto como README.md.

Ejecuta los siguientes comandos en tu terminal:

git init
git add .
git commit -m "Initial commit: Omnitrix Explorer"
git branch -M main
git remote add origin [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
git push -u origin main


⚙️ Funcionamiento Interno

El sistema sigue el flujo definido en la documentación técnica:

El usuario proporciona el archivo CSV.

El motor de JavaScript parsea el texto plano, convirtiendo filas en objetos JSON.

Se aplica un filtro de búsqueda sobre el array de objetos.

Los resultados se inyectan en el DOM mediante plantillas de literales (Template Literals).

📝 Notas de Versión

v1.0.0: Lanzamiento inicial con soporte para carga de CSV y visualización de tarjetas básicas.

v1.1.0: Corrección de errores en el diagrama de flujo y optimización del motor de búsqueda.

Desarrollado para entusiastas del Omnitrix y la gestión de datos.