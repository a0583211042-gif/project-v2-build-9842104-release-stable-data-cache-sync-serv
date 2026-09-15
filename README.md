# סינכרון — גרסה 2 — בנייה מחדש

מערכת קבוצתית בעברית, מותאמת לנייד ולמחשב, עם חיבור קיים ל-Firebase Firestore.

## מבנה
- `index.html` — האפליקציה הראשית.
- `board.html` — כתובת תאימות שמפנה ללוח השבועות.
- `personal.html` — כתובת תאימות שמפנה לאזור האישי.
- `chat.html.html` — כתובת תאימות שמפנה לצ'אט.

המערכת שומרת על מסמכי הענן הקיימים:
- `groupData/קודי הגדרות` (עם fallback ל-`groupData/configCodes`)
- `groupData/customTopics`
- `groupData/metaMeta`
- `groupData/chatRoom`
- `userCodes` (לתאימות)
