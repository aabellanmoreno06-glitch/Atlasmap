# My Travel Atlas

Tu atlas de viajes personal, en español y con tema oscuro.

## Publicar con GitHub Pages

1. Crea un repositorio en GitHub llamado `my-travel-atlas` (puede ser público o privado; GitHub Pages puede tener limitaciones según tu plan).
2. Sube `index.html` a la raíz del repositorio.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que GitHub Pages publique la web. La dirección aparecerá en esa misma sección.

## Funciones

- Mapa mundial interactivo.
- Búsqueda de países y ciudades.
- Estados Visitado y Wishlist.
- Estadísticas y perfil básico.
- Guardado local en el navegador.
- Importación y exportación de copias JSON.

## Importante sobre privacidad y datos

- Los destinos se guardan en `localStorage` del navegador y dispositivo que uses. No hay cuentas ni sincronización entre dispositivos.
- Para compartir o transferir tus datos, exporta el JSON y compártelo de forma privada. No subas tu copia JSON al repositorio público.
- El mapa usa teselas de CARTO, datos de fronteras de `datasets/geo-countries` y búsqueda de OpenStreetMap/Nominatim; esos servicios externos pueden recibir solicitudes de red.
- Para usar Nominatim, respeta su política de uso: https://operations.osmfoundation.org/policies/nominatim/
