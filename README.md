# 🎥 Skrynix - Studio Edition for macOS

Skrynix es una aplicación de grabación de pantalla nativa, ultraligera y de alto rendimiento diseñada exclusivamente para macOS. Desarrollada con las últimas tecnologías de Apple (**Swift 6**, **SwiftUI** y **ScreenCaptureKit**), Skrynix permite capturar la pantalla en máxima resolución sin pérdida de calidad, grabando simultáneamente el audio interno del sistema y el micrófono físico del Mac.

A diferencia de otras herramientas pesadas, Skrynix se ejecuta en segundo plano con un impacto mínimo en el procesador, ofreciendo una experiencia fluida incluso durante sesiones de juego intensas o tareas de desarrollo exigentes.

🌍 **Sitio Web Oficial:** [skrynix.weblocalstudio.es](https://skrynix.weblocalstudio.es)  
📦 **Descargar Instalador:** [Últimas Versiones / Releases](https://github.com/weblocalstudio/Skrynix/releases)

---

## ✨ Características Principales

* **🚀 Rendimiento Ultra-HD (4K/Retina):** Captura de vídeo nativa utilizando el códec moderno **HEVC (H.265)**. Olvídate de los vídeos pixelados o corruptos; graba exactamente lo que ven tus ojos.
* **🎙️ Audio Dual Sincronizado:** Captura el audio de tus aplicaciones (juegos, vídeos, llamadas) junto con tu voz a través del micrófono interno o externo en pistas perfectamente acopladas.
* **⏱️ Cronómetro Flotante Global:** Una mini-interfaz flotante te acompaña en la esquina superior de la pantalla. No se oculta al cambiar de aplicación y te mantiene al tanto del tiempo exacto de grabación.
* **⌨️ Atajo de Teclado Global (`⌥ + R`):** Inicia y detiene tus grabaciones al instante desde cualquier lugar del sistema, sin necesidad de abrir paneles molestos o interrumpir lo que estás haciendo.
* **🔒 Sandbox & Privacidad Segura:** Tus grabaciones se procesan de forma local y segura. Gracias a la integración con el sistema de permisos de Apple, tú decides en qué carpeta se guardan tus archivos `.mov`.

---

## 🛠️ Requisitos del Sistema

* **Sistema Operativo:** macOS 15.0 o superior.
* **Arquitectura:** Optimizado para Apple Silicon (M1, M2, M3, M4) y compatible con procesadores Intel.
* **Permisos requeridos:** * Grabación de pantalla y audio del sistema.
  * Acceso al micrófono (para capturar tu voz).
  * Accesibilidad (para el funcionamiento del atajo de teclado global).

---

## 📦 Instalación Rápida

Para instalar Skrynix en tu Mac de forma definitiva, sigue estos sencillos pasos:

1. Ve a la sección de **[Releases](https://.github.com/weblocalstudio/Skrynix/releases)** en la parte derecha de este repositorio.
2. Descarga la versión más reciente del archivo ejecutable empaquetado: `Instalador_Skrynix.dmg`.
3. Haz doble clic sobre el archivo descargado para montar el disco virtual en tu Mac.
4. Arrastra el icono de **Skrynix** directamente dentro de tu carpeta de **Aplicaciones**.
5. Abre la aplicación desde tu Launchpad o Finder por primera vez.

> 💡 **Nota sobre los permisos:** Al abrir la app por primera vez, macOS te solicitará autorización para grabar la pantalla y usar el micrófono. Asegúrate de otorgar los permisos en *Ajustes del Sistema > Privacidad y seguridad* para que todas las funciones se ejecuten correctamente.

---

## ⌨️ Guía de Uso del Atajo Global

Skrynix está pensado para trabajar de manera invisible en tu día a día:

* **Empezar a grabar:** Configura la carpeta de destino y las fuentes de audio desde el panel principal. Luego, minimiza la aplicación o déjala en segundo plano. Pulsa **`Option (⌥) + R`** para arrancar la grabación al instante.
* **Control visual:** Sabrás que estás grabando porque aparecerá la burbuja con el contador de tiempo flotando en tu pantalla de manera fija.
* **Detener y guardar:** Cuando hayas terminado, vuelve a pulsar **`Option (⌥) + R`**. El cronómetro desaparecerá y el archivo de vídeo aparecerá empaquetado directamente en la carpeta seleccionada en formato `.mov` de alta calidad.