![preview image for DB](azkar-db.png) "صورة توضيحية لقاعدة البيانات")
# azkar-db
 قاعدة بيانات/مجموعة بيانات تحتوي على الأدعية والأذكار والرقية 

## الملفات
#### azkar-db
&#x202b; ملف قاعدة البيانات
ويستخدم قاعدة البيانات SQLite

&#x202b; يمكن قراءة وتعديل قاعدة البيانات باستخدام DB browser for SQLite، أو SQLiteStudio
وكلاهما برامج مجانية تعمل على عدد من أنظمة التشغيل
http://sqlitebrowser.org/
https://sqlitestudio.pl/

#### azkar.json
&#x202b; ملف بصيغة json، يحتوي على نسخة من جدول الأذكار تم تصديره من قاعدة البيانات

يمكن استخدامه بدلا من قاعدة البيانات في مواقع الويب

#### azkar.csv
&#x202b; ملف بصيغة csv، يحتوي على نسخة من جدول الأذكار تم تصديره من قاعدة البيانات

يمكن القراءة والتعديل عليه بدلا من قاعدة البيانات، باستخدام جداول إكسل وغيرها من البرامج


## المسميات
قاعدة البيانات تحتوي على جدول &#x202b;  azkar

الجدول يحتوي على ستة أعمدة كما يلي&#x202b;:
* category : التصنيف
* zekr : الذكر أو الدعاء
* description : الوصف أو الشرح
* count : عدد التكرارات
* reference : المرجع للأحاديث والآيات
* search : كلمات مفتاحية للبحث عن الذكر


## تحت التطوير
* إضافة المرجع، عدد التكرارات، الشرح
* &#x202b; إستخدام الترميز utf-8 لجميع النصوص

## إضافة التعديلات
يفضل إجراء التعديلات على ملف قاعدة البيانات وليس الملفات الأخرى، لأن الملفات الأخرى يمكن تصديرها من قاعدة البيانات.

## للمساهمة والمساعدة
يمكن المساعدة فيما يلي&#x202b;:
* إصلاح الأخطاء
* التبليغ عن الأخطاء
* استخدام هذه الملفات لتطوير موقع أو تطبيق
* تحديث المعلومات المفقودة في قاعدة البيانات مثل المرجع للأحاديث والآيات
* نشر وتوزيع قاعدة البيانات (الدال على الخير كفاعله) و(من دل على خير فله مثل أجر فاعله أو عامله)



# الرخصة
هذه الملفات بدون رخصة استخدام، يحق لك فعل ما تريد بها مجانا وبدون أي مسائلة قانونية.
