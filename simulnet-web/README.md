# Sistemas Simulnet — sitio web

Sitio estático (HTML, CSS y JavaScript sin dependencias), listo para Vercel.

## Contenido

```
simulnet-web/
├── index.html      Página completa
├── img/            Imágenes optimizadas (.webp)
├── favicon.svg     Ícono de la pestaña
├── vercel.json     Configuración (URLs limpias y caché de imágenes)
└── robots.txt
```

## Publicar en Vercel

**Opción A — desde el navegador**
1. Entra a vercel.com → Add New → Project.
2. Importa el repositorio de GitHub que contenga esta carpeta (o súbela con "Deploy" arrastrando la carpeta).
3. Framework Preset: **Other**. Build Command y Output Directory: vacíos.
4. Deploy.

**Opción B — desde la terminal**
```
npm i -g vercel
cd simulnet-web
vercel          # vista previa
vercel --prod   # producción
```

## Dominio

En el proyecto de Vercel: Settings → Domains → agrega `simulnet.com` y `www.simulnet.com`, y configura en tu proveedor de dominio los registros DNS que Vercel indique.

## Datos a revisar antes de lanzar

- Formulario: arma el mensaje y abre el correo del visitante hacia info@simulnet.com. Para recibir solicitudes automáticamente, conéctalo a un servicio de formularios (por ejemplo Formspree) o a una función de Vercel.
- Logo: es una recreación vectorial; reemplázala por el archivo oficial cuando lo tengas.
