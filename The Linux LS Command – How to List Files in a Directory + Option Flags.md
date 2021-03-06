# امر اللينكس LS - كيف تعرض الملفات الموجودة في مجلد +خيارات الاوامر (options) 


![The Linux LS Command – How to List Files in a Directory + Option Flags](https://www.freecodecamp.org/news/content/images/size/w2000/2020/09/article-banner-7.png)

منذ نشئة اليونكس (Unix) في اوائل 1970 ، استخدمته الكثير من انظمة التشغيل كاساس لبناء نظام التشغيل ، بعض هذه الانظمه  فشل والبعض الاخر نجح .

لينكس (Linux) هو احد انظمة التشغيل المشهورة المبينة علي نظام اليونكس (Unix) ، وهو نظام مفتوح المصدر (open source) ومستخدم على نطاق واسع في العالم في الكثير من المجالات .


وواحدة من اروع ميزات نظام التشغيل لينكس (Linux) هي واجهة الاوامر (Command Line Interface) واختصارها (CLI) وهي تسمح للمستخدم للتفاعل مع الحاسوب من خلال شيل  (shell ) .
 لينكس شيل  (Linux shell) هي بيئة (REPL) اختصار ل (**R**ead,  **E**valuate,  **P**rint,  **L**oop) تعني (اقرا ، قيم ، اطبع ، تكرار) تسمح للمستخدم بكتابة اوامر وتقوم (shell) بتنفيذ الامر وتعرض النتائج 


و  `ls` هو احد اوامر (Linux) الكثيرة الذي يسمح للمستخدم بعرض الملفات او المجلدات من خلال واجهة الاوامر  (CLI) 

في هذة المقالة سنبحر في تفاصيل  الامر `ls` ، وبعض اوامره الفرعية المهمة التي سوف تحتاجها من يوم لاخر .  
## المتطلبات الأساسية
- جهاز حاسوب به مجلدات وملفات
- ان تقوم بتثبيت أحد توزيعات (Linux)
- المعرفة بسيطة ب (CLI)
- ابتسامة على وجهك :)

## امر اللينكس `ls` 

امر `ls` يستخدم لعرض قائمة الملفات او المجلدات في (Linux) او نظام تشغيل مبني على (Unix) - (Unix-based) 

هو مثل تصفح الملفات باستخدام _File explorer_  or  _Finder_ من خلال (GUI) الواجه الرسومية ، امر `ls` يستخدم لعرض قائمة الملفات او المجلدات الموجودة في المجلد الحالي ، ويسمح لك بالتعامل معها من خلال الاوامر .  

افتح terminal الخاصة بجهازك و اكتب `ls` ل تشاهد كيف تعمل :  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-9.40.29-PM.png)

## كيف تعرض ملفات المجلد مع خيارات الاوامر

امر `ls` له بعض العلامات او الاشارات (flags) (احيانا يطلق عليها بالخيارات  (options)) وهي معلومات اضافية  تغير طريقة عرض الملفات او المجلدات على terminal الخاصة بجهازك. 

بمعنى اخر ال flags تغير في طريقة عمل الامر  `ls`  : 

```
 ls [flags] [directory]
```

### عرض الملفات الموجودة في مجلد العمل الحالي : 

اكتب الامر `ls` لعرض محتويات المجلد الحالي : 

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-9.40.29-PM.png)

### عرض الملفات في مجلد اخر :
اكتب الامر `ls [directory path here]` لعرض محتويات مجلد اخر (من خلال تحديد مسار المجلد): 


![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-10.32.52-PM.png)

### عرض الملفات في المجلد الرئيسي (root)  
اكتب الامر `ls /` لعرض محتويات المجلد الرئيسي : 


![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-10.46.10-PM.png)

### عرض الملفات الموجودة في المجلد الاب لهذا المسار  
اكتب الامر `.. ls` لعرض محتويات المجلد الاب (مرحلة واحدة للاعلى في الابوية) ، استخدم الامر `../.. ls` لعرض المحتويات (مرحلتين للاعلى) :  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-10.48.22-PM.png)
### عرض الملفات في المسار الرئيسي الخاص بالمستخدم (home/user/) 
اكتب الامر `~ ls` لعرض محتويات المسار الرئيسي الخاص بالمستخدم :  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-10.51.19-PM.png)

### عرض فقط المجلدات
اكتب الامر ` /* ls -d` لعرض فقط المجلدات : 

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.53.05-PM.png)

### عرض جميع محتويات المجلدات  
اكتب الامر `* ls` لعرض جميع محتويات المجلدات :  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-1.07.54-PM.png)

### عرض كافة الملفات لجميع المسارات  
اكتب الامر `ls -R` لعرض كافة محتويات المسارات الفرعية للمسار الحالي :   

