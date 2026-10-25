# Criminalística: Procesa la Escena

Sitio estático en HTML, CSS y JavaScript listo para desplegar en Vercel.

## Publicar en Vercel

### Opción 1: desde el navegador
1. Descomprime este proyecto.
2. Entra en https://vercel.com/new e inicia sesión.
3. Importa un repositorio Git que contenga estos archivos, o usa la opción de despliegue disponible en tu cuenta.
4. Deja el framework como **Other** y la configuración de build vacía; la página está en `index.html` en la raíz.
5. Pulsa **Deploy**.

### Opción 2: con la CLI de Vercel
Necesitas Node.js y Git/npm instalados.

```bash
npm install -g vercel
cd criminalistica-vercel
vercel
```

Para publicar en producción:

```bash
vercel --prod
```

No necesita `npm install`, compilación ni variables de entorno.
