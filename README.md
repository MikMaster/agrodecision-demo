# AgroDecisión — demostración ejecutiva (concepto de producto)

Esta carpeta contiene una **demo independiente** de una futura solución de análisis gerencial agropecuario. **No es el sistema completo TPT Agriculture ni incluye sus módulos internos.** Fue diseñada para una conversación comercial preliminar con propietarios y administradores.

## Qué funciona

- Selector entre dos explotaciones ficticias.
- Indicadores y gráfico interactivo con tres meses de cifras ilustrativas.
- Indicador de uso de capacidad instalada.
- Comparación de dos escenarios de inversión con valores editables.
- Listado de movimientos de ejemplo de solo lectura.
- Pantalla que explica qué se ofrecería en un diagnóstico remunerado.

## Limitaciones intencionales

- Sin bases de datos, usuarios, contratos, nómina, inventario ni sincronización.
- Sin almacenamiento en servidores, telemetría ni solicitudes de red externas desde el código de esta demo.
- No permite registrar datos de una empresa real. Las cifras están inventadas y no sustituyen un análisis financiero.
- Los cálculos muestran únicamente financiación inicial, efectivo restante y reserva de liquidez. No calculan ROI, VAN, TIR ni rentabilidad.
- El nombre AgroDecisión es provisional y no constituye una denominación comercial verificada.

## Publicar gratis en GitHub Pages

1. Inicia sesión en GitHub y crea un repositorio **público nuevo** llamado, por ejemplo, `agrodecision-demo`. No subas el código completo de TPT Agriculture a ese repositorio.
2. Sube exclusivamente `index.html`, `.nojekyll` y este `README.md` a la raíz del nuevo repositorio.
3. Ve a **Settings → Pages**. En **Build and deployment** selecciona **Deploy from a branch**, rama `main`, carpeta `/(root)` y guarda.
4. La dirección de la demo será la que GitHub muestre en Pages (habitualmente `https://USUARIO.github.io/agrodecision-demo/`). **No se genera automáticamente un enlace real hasta publicar el repositorio.**
5. Comprueba el funcionamiento desde una ventana privada del navegador y un teléfono antes de compartirlo.

**Ojo:** Pages es público, incluso cuando un plan de pago permite alojar la fuente en un repositorio privado. No colocar información confidencial ni secretos en el HTML/JS.

## Ejecutar localmente

Abre `index.html` en tu navegador. No requiere npm, Node, Rust, GitHub ni instalación de dependencias.
