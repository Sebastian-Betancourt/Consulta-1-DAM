#Consulta-1-DAM
 🚀 Descripción
Aplicación desarrollada con Ionic Angular que incluye:
- Icono personalizado.
- Splash Screen.
- Configuración de AndroidManifest.xml.
- APK funcional generado.
- 
  ⚙️ Pasos realizados
1. Creación del proyecto:
   ionic start consulta tabs --type=angular
2. Añadida plataforma Android:
   ionic capacitor add android
3. Generación de iconos y splash personalizados:
   npm install @capacitor/assets
   npx capacitor-assets generate
4. Crear carpeta resources y poner el icon y splash
6. Verificación y ajuste de AndroidManifest.xml.
7. Generación del APK:
   ionic build
  npx cap copy
  npx cap open android
8. Luego en Android Studio:
Build > Build APK(s) → se genera en android/app/build/outputs/apk/debug/app-debug.apk.
<img width="1024" height="1024" alt="icon" src="https://github.com/user-attachments/assets/fda3ec64-c0dc-4c21-8257-2d4e46d50d42" />

