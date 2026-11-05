# Meyveler ve Sebzeler

Kuiz interaktiv për të mësuar emrat e pemëve dhe perimeve në turqisht dhe shqip.

## Nisja lokalisht

Kërkohet Node.js 18 ose më i ri.

```bash
npm install
npm run dev
```

Hap adresën lokale që shfaq Vite në terminal.

Për të provuar versionin e prodhimit:

```bash
npm run build
npm run preview
```

## Publikimi me GitHub dhe Vercel

1. Krijo një repository të ri në GitHub dhe ngarko këta skedarë.
2. Në Vercel, zgjidh **Add New Project** dhe importo repository-n.
3. Vercel zbulon Vite automatikisht. Nëse kërkohet konfigurim, përdor:
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
4. Zgjidh **Deploy**. Publikimet e mëvonshme në degën kryesore bëhen automatikisht pas çdo `git push`.
