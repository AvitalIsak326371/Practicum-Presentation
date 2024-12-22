# מצגת פרויקט ניהול שיעורים

מצגת זו מסכמת את הפרויקט שבוצע במסגרת הפרקטיקום. היא כוללת את המשימות העיקריות שבוצעו, צילומי מסך של הקוד שנכתב, והסברים מפורטים על המערכת שפותחה.

## על הפרויקט

הפרויקט הוא מערכת לניהול שיעורים המבוססת על ארכיטקטורת מיקרו-שירותים. המערכת משלבת בין **Java Spring Boot** עבור השירותים בצד השרת לבין **Angular** עבור צד הלקוח. המערכת משתמשת ב-**Kafka** לניהול תקשורת בין השירותים.

## תוכן המצגת

- מבוא: תיאור כללי של המערכת והמטרות.
- ארכיטקטורה:  
  - תכנון ארכיטקטורת המיקרו-שירותים.
  - שימוש ב-Kafka לניהול תקשורת בין שירותים.
- שירותים עיקריים:
  - **attendance-service**: 
    - ניהול נוכחות בזמן אמת.
    - קבלת הודעות על תחילת שיעור באמצעות Kafka.
    - שליחת נתונים בזמן אמת ל-Angular דרך WebSocket.
  - **scheduler-service**: 
    - שליחת הודעות על תחילת וסיום שיעורים.
    - שליחת נתונים על שיעורים עתידיים.
- ממשק המשתמש: 
  - דוגמאות למסכים.
  - ממשק המשתמש לשיעורים עתידיים.
- קוד לדוגמה: 
  - קטעי קוד עיקריים שנכתבו בשירותים.
  - הסברים על הפתרונות שבוצעו.

## איך לצפות במצגת

1. הורד את המצגת .  
2. פתח את קובץ המצגת (`presentation.pptx`) בתוכנה מתאימה (כמו Microsoft PowerPoint או Google Slides).

## טכנולוגיות בשימוש

- **Java Spring Boot**  
- **Angular**  
- **Kafka**  
- **WebSocket**



---
