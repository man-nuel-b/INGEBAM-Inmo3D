# INGEBAM Inmo3D

Visualizador inmobiliario experimental independiente.

## Estado del repositorio
- Entrada web: `index.html` (visor V10.7).
- El arranque recupera la experiencia desde `premium/` e inyecta módulos `render-quality-v104.js`, `visual-finish-v105.js`, `materials-physical-v106.js` y `runtime-bridge-v107.js`.
- Recursos adicionales en `assets/`.
- El proyecto está separado de Muebles360, Ventanas3D, Cubikeitor y TIMELESS TCO.

## Abrir
En GitHub Pages, si el repositorio tiene Pages activado: https://man-nuel-b.github.io/INGEBAM-Inmo3D/

Para desarrollo local, servir la carpeta con un servidor HTTP (por ejemplo `python -m http.server 8000`) y visitar `http://localhost:8000/`. Evitar abrir `index.html` directamente con `file://` porque la carga usa `fetch`.

## Verificación manual
1. Cargar la raíz y comprobar que el visor sustituye la pantalla inicial.
2. Comprobar que no aparecen errores de carga de recursos o de CORS.
3. Confirmar que controles de cámara, iluminación y materiales continúan funcionando.
4. Revisar versión móvil y consola del navegador.
5. Antes de vender, reemplazar cualquier dato visual o económico demostrativo por información validada.

> Esta documentación no equivale a una certificación de funcionamiento o fotorrealismo.