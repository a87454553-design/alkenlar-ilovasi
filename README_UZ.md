# Alkenlar — o‘rnatiladigan web-ilova (PWA)

## Fayllar
- `index.html` — ilova interfeysi va dars materiallari
- `manifest.webmanifest` — ilovani bosh ekranga o‘rnatish sozlamalari
- `sw.js` — kesh va oflayn ochilish uchun service worker
- `icon.svg` — ilova belgisi

## Muhim
PWA sifatida o‘rnatish uchun fayllar HTTPS manzilda joylashtirilishi kerak (localhost ham ishlab chiqish uchun ishlaydi). ZIP faylning o‘zini telefonga yuklab olishning o‘zi avtomatik o‘rnatmaydi.

## Eng sodda bepul joylashtirish usuli
1. Kompyuterda yoki telefonda GitHub hisobiga kiring.
2. Yangi repository yarating (masalan, `alkenlar-ilovasi`).
3. Ushbu ZIP ichidagi fayllarni repository ildiziga yuklang.
4. Repository → Settings → Pages bo‘limiga kiring.
5. Build and deployment ichida `Deploy from a branch`, branch `main`, folder `/ (root)` ni tanlang va Save bosing.
6. GitHub sizga `https://...github.io/alkenlar-ilovasi/` kabi manzil beradi.

## Telefonga o‘rnatish
### iPhone (Safari)
1. Joylashtirilgan HTTPS manzilni Safari’da oching.
2. Share (Ulashish) tugmasini bosing.
3. `Add to Home Screen` / `Bosh ekranga qo‘shish` ni tanlang.
4. Add tugmasini bosing.

### Android (Chrome)
1. HTTPS manzilni Chrome’da oching.
2. Menyu (⋮) → `Install app` yoki `Add to Home screen` ni bosing.
3. Tasdiqlang.

Ilova hozircha veb-PWA. Bu App Store yoki Google Play’dagi alohida do‘kon ilovasi emas.
