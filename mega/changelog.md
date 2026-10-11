# Novedades — MegaDownloader 4.0.0 Beta

Primera beta de la nueva aplicación independiente MegaDownloader 4 para Windows 10 y Windows 11.

## Incluye

- Aplicación autocontenida para Windows x64; no requiere instalar .NET por separado.
- Descarga de enlaces públicos de MEGA para archivos y carpetas.
- Cola persistente con inicio, pausa, reanudación y cancelación individual, además de historial.
- Ajustes de descargas simultáneas, conexiones por archivo, límite global de velocidad y reintentos.
- Extracción automática de ZIP, 7z, RAR y TAR, con solicitud de contraseña para archivos protegidos.
- Detección opcional de enlaces MEGA copiados al portapapeles.
- Interfaz en español e inglés, temas claro y oscuro, métricas y progreso en la barra de tareas.
- Integración opcional de Psiphon y VLC portable.
- Enlaces directos temporales servidos localmente mientras MegaDownloader permanece abierto.

## Consideraciones de esta beta

- La aplicación solo procesa enlaces públicos; no incluye inicio de sesión en cuentas MEGA.
- Un enlace directo generado por la app es local y temporal, no una URL CDN pública.
- La cuota de transferencia mostrada es tráfico contabilizado por la aplicación; no representa la cuota oficial restante de MEGA.
- Proxy, RSS, control web remoto, claves precompartidas, DLC y cuentas ELC todavía no están disponibles.

## Distribución

MegaDownloader 4 se distribuye únicamente como archivo ZIP. La configuración y la cola se conservan en `%LOCALAPPDATA%\MegaDownloaderNext`.
