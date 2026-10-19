# YDS.tn

الموقع ملفّات منفصلة. **ما تحطّش** نسخة فيها `data:image` / `data:video` (5MB+) على GitHub — الواجهة تظهر `index.html` فاضي خاطر الملف أكبر من اللي GitHub يعرضو.

## الملفات

```
index.html          ← الكود (حوالي 135 KB — يظهر على GitHub)
images/             ← الصور
videos/             ← الفيديو
```

## كيفاش ترفع على GitHub

1. امسح `index.html` الفاضي من الريبو إن كان موجود.
2. ارفع **المجلد كامل**: `index.html` + `images/` + `videos/`.
3. ما تلصّقش محتوى الملف في المحرّر متاع github.com — الملف الكبير يتمسّح.
4. من التيرمينال:

```bash
git add index.html images videos
git commit -m "YDS site"
git push
```

GitHub Pages: Settings → Pages → Deploy from branch → `/` (root). الرابط يولي `https://USER.github.io/REPO/`

WhatsApp: `+216 94 508 504`
