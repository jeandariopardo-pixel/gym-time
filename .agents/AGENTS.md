# Reglas del Proyecto (Gym Time)

## Despliegue y Control de Versiones en GitHub

Cuando se genere una nueva versión del proyecto con Antigravity / CLI:

1. **Ruta y Nombre de Archivos Estables**:
   * No cambies la ruta ni el nombre del archivo principal que la app usa.
   * Mantén siempre el archivo principal con el nombre `Gym_Time_ultra_pro.html` en la rama `main` y en la misma ubicación.
   * La app debe usar siempre una URL fija del tipo: `https://raw.githubusercontent.com/TU-USUARIO/TU-REPO/main/Gym_Time_ultra_pro.html`.
   * Los cambios deben ser confirmados (commit) y subidos (push) sobre ese mismo archivo. El enlace no debe cambiar.

2. **Enlaces Estables para Releases (Descargas)**:
   * Mantén siempre el mismo nombre de archivo para el archivo empaquetado en las releases, por ejemplo: `app-gym-time.zip`.
   * Crea releases incrementales (v1, v2, v3...), pero asegurando que el asset adjunto siempre se llame exactamente `app-gym-time.zip`.
   * La app debe usar esta URL fija y estable para descargas: `https://github.com/TU-USUARIO/TU-REPO/releases/latest/download/app-gym-time.zip`.

3. **Control Interno de Versión en la UI**:
   * La indicación de la versión (ej. "v1", "v2", "v3") no debe modificar las URLs de descarga ni de carga.
   * El número de versión se actualiza modificando directamente el texto interno en el código/JSON/configuración de la UI (ej. "Versión actual: v3"), dejando los enlaces estables.
