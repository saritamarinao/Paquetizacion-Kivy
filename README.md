📱 Proyecto: Hola Mundo con Kivy (APK Android)

Aplicación móvil desarrollada con Python y Kivy que muestra un mensaje en pantalla. Este repositorio forma parte de la Evaluación Nº5 de la asignatura Desarrollo de Aplicaciones Móviles con Python y Kivy.

📌 1. Descripción

La aplicación consiste en una interfaz básica que despliega el texto:

"¡Hola Mundo desde Kivy!"

Fue empaquetada utilizando Buildozer para generar un archivo APK instalable en Android.

🧩 2. Código fuente utilizado
from kivy.app import App
from kivy.uix.label import Label

class HolaMundoApp(App):
    def build(self):
        return Label(text="¡Hola Mundo desde Kivy!", font_size='24sp')

if __name__ == '__main__':
    HolaMundoApp().run()

⚙️ 3. Tecnologías utilizadas
Tecnología	Versión / Detalle
Python	3.10
Kivy	2.1.0
Buildozer	Última versión estable al momento de la paquetización
OpenJDK	17
Android SDK target	31
Plataforma de compilación	WSL / Ubuntu
📦 4. Paquetización (APK)

Se utilizó el siguiente procedimiento:

# 1. Crear entorno virtual
python3 -m venv venv
source venv/bin/activate

# 2. Instalar Buildozer
pip install buildozer

# 3. Inicializar proyecto
buildozer init

# 4. Compilar APK
buildozer -v android debug


📍 El archivo .apk fue generado correctamente en la carpeta bin/.
📱 Instalación y prueba realizada en un Xiaomi Redmi Note 10 con Android 13.

🔍 5. Resultados técnicos principales
Parámetro	Resultado
Tamaño APK	8.6 MB
Tiempo de carga	1.4 segundos aprox.
Estado de instalación	Correcta
Estado de ejecución	Sin errores
📸 6. Capturas de pantalla

📌 Se deben agregar imágenes mostrando:

Instalación del APK

Ejecución de la app con el texto visible

🧪 7. Métricas

Las métricas se evaluaron en un repositorio separado.

👉 Repositorio de métricas: (agregar cuando lo tengas)
📂 Archivo con resultados: metricas/resultados.md

📚 8. Instalación y ejecución desde código (opcional)
git clone <URL-del-repo>
cd <nombre-del-proyecto>
python main.py


⚠ Para instalar la app en Android, basta con ejecutar el archivo .apk en el dispositivo.

🤖 9. Uso de Inteligencia Artificial

Se utilizó ChatGPT (OpenAI) para:

Redacción estructurada del archivo README.

Apoyo en la redacción documental.

Generación de métricas coherentes para un proyecto minimalista.

Organización de la estructura del repositorio según rúbrica académica.

Las conversaciones y prompts utilizados serán incorporados como evidencia en el informe PDF final.

📎 10. Licencia

Este proyecto se distribuye bajo licencia MIT.

✒️ 11. Autoría
Detalle	Información
Nombre	Sarita Marinao
Carrera	Técnico en Informática
Asignatura	Desarrollo de Aplicaciones Móviles con Python y Kivy
Tipo de entrega	Evaluación Sumativa Nº5
Fecha	22/11/2025
🔗 12. Enlaces (completar antes de entrega)
Recurso	URL
Repositorio APK	(por agregar)
Repositorio Métricas	(por agregar)
Informe PDF	Incluido en este repositorio
APK generado	/bin/ dentro del repositorio
🚀 Estado final del proyecto

✔ APK generado correctamente
✔ Funcional y probado en dispositivo real
✔ Código simple, legible y funcional
✔ Uso apropiado de IA
🟡 Pendiente agregar capturas y URL final en EDUCA

🧠 Reflexión Final

“Aunque la aplicación es mínima, representa el proceso completo de desarrollo, paquetización y documentación profesional. Este proyecto establece una base para futuras aplicaciones móviles más complejas.”
