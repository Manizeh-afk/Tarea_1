# HappyBirthday

Aplicación Android de una tarjeta de cumpleaños, construida con Kotlin y Jetpack Compose.

## Requisitos

- Android Studio con soporte para proyectos Gradle y Kotlin.
- JDK 17 o superior.
- Android SDK instalado (el proyecto configura compileSdk 37 y minSdk 24).

## Abrir y ejecutar

1. Clona el repositorio y abre la carpeta del proyecto en Android Studio.
2. Espera a que Gradle sincronice las dependencias.
3. Ejecuta la configuración `app` en un emulador o dispositivo con Android 7.0 (API 24) o superior.

También puedes compilar el APK de depuración desde la raíz del proyecto:

```bash
./gradlew assembleDebug
```

En Windows:

```powershell
.\gradlew.bat assembleDebug
```

La tarjeta se implementa en `app/src/main/java/com/example/happybirthday/MainActivity.kt`; la imagen y la fuente están en `app/src/main/res`.
