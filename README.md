# אתר אישי — אביב בן-צבי

אתר תיק עבודות סטטי, בנוי ב-HTML/CSS/JS ללא תלויות חיצוניות (מלבד גופנים מ-Google Fonts).

## מבנה התיקייה

```
aviv-site/
├── index.html          # הקובץ הראשי — כל ה-HTML, ה-CSS וה-JS בפנים
├── assets/
│   ├── aviv-portrait.jpg   # תמונת פנים (600x600, מוטמע מקור 768x1364)
│   └── aviv-logo.png       # לוגו "אביב — בינה ופדגוגיה"
└── README.md
```

## פריסה ב-GitHub Pages

1. צור repository חדש ב-GitHub (לדוגמה: `avivbz/avivbz.github.io` או `aviv-portfolio`)
2. העלה את **תוכן התיקייה `aviv-site`** (לא את התיקייה עצמה) לשורש ה-repo
3. לך ל-**Settings → Pages**
4. תחת "Source" בחר: **Deploy from a branch**, `main` / `(root)`
5. לחץ Save. תוך 1-2 דקות האתר יהיה זמין בכתובת המופיעה.

### דרך מהירה דרך גיט (אם נוח):
```bash
cd aviv-site
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

## טכנולוגיה

- HTML5 סטטי
- CSS עם משתנים (CSS custom properties) — קל לשינוי צבעים בנקודה אחת
- Vanilla JavaScript — ללא ספריות
- Google Fonts: Frank Ruhl Libre (כותרות) + Heebo (גוף)
- רספונסיבי: Desktop / Tablet / Mobile
- RTL מלא, נגישות בסיסית (aria attributes, prefers-reduced-motion)

## עריכה עתידית

- **שינוי פלטת צבעים**: ערוך את `:root { --color-... }` בראש ה-`<style>`
- **הוספת פרויקט חדש**: העתק את הבלוק `<a class="project">` בתוך הקטגוריה הרצויה
- **שינוי טקסטים**: כל הטקסטים בעברית נמצאים ישירות ב-HTML, בלי קבצי תרגום
