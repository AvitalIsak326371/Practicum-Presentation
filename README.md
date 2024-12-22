# מערכת לניהול מוסד לימודי

מצגת זו מסכמת את הפרויקט שמטרתו להקים מערכת לניהול האגף האדמיניסטרטיבי של מוסד הלימודים "הסמינר הישן".  
הפרויקט מפותח על ידי צוות פיתוח מקצועי, ואני אחראית על פיתוח תשתיות לניהול שיעורים ונוכחות.

---

## על המערכת

המערכת מחליפה ניהול ידני שהתבצע באמצעות קבצי Excel במערכת דיגיטלית מתקדמת.  
היא מאפשרת למזכירות, למנהלים ולצוותי הוראה גישה נוחה לניהול נתוני תלמידים, קורסים, שיעורים ונוכחות.

### מטרות הפרויקט:
- ייעול תהליכי עבודה באגף האדמיניסטרטיבי.  
- שיפור הנגישות והאבטחה של המידע.  
- שילוב טכנולוגיות מתקדמות לניהול בזמן אמת.  
- פיתוח חוויית משתמש ידידותית ואינטראקטיבית.  

---

## תפקידי בפרויקט

### תחומי אחריות:
- פיתוח **ניהול שיעורים ונוכחות** באמצעות **Java Spring Boot** ו-**Angular**.  
- יצירת **פייפליינים לתקשורת בזמן אמת**:  
  - שימוש ב-**Kafka** להודעות על תחילת, סיום ושיעורים עתידיים.  
  - אינטגרציה עם **WebSocket** להצגת המידע ב-Angular.  
- יישום **API לניהול נוכחות**:  
  - פיתוח שירותי REST להוספה, עדכון וצפייה בנוכחות.  
  - חיבור ל-DB Connector לשמירת נתונים.  
- פריסת המערכת בענן:  
  - העלאת שירות ה-attendance-service ל-Render עם Docker.  

### תרומתי:
- יצירת מנגנון מתזמן (Scheduler-Service) שמנהל את הודעות השיעורים.  
- שילוב טכנולוגיות מתקדמות כמו **Kafka** ו-WebSocket לתמיכה בתקשורת מבוזרת.  
- שיפור חוויית המשתמש ב-Angular ע"י יצירת מסכים דינמיים לניהול נוכחות.  

---

## טכנולוגיות בשימוש

- **Backend**: Java Spring Boot, Kafka, Docker  
- **Frontend**: Angular  
- **Database**: PostgreSQL  
- **Cloud Deployment**: Render  

---

## איך לצפות במצגת

1. הורד את המצגת.
2. פתח את קובץ המצגת באמצעות PowerPoint או Google Slides.  

---

## קישורים נוספים

- [מדריך Kafka](https://kafka.apache.org/)  
- [מסמך מתודולוגיית Agile](https://agilemanifesto.org/)  

---

