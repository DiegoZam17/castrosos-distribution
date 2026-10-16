# Castrosos — distribución Android

Repositorio público de instaladores y manifiestos firmados de Castrosos. No contiene el código fuente ni datos de usuarios.

## Canal de prueba

La candidata Android 0.21.1 RC4 (código 44) se prepara para validar la distribución desde Castrosos 0.21.1 RC3 (código 43). Conserva las funciones de RC3; no debe interpretarse como una corrección nueva de Google en Windows o una certificación de todos los teléfonos.

Desde Castrosos: Configuración → Actualizaciones → Buscar actualizaciones → descargar e instalar. Android solicita la confirmación final. No desinstalar ni borrar datos para actualizar.

Las APK conservan el paquete `com.castrosos.app` y la firma permanente. El manifiesto usa Ed25519 y caduca; la aplicación rechaza información alterada o caducada.

La prueba pública completa está en curso. Sus resultados y límites se incorporarán a las notas de la versión.
