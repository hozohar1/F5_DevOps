# F5_DevOps
Home assigment for DevOps Engineer - Intern
קונטיינר Nginx מקשיב לשני פורטים: 8080 ו-8081.
פורט 8080: מחזיר דף HTML מותאם אישית עם הודעת הצלחה.
פורט 8081: מחזיר שגיאת 404 כדי לדמות תגובה כושלת.
קונטיינר בדיקות מבצע בדיקות HTTP על שני הקצוות בעזרת ספריית requests של Python. אם השרת ב-port 8080 מחזיר קוד סטטוס 200 והשרת ב-port 8081 מחזיר קוד סטטוס 404, הבדיקה נחשבת להצלחה.
