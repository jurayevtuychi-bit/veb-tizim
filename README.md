# Veb Tizimlari — Interaktiv Mobil Ilova va GitHub Actions APK Yig'uvchi

Ushbu repozitoriy **"Veb Tizimlari"** fani bo'yicha oliy ta'lim muassasalari talabalari va IT mutaxassislari uchun yaratilgan professional interaktiv o'quv platformasi hamda Android APK mobil ilovasini avtomatik yig'ish (CI/CD) to'plamidir.

---

## 📌 Ilova Tarkibi va Imkoniyatlari:
1. **8 ta Asosiy Modul va 15 ta To'liq Nazariy Mavzu:**
   - **I Modul:** Veb tizimlariga kirish va Veb arxitekturasi (Mavzu 1, 2)
   - **II Modul:** Frontend asoslari — HTML5 va CSS3 (Mavzu 3, 4)
   - **III Modul:** Dinamik veb — JavaScript va React.js (Mavzu 5, 6)
   - **IV Modul:** Backend va Ma'lumotlar bazalari — Node.js, Express, SQL va MongoDB (Mavzu 7, 8)
   - **V Modul:** API tizimlari va Autentifikatsiya — RESTful API, GraphQL va JWT/OAuth (Mavzu 9, 10)
   - **VI Modul:** Veb xavfsizlik va Joylashtirish — XSS, CSRF, SQLi va CI/CD (Mavzu 11, 12)
   - **VII Modul:** Real vaqt aloqasi va PWA — WebSocket, Socket.IO va PWA (Mavzu 13, 14)
   - **VIII Modul:** Testlash, Optimallashtirish va Mustaqil amaliy loyihalar (Mavzu 15 + 5 ta loyiha)
2. **Qat'iy O'quv Ketma-Ketligi va Test Nazorati:**
   - 1-modul testini **100%** bajarmaguncha 2-modul ochilmaydi;
   - 2-modul 100% -> 3-modul;
   - 3-modul 100% -> 4-modul;
   - 4-modul 100% -> 5-modul;
   - 5-modul 100% -> 6-modul;
   - 6-modul 100% -> 7-modul;
   - 7-modul 100% -> 8-modul;
   - 8-modul 100% -> Yakuniy Nazorat Testiga ruxsat beriladi.
3. **Yakuniy Nazorat Testi (15 ta Savol):**
   - Barcha 8 ta modul 100% natija bilan yakunlangach faollashadi.
4. **Foydalanuvchi Shaxsiy Kabineti:**
   - Talaba ismi, familiyasi, OTM, guruhi, talaba ID raqami;
   - 9 bosqichli to'liq progress monitoringi va individual test natijalari;
   - Natijalarni mahalliy saqlash (`localStorage`) va qayta tiklash.
5. **Rasmiy Akademik Sertifikat:**
   - Yakuniy testdan 100% o'tgach faollashuvchi, QR-kodli, muhrli unikal sertifikat;
   - Canvas orqali yuqori aniqlikdagi **PNG formatida yuklab olish** va **Chop etish (Print)** imkoniyati.
6. **12 ta Virtual Laboratoriya va Interaktiv Simulyatorlar:**
   - HTTP so'rovlar, HTML5 Form validatori, Flexbox/Grid studiyasi, JS Event Loop, React VDOM, Express Middleware, SQL vs MongoDB, REST vs GraphQL, JWT Debugger, XSS/SQLi Xavfsizlik laboratoriyasi, WebSocket chat va PWA oflayn kesh studiyasi.
7. **Moslashuvchan Shrift O'lchami:**
   - 85%, 100%, 115% va 130% kattalashtirish imkoniyati.
8. **Oq-havorang (White-Cyan) Elegant Dizayn:**
   - Zamonaviy Glassmorphism UI va geometrik naqshli orqa fon.

---

## 🚀 GitHub Actions orqali APK Yig'ish Yo'riqnomasi:
1. Ushbu ZIP arxivini yuklab oling va kompyuteringizda oching;
2. GitHub da yangi repozitoriy oching (masalan, `veb-tizimlari-app`);
3. Barcha fayllarni repozitoriyning `main` branchiga yuklang (push);
4. Repozitoriyingizdagi **Actions** bo'limiga o'ting — **Build Android APK** workflow avtomatik tarzda Java 21 va Gradle 8 orqali APK ni yig'ishni boshlaydi;
5. Qurilish tugallangach (taxminan 3-4 daqiqa), **Artifacts** bo'limidan tayyor `VebTizimlari-APK.zip` ni yuklab olib, Android telefoningizga o'rnating!
