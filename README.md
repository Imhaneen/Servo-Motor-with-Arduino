
# خوارزميات تشغيل محركات من نوع سيرفو موتر لتشكيل حركة مشي الروبوتات
***

ماهي محركات السيرفو موتر ؟

 محركات السيرفو هي محركات دورانية او خطية تحتوي على حساس مدمج معها ليتم التحكم بشكل دقيق جدا

لماذا يتم استخدام السيرفو موتر لقدم الروبوت؟

 ليتم تحريك قدم الروبوت بدقة عالية وسلاسة

***



1- لتشكيل حركة الروبوتات  يتم تقسيم الحركة بحيث يتم تنفيذها بالتناوب بين القدمين
كل قدم تحتوي على ثلاثة محركات من نوع سيرفو موتر 


2- توصيل محرك السيرفو بالدائرة الالكترونية

يوجد ثلاثة منافذ في محرك السيرفو عادة مايتم تمييزها بألوان مختلفة

> -  (digital)ويتم توصيلة بأحد منافذ(Signal (SIG))السلك البرتقالي هو
> - ويتم توصيلة بالقطب الموجب لمصدر الطاقة(power supply (VCC))السلك الاحمر هو
> -  يتم توصيلة بالقطب السالب لمصدر الطاقة Ground (GND)السلك الاسود او البني وهو



3- كتابة الكود 
يتم كتابة الكود عن طريق برنامج الاردوينو باستدعاء المكتبات ويتم تعريف المحركات ومنافذ توصيلها ومن ثم كتابة كود حركة الروبوتات بتحديد الزوايا المناسبة.


4- الاختبار 
يتم اختبار حركة الروبوتات وتصحيح الأخطاء والتأكد من صحة الكود