![](https://www.freecodecamp.org/news/content/images/2020/09/Screenshot-2020-09-01-at-9.04.56-AM.png)

> ملاحظة هذه العملية ممكن ان تحتاج وقت طويل لعرض جميع الملفات لانها سوف تعرض جميع محتويات المسارات بشكل منفصل ، لذلك يمكن تحديد المسار او المجلد الذي تود عرض جميع مساراته مثل `ls Downloads -R`  

### عرض الملفات مع عرض المساحة المستخدمة لكل منها  
اكتب الامر `ls -s` (the  **s**  is lowercase) عرض الملفات او المجلدات مع عرض المساحة المستخدمة لكل منها  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.30.19-PM.png)

### عرض الملفات مع معلومات تفصيلية 
اكتب الامر `ls -l` لعرض محتويات المجلد او المسار الحالي على شكل جدول يحتوي على المعلومات التالية : 

- الصلاحيات الممنوحة لكل محتوى 
- عدد الروابط
- مالك المحتوى
- مالك المجموعة
- حجم المحتوى بالبايت
- تاريخ او وقت آخر تعديل
- اسم الملف او المجلد

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-20-at-10.52.37-PM.png)

### عرض الملفات مع معلومات تفصيلية بشكل اوضح عن حجم الملفات 
اكتب الامر  `ls -lh` لعرض محتويات المجلد او المسار الحالي على شكل جدول مثل السابق لكن بتوضيح اكثر لحجم الملف او المجلد  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.14.33-PM.png)

ملاحظة الاحجام المعروضة تعني bytes (B) و megabytes (MB) و gigabytes (GB) و terabytes (TB) 
### عرض جميع الملفات بما يتضمن المخفية منها 
اكتب الامر `ls -a` لعرض كافة محتويات المسار الحالي بما يتضمن المخفية منها :   
في اللينكس اي ملف يبدا ب `.` يعتبر ملف مخفي 

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-11.12.26-AM.png)

### عرض الملفات مع معلومات تفصيلية بما يتضمن المخفية منها 
اكتب اي من الاوامر التالية `ls -l -a`  او  `ls -a -l`  او  `ls -la`  او  `ls -al`  لعرض الملفات او المجلدات بما يتضمن المخفية منها : 

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.17.01-PM.png)

### عرض الملفات وترتيبها حسب التاريخ والوقت
اكتب الامر `ls -t`لعرض الملفات والمجلدات وترتيبها حسب تاريخ ووقت التعديل بشكل تنازلي (من الاحدث للاقدم ) .

يمكن اضافة ال `-r`  كflag للامر السابق لعكس الترتيب ليصبح الامر بهذا الشكل `ls -tr` :  

![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.20.09-PM.png)

### عرض الملفات وترتيبها حسب الحجم 
اكتب الامر `ls -S`  (the  **S**  is uppercase) لعرض الملفات او المجلدات وترتيبها حسب الحجم من الاكبر للاصغر  .

يمكن اضافة ال `-r`  كflag للامر السابق لعكس الترتيب ليصبح الامر بهذا الشكل `ls -Sr` :  


![](https://www.freecodecamp.org/news/content/images/2020/08/Screenshot-2020-08-21-at-12.20.38-PM.png)

### كتابه نتيجة عرض الملفات في ملف   
### List files and output the result to a file
اكتب الامر `ls > output.txt` لكتابه نتيجة عرض الملفات في ملف `output.txt` يمكنك استخدام اي flag من التي تم شرحها سابقاً مثل `la-` , اهم ما في هذه النقطة انك يمكنك ان تكتب الناتج في ملف بدل من عرضه على الشاشة . 

يمكن لك ان تستخدم الملف حسب ما تريد ، لكن لعرض محتوياته استخدم الامر `cat output.txt` :  

![](https://www.freecodecamp.org/news/content/images/2020/09/Screenshot-2020-09-01-at-9.12.59-AM.png)

.
# خلاصة 

هناك الكثير من الاوامر و تشكيلات الاوامر (تجميع اكثر من امر ) لعرض الملفات والمجلدات بما يناسب احتياجك ، المهم انك يمكنك جمع اكثر من امر وتنفيذه كانه امر واحد . 

تخيل انك تريد ان عرض الملفات مع معلومات تفصيلية بما يتضمن المخفية وترتيبها حسب الحجم ، سيكون الامر`ls -alS`  وهو تجميع للاوامر  `ls -l`و `ls -a`و `ls -S`.

في حال لم تذكر او غير متاكد من طريقة استخدام اي امر يمكنك تنفيذ الامر `ls --help`  or  `man ls` وسيعرض لك دليل يشرح استخدام الامر مع كل الخيارات الممكنة للامر `ls` :  

![](https://www.freecodecamp.org/news/content/images/2020/09/Screenshot-2020-09-01-at-9.57.37-AM.png)


شكراً لكم للقرائة ! 
