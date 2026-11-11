# 🏴‍☠️ Pirate Token App — Community Edition

![Version](https://img.shields.io/badge/Versión-1.0.0-F59E0B?style=for-the-badge)
![Platform](https://img.shields.io/badge/Plataforma-Android-10B981?style=for-the-badge&logo=android)
![Framework](https://img.shields.io/badge/Hecho_con-Flutter-02569B?style=for-the-badge&logo=flutter)
![Author](https://img.shields.io/badge/Dev-@AngelForester20-black?style=for-the-badge&logo=x)

**Pirate Token App** es una aplicación *companion* creada para la comunidad de **Fortnite** que permite llevar el registro exacto de cofres saqueados, tiempo de juego verificado, progreso del botín pirata y generar una **X Card (Gamer Card)** lista para compartir en redes sociales.

---

## ✨ Características Principales

* **⏱️ Tracker de Partida y Cofres:**
  * Cronómetro integrado para medir la duración de tus sesiones.
  * Pad táctil con respuesta háptica para sumar cofres (`+1`, `+5`, `+10` o `-1`) sin distraerte de la partida.
  * Registro histórico de cofres, partidas jugadas y nivel de cuenta de temporada.
* **🛡️ Sistema Anti-Cheat de Horas (Cap Verificado):**
  * Calcula automáticamente el límite matemático de horas posibles desde el inicio del evento (**1 de Noviembre de 2026**), evitando que se ingresen tiempos de juego irreales en las tarjetas compartidas.
* **📦 Gestor de Botín Híbrido (12 Recompensas):**
  * **7 Coleccionables Únicos (Checklist):** Seguimiento de skins, herramientas, vehículos, calcomanías y los Tokens de Acceso a la Tienda Pirata (2026 y 2027)[cite: 1].
  * **5 Consumibles Grises (Acumulables Infinitos):** Contadores independientes para Fuego Artificial Dorado, Acelerador de Extracción, Extractor Portátil y Localizadores[cite: 1].
* **🪪 Generador de X Card (Modo Captura Limpia):**
  * Tarjeta resumen con tu **ID de Fortnite**, tu **usuario de X (`@Usuario`)**, nivel de cuenta y cálculo automático de **Rango Pirata** (*Grumete Novato*, *Saqueador del East Blue*, *Corsario Supernova*, *Comandante Yonko* y *Rey de los Piratas*).
  * Al tocar el botón **Modo Captura X**, se ocultan las barras de navegación para tomar un *screenshot* limpio.
* **💾 Persistencia Local con SQLite:**
  * Todos tus datos se guardan automáticamente en la memoria interna de tu dispositivo (100% offline y sin requerir inicio de sesión en tu cuenta de Epic Games).

---

## 🏆 Catálogo de Botín Soportado

| Recompensa | Tipo en la App | Categoría |
| :--- | :--- | :--- |
| **A$AP Rocky de Oro Macizo** | Checklist Único | Skin Épica |
| **Guanteletes de Oro Macizo** | Checklist Único | Herramienta |
| **Saqueo en el Paraíso** | Checklist Único | Pantalla de Carga |
| **Mercedes-AMG G 63 'G-Wagon'** | Checklist Único | Vehículo |
| **Tripulación Llama Dorada** | Checklist Único | Calcomanía |
| **Acceso Tienda Pirata (2026)** | Checklist Único | Token Pirata |
| **Acceso Tienda Pirata (2027)** | Checklist Único | Token Pirata |
| **Fuego Artificial Dorado** | Contador Acumulable (`+/-`) | Consumible Gris |
| **Acelerador de Extracción** | Contador Acumulable (`+/-`) | Consumible Gris |
| **Extractor Portátil** | Contador Acumulable (`+/-`) | Consumible Gris |
| **Localizador de Espíritus** | Contador Acumulable (`+/-`) | Consumible Gris |
| **Localizador de la Suerte** | Contador Acumulable (`+/-`) | Consumible Gris |

---

## 📲 Cómo Descargar e Instalar el APK (Usuarios de Android)

1. Ve a la sección de [**Releases**](../../releases) de este repositorio.
2. Descarga el archivo **`Pirate_Token_App_v1.0.apk`** (o `app-arm64-v8a-release.apk`).
3. Abre el archivo descargado en tu teléfono Android.
4. **Nota sobre Google Play Protect:** Al ser una aplicación independiente de la comunidad (fuera de la Play Store), Android puede mostrar un aviso preventivo. Simplemente toca en **"Más detalles"** y luego en **"Instalar de todas formas"**.

---

## 🛠️ Compilar desde el Código Fuente (Desarrolladores)

Si deseas clonar este repositorio y compilar el proyecto por tu cuenta:

```bash
# 1. Clonar el repositorio
git clone [https://github.com/TU_USUARIO_GITHUB/pirate_token.git](https://github.com/TU_USUARIO_GITHUB/pirate_token.git)
cd pirate_token

# 2. Instalar dependencias
flutter pub get

# 3. Ejecutar en modo debug
flutter run

# 4. Compilar APK ligero de lanzamiento
flutter build apk --release --split-per-abi

```

---

# 📋 Historial de Versiones (Changelog) 

v1.0.0 — Community Edition (Lanzamiento Oficial)
Lanzamiento inicial para la comunidad de X.

* **Implementación de X Card con modo de captura limpia y rangos dinámicos.**

* **Separación de los 7 ítems únicos y 5 consumibles grises acumulables.**

* **Algoritmo verificador de horas máximas desde el 1 de Noviembre de 2026.**

* **Base de datos local con sqflite.**

---

# 👨‍💻 Autor y Soporte

**Desarrollado por Ángel Misael Villegas García.**

**X (Twitter): @AngelForester20**

**¿Encontraste algún bug o tienes una idea para la versión v1.1.0? ¡Mándame un DM o mencióname en X con la captura de tu X Card!**

---

```bash
Aviso Legal: Esta es una aplicación no oficial creada por fans para la comunidad. No está afiliada, respaldada ni patrocinada por Epic Games, Inc.
