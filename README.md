# Chasu Atelier - Sitio Web

## Estructura del proyecto

```
├── index.html          ← Página principal
├── styles.css          ← Estilos (paleta Navy/Pink/Beige)
├── script.js           ← Interactividad (menú, animaciones)
├── assets/
│   ├── logo.png        ← Tu logo de Chasu Atelier
│   └── patterns/       ← PDFs de patrones descargables
│       ├── flor-cerezo.pdf
│       ├── corona-hojas.pdf
│       └── mariposa-monarca.pdf
└── README.md
```

## Cómo personalizar

### 1. Logo
Coloca tu imagen del logo en `assets/logo.png`

### 2. Videos de YouTube
En `index.html`, busca `VIDEO_ID_1`, `VIDEO_ID_2`, `VIDEO_ID_3` y reemplázalos con los IDs reales de tus videos de YouTube.

El ID es la parte después de `v=` en la URL del video:
- URL: `https://www.youtube.com/watch?v=abc123`
- ID: `abc123`

### 3. Patrones PDF
Coloca tus archivos PDF en la carpeta `assets/patterns/` con los nombres:
- `flor-cerezo.pdf`
- `corona-hojas.pdf`
- `mariposa-monarca.pdf`

O cambia los nombres en el HTML según tus archivos.

### 4. Redes sociales
En el footer, reemplaza los `href="#"` de Instagram, YouTube y Pinterest con tus URLs reales.

### 5. Newsletter
El formulario actualmente muestra un alert. Para conectarlo a un servicio real:
- **Mailchimp**: Reemplaza el `action="#"` del form con tu URL de Mailchimp
- **ConvertKit**: Usa su formulario embebido

## Cómo subir a GoDaddy

1. Entra a tu panel de GoDaddy
2. Ve a "Hosting" → "File Manager" (o usa FTP)
3. Sube TODOS los archivos a la carpeta `public_html/`
4. Asegúrate de mantener la estructura de carpetas (assets/, etc.)

## Integración futura con Amazon

La sección "Tienda" está preparada como placeholder. Cuando estés lista para conectar con Amazon:
- Puedes agregar enlaces directos a tus productos de Amazon
- O integrar la API de Amazon Associates para mostrar productos dinámicamente
