SURSAATHI — Hinglish Singing Practice PWA

FILES
- index.html: app
- manifest.json: install/app metadata
- sw.js: offline cache
- icons/: app icons

IMPORTANT
PWA install prompt/service worker offline mode ke liye website ko HTTPS hosting par serve karna zaroori hai. ZIP ko seedha extract karke index.html kholne par app chal sakti hai, lekin browser install aur offline PWA features available nahi honge. MDN reference: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Making_PWAs_installable

EASIEST WAY (GitHub Pages)
1. GitHub par sign in karke ek naya repository banao, e.g. sursaathi.
2. Is ZIP ko extract karo aur andar ki files/folders repository ke root mein upload karo (ZIP ko as-is upload mat karna).
3. Repository Settings > Pages kholo.
4. "Deploy from a branch" select karo, branch "main", folder "/ (root)", phir Save.
5. GitHub Pages jo HTTPS website URL de, usse phone aur laptop dono par kholo.
6. Android/desktop Chrome ya Edge mein browser menu se "Install app" / "Install SurSaathi" select karo.
7. iPhone par Safari mein Share > Add to Home Screen use karo.

PHONE AUR LAPTOP
- Dono devices par same published HTTPS URL kholna.
- Har device par install separately karna.
- App class/homework progress usi device ke browser mein save hoti hai; devices ke beech sync abhi included nahi hai.

FEATURES
- 30 Hinglish lessons and homework popups
- Virtual synthesized keyboard, metronome, simple drone
- Progress tracking using local browser storage
- Basic offline cache after first successful online load

LIMITATIONS
- Keyboard/drone sounds synthesized hain, real harmonium/tanpura recordings nahi.
- Automatic voice pitch analysis, cloud sync, accounts, push reminders aur real audio lessons abhi included nahi.
