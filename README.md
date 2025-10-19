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
   <img width="620" height="363" alt="image" src="https://github.com/user-attachments/assets/fcdb3a58-8ca9-4683-a08c-6179cbf28ca1" />

6. Verificación y ajuste de AndroidManifest.xml.
   <img width="1023" height="764" alt="image" src="https://github.com/user-attachments/assets/f7bfcdd5-db07-49f1-b068-465a897edf51" />

8. Generación del APK:
   ionic build
  npx cap copy
  npx cap open android
9. Luego en Android Studio:
Build > Build APK(s) → se genera en android/app/build/outputs/apk/debug/app-debug.apk.
10.Probar el APK
   <img width="206" height="463" alt="image" src="https://github.com/user-attachments/assets/44dd8795-060d-40e5-bb0f-6d1626db737d" />
  <img width="571" height="1280" alt="image" src="https://github.com/user-attachments/assets/b648928c-26bc-4540-a502-d8419757004f" />
