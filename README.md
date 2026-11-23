# BTC Kalshi Pro para iPhone

## Publicar con GitHub Pages
1. Sube todos los archivos de esta carpeta a la raíz de un repositorio público.
2. En GitHub abre **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona **main** y **/(root)**, luego **Save**.
5. Espera a que GitHub Pages publique el sitio. Abre la URL que aparece en esa página desde Safari en tu iPhone.
6. En Safari toca **Compartir → Añadir a pantalla de inicio**.

## Alcance y limitaciones
- El precio y las velas se consultan desde la API pública de Binance (BTCUSDT, 15 minutos).
- Los indicadores son una lectura técnica sencilla, no una probabilidad calibrada ni una predicción garantizada.
- No hay conexión con la cuenta, precios ni API de Kalshi. Introduce/verifica manualmente el precio del contrato en Kalshi.
- No realiza apuestas ni órdenes automáticas.
- El navegador de iPhone puede suspender la app en segundo plano. Esta PWA no garantiza análisis 24/7 ni alertas cuando está cerrada. Para eso se necesita un servicio backend en la nube y un sistema de notificaciones.
- La calculadora es aproximada y no incorpora comisiones, spread ni otras condiciones de Kalshi.
- Los datos requieren internet y disponibilidad de Binance.
