# CV Ejecutivo Interactivo — Dionicio Flores Vilches

Currículum vitae web interactivo de alto impacto visual, diseñado con **Tailwind CSS**, **Glassmorphism**, animaciones táctiles, exportación de **PDF vectorial nativo** (formato Carta con jsPDF), descarga instantánea de **vCard (.vcf)** y compartición mediante **Código QR**.

Optimizado al 100% para teléfonos **Android, iPhone, Tablets (iPad) y PC/Mac**.

---

## 🚀 Guía Rápida para Publicar en GitHub Pages (en 2 minutos)

Tu cuenta de GitHub es: [https://github.com/saxneal-png](https://github.com/saxneal-png)

Tienes **dos opciones** de enlace:

| Opción | Nombre del Repositorio | Enlace Final Resultante |
| :--- | :--- | :--- |
| **Opción A (Recomendada como sección)** | `cv` | `https://saxneal-png.github.io/cv/` |
| **Opción B (Como sitio principal de tu perfil)** | `saxneal-png.github.io` | `https://saxneal-png.github.io/` |

---

### Método 1: Desde la web de GitHub (Sin instalar nada en tu PC)

1. Ingresa a [GitHub - Nuevo Repositorio](https://github.com/new).
2. En **Repository name**, escribe `cv` (o `saxneal-png.github.io`).
3. Asegúrate de marcarlo como **Public** (Público) y haz clic en **Create repository**.
4. En la pantalla que aparece, haz clic en **"uploading an existing file"** (subir un archivo existente).
5. Arrastra y suelta el archivo `index.html` de esta carpeta.
6. Presiona el botón verde **"Commit changes"**.
7. Ve a la pestaña **Settings** (Configuración) del repositorio -> Menú lateral izquierdo **Pages**.
8. En **Build and deployment** > **Source**:
   - Branch: Selecciona `main` (o `master`)
   - Carpeta: `/ (root)`
   - Haz clic en **Save** (Guardar).
9. ¡Listo! En 1 a 2 minutos tu enlace estará activo con candado SSL (HTTPS).

---

### Método 2: Mediante la Terminal / Git

Si prefieres usar Git desde tu terminal:

```bash
cd /Users/dioniciofelipefloresvilches/.gemini/antigravity/scratch/cv-ejecutivo

# 1. Inicializar repositorio local
git init
git add index.html README.md
git commit -m "feat: CV Ejecutivo Interactivo con soporte móvil y PDF"
git branch -M main

# 2. Conectar con tu repositorio en GitHub (creado previamente como 'cv')
git remote add origin https://github.com/saxneal-png/cv.git

# 3. Subir los archivos
git push -u origin main
```

Luego activa GitHub Pages en **Settings > Pages > Branch: main > Save**.

---

## 📱 Características Destacadas Implementadas

- **Navegación Ergonómica Móvil**: Menú dock inferior para pulgares (*thumb-friendly*) en smartphones.
- **Exportación de PDF Vectorial**: Genera un PDF nítido en formato Carta (US Letter) sin depender de impresoras o recortes del navegador.
- **Guardar Contacto Directo (.vcf)**: Los reclutadores o autoridades pueden agregar tus datos directo a la agenda de su teléfono con un toque.
- **Modal con Código QR**: Permite que otra persona escanee tu pantalla para abrir el CV en su propio teléfono de inmediato.
- **Metadatos Open Graph**: Vista previa atractiva con título y descripción ejecutiva al compartir el enlace por WhatsApp o LinkedIn.
- **Ahorro de Batería Inteligente**: Pausa automática de animaciones en pestañas en segundo plano y menor carga gráfica en dispositivos móviles.
