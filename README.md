# Conecta — prototipo inicial

Abre `index.html` en un navegador moderno. Permite escribir mensajes y grabar/reproducir notas de voz en el mismo dispositivo.

## Importante
Esta primera versión es un prototipo local: guarda los mensajes en el almacenamiento del navegador. **Todavía no sincroniza conversaciones entre dos personas ni entre dispositivos.**

Para convertirla en una aplicación real de mensajería habrá que añadir:
1. Firebase Authentication para cuentas e inicio de sesión.
2. Cloud Firestore para mensajes en tiempo real.
3. Firebase Storage para guardar audios.
4. Reglas de seguridad para que cada usuario solo acceda a sus conversaciones.

La grabación de audio requiere permiso de micrófono y normalmente funciona en `localhost` o en un sitio HTTPS.
