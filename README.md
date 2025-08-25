# Bikeshared – Marketplace (Next.js 14 + Stripe + Tailwind)

Proyecto generado automáticamente a partir de tu pedido de modernización.
Si nos compartes el ZIP original (no RAR) puedo integrar tus assets reales. (No se pudo extraer el RAR: BadZipFile('File is not a zip file'))

## Requisitos
- Node 18+
- Cuenta de Stripe (modo test)

## Pasos
1. **Instalar** dependencias:
   ```bash
   npm install
   ```
2. **Configurar** variables:
   ```bash
   cp .env.example .env.local
   # Rellena STRIPE_SECRET_KEY y NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY
   ```
3. **Desarrollo**:
   ```bash
   npm run dev
   ```
4. **Despliegue** (recomendado Vercel):
   - Añade las variables de entorno en el dashboard del proyecto.
   - `NEXT_PUBLIC_BASE_URL` con tu dominio.

## Dónde pegar tus assets
- Coloca imágenes en `public/` (por ejemplo, `public/bikes/*.jpg`).
- El héroe usa `public/hero-placeholder.jpg` (puedes reemplazarlo por tu imagen).
- Los productos están en `data/products.json`.

## Persistencia y usuarios (opcional)
- Activa Supabase y reemplaza el listado en memoria por consultas reales.