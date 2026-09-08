# OmeTV-Geolocalizer

Panel flotante para la obtención de IP, geolocalización y captura en tiempo real mediante WebRTC para OmeTV.

---

## Características

- **Interceptación WebRTC:** Intercepta candidatos ICE (`srflx`) para extraer la dirección IP pública del interlocutor en tiempo real.
- **Geolocalización y datos de red:** Muestra país, región, ciudad, proveedor de internet (ISP), idiomas, zona horaria y coordenadas geográficas con botón de copiado rápido.
- **Captura automática de video:** Extrae un fotograma centrado directamente del flujo de video remoto al conectarse.
- **Panel flotante interactivo:** Interfaz oscura, arrastrable por la pantalla y minimizable.
- **Simulador local:** Incluye un entorno de prueba para simular conexiones e interfaces sin necesidad de ingresar a OmeTV.

---

## Guía de Configuración

### 1. Crear una cuenta en IPGeolocation
Ingresa a [https://ipgeolocation.io/](https://ipgeolocation.io/) y crea una cuenta gratuita.

### 2. Copiar tu clave API
Inicia sesión, accede a tu panel de control (Dashboard) y copia tu clave API.

### 3. Configurar el script
Abre el archivo `ometv_console_snippet.js` y reemplaza:

```javascript
let apiKey = "";
```

por:

```javascript
let apiKey = "TU_API_KEY";
```

### 4. Abrir OmeTV
Ve a [https://ome.tv/](https://ome.tv/) e inicia sesión.

### 5. Abrir las Herramientas de Desarrollador
Presiona `F12` o la combinación `Ctrl + Shift + I`.

### 6. Abrir la Consola
Selecciona la pestaña **Console**.

Si el navegador muestra el aviso de seguridad:
> Warning: Don't paste code into the DevTools Console...

escribe:
```text
allow pasting
```
y presiona **Enter**.

### 7. Ejecutar el script
Pega todo el código del script en la consola y presiona **Enter**.

### 8. Comenzar a usar OmeTV-Geolocalizer
Una vez conectado con otro usuario, el panel flotante mostrará automáticamente la información disponible y la captura de video.
