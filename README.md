# SSS Luxury Parfum

Premium atirlar katalogi (bitta `index.html` fayl, qo‘shimcha dasturlar kerak emas).

## GitHub Pages orqali ishga tushirish
1. GitHub’da yangi repository oching (masalan `sss-luxury-parfum`).
2. `index.html`, `README.md` va `.nojekyll` fayllarini repositoryga yuklang (Add file → Upload files).
3. **Settings → Pages** bo‘limiga kiring.
4. **Source**: `Deploy from a branch`, **Branch**: `main`, papka: `/ (root)` → **Save**.
5. 1–2 daqiqadan keyin sayt `https://<username>.github.io/<repo-nomi>/` manzilida ochiladi.

## Nimani o‘zgartirish mumkin
`index.html` ichida `SOZLAMALAR` degan joyni toping:
- `TG_USER` — Telegram username
- `IG_USER` — Instagram username
- `PRODUCTS` — atirlar ro‘yxati (`p10` — 10 ml narxi, so‘mda)
- `MULT` — 20, 30, 50, 100 ml narxlari 10 ml narxiga nisbatan koeffitsiyenti
- `FEATURED` — "Ko‘p so‘raladigan atirlar" qatoridagi atirlar

Rasmlar `IMG` ichida base64 shaklida joylashgan.
