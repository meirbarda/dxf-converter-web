# 🗺️ ממיר DXF ל-KML/GeoJSON | DXF Converter

ממיר פוליגונים מקבצי DXF לפורמט KML (Google Earth) או GeoJSON (GIS).

**🔗 [לחץ כאן לשימוש באפליקציה](https://YOUR_USERNAME.github.io/dxf-converter/)**

---

## ✨ תכונות

- ✅ **עובד בדפדפן** - אין צורך בהתקנה
- ✅ **תומך בקואורדינטות ישראליות** - EPSG:6991, EPSG:2039
- ✅ **המרה ל-KML** - לצפייה ב-Google Earth
- ✅ **המרה ל-GeoJSON** - שומר קואורדינטות רשת ישראל
- ✅ **גרירה ושחרור** - ממשק פשוט בעברית
- ✅ **עיבוד DXF מקומי** - קבצי DXF מעובדים כולם בדפדפן שלך, ללא העלאה לשרת
- ℹ️ **קבצי DWG** - מועלים לשרת המרה המופעל על ידי ברדה הנדסה ומעובדים לצורך ההמרה בלבד

## 🚀 שימוש

1. פתח את [הקישור לאפליקציה](https://YOUR_USERNAME.github.io/dxf-converter/)
2. גרור קובץ DXF לאזור ההעלאה
3. בחר מערכת קואורדינטות מקור (בד"כ Israel 2005)
4. בחר פורמט פלט (KML או GeoJSON)
5. לחץ "המר קובץ"
6. הורד את התוצאה

## 📍 מערכות קואורדינטות נתמכות

| קוד | שם | תיאור |
|-----|-----|-------|
| **6991** | Israel 2005 | רשת ישראל החדשה (IG05/12) - **מומלץ** |
| 2039 | Israel 1993 | ITM - רשת ישראל |
| 32636 | UTM 36N | Universal Transverse Mercator |
| 4326 | WGS84 | קואורדינטות GPS |

## 📋 פורמטים

### KML (Google Earth)
- קואורדינטות: WGS84 (EPSG:4326)
- שימוש: Google Earth, Google Maps

### GeoJSON (GIS)  
- קואורדינטות: רשת ישראל מקורית
- שימוש: QGIS, ArcGIS, תוכנות GIS

## 🛠️ פיתוח מקומי

```bash
git clone https://github.com/YOUR_USERNAME/dxf-converter.git
cd dxf-converter
# פתח index.html בדפדפן
```

## 📄 רישיון

© ברדה הנדסה (Barda Engineering). כל הזכויות שמורות. שימוש, העתקה, שינוי או הפצה של הקוד מחייבים אישור בכתב ממאיר ברדה.

© Barda Engineering. All rights reserved. Use, copying, modification, or distribution of this code requires written permission from Meir Barda.

---

**נוצר על ידי [ברדה הנדסה](https://barda-eng.co.il)** | מאיר ברדה - מודד מוסמך מס' 1609
