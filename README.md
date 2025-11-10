# Poker Tracker - Legal Website

אתר מדיניות פרטיות ותנאי שימוש עבור אפליקציית Poker Tracker.

## הוראות פריסה ל-Vercel

### שלב 1: צור repository ב-GitHub
1. לך ל-GitHub.com
2. לחץ על "New repository"
3. תן שם: `poker-tracker-legal`
4. בחר Public (או Private - שניהם עובדים)
5. לחץ על "Create repository"

### שלב 2: העלה את הקבצים
```bash
cd /Users/omersavransky/pok/legal-website
git init
git add .
git commit -m "Initial commit: Legal website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/poker-tracker-legal.git
git push -u origin main
```

### שלב 3: חבר ל-Vercel
1. לך ל-[Vercel.com](https://vercel.com) והתחבר (או הירשם)
2. לחץ על "Add New" → "Project"
3. ב אימפורט Git Repository - חפש את `poker-tracker-legal`
4. לחץ על "Import"
5. השאר את כל ההגדרות כברירת מחדל
6. לחץ על "Deploy"

### שלב 4: קבל את ה-URL
לאחר הפריסה, תקבל URL כמו:
`https://poker-tracker-legal.vercel.app`

### שלב 5: עדכן את האפליקציה
עדכן את ה-URLs בקוד האפליקציה:
- `SettingsView.swift`
- `WelcomeView.swift` (אופציונלי)

החלף את `YOUR_VERCEL_URL` ב-URL שקיבלת.

## קבצים באתר
- `index.html` - עמוד ראשי
- `privacy-policy.html` - מדיניות פרטיות
- `terms-of-service.html` - תנאי שימוש
- `styles.css` - עיצוב
- `vercel.json` - הגדרות Vercel

## עדכון התוכן
כדי לעדכן את המסמכים:
1. ערוך את הקבצים המתאימים
2. `git add .`
3. `git commit -m "Update legal documents"`
4. `git push`

Vercel יפרוס אוטומטית את השינויים תוך דקות!

## תמיכה
לשאלות: support@pokertracker.app
