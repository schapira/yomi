# yomi
929 hackthon
זהו פורמט של פרוטוקול לשיתוף תכני לימוד המטרה היא לאפשר לפלטפורמות לדבר אחת עם השניה לטובת איכות חווית משתמש טובה יותר על ידי שיתופי פעולה בין הגורמים השונים
ההשראה באה מלימוד התנך היומי 
הפורמט יכול להכיל כל סוג של לימוד על בסיס יומיומי

על מנת שאפליקציה תדבר עם ספק תוכן על האפליקציה ליצור טוקן ייחודי באתר הספק לצרכי אימות 
## מידע על הפורמט 
שדות חובה מסומנים ב שני כוכביות (*)
### **provider***
מידע על ספק התוכן
* **name*** - STRING שם הספק (לדוגמא 929) 
* site - STRING, url
* **phone*** - 
* **email*** - STRING
* logo - STRING (link to jpeg image)
### partner
מידע על האנשים השותפים ביצירה התוכן

**חובה לפחות אחד יוצר
ולפחות אחד בעל זכויות יוצרים**
* **name*** - STRING 
* **role** - STRING (CREATOR etc)
* rights - BOLLEAN 
* site - STRING, url
* phone - 
* email - STRING
* image - link to jpeg image
### **data***
התוכן עצמו
* **title*** - STRING
* **format*** - TEXT, IMAGE, VIDEO, AUDIO
* **category*** - SOURCE, TRANSLATION, COMMENTARY, WORKART
* **language*** - STRING, he, en, fr .....
* **data***- STRING, in case of TEXT, the text itself, in case of media (IMAGE, VIDEO, AUDIO) direct link to file 
* **licence*** - STRING link to licence detail.
### **serials***
* **source*** - array, ['תהילים','יב','ד']
* daynum - NOMBER, days since day one of this learning
* date - NUMBER (timestamp)


