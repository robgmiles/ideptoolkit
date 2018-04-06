---
layout: page
title: تحويل شريط MiniDV
menu: true
order: 6
lang: عربى
ref: minidv
permalink: /minidv-ara
---

## قائمة المعدات

1. جهاز فيديو رقمي سوني Model HVR-M25AU  (وسلك التيار المتردد)
![](../assets/img/minidv/video_deck.png)

2. كابل FireWire 800/400 9-Pin/6-Pin
![](../assets/img/minidv/firewire.png)

3. موصل Apple Thunderbolt  إلى محول FireWire
![](../assets/img/minidv/firewire_adapter.png)
**لاصلاحات الشريط الضرورية (4-6):**

4.  شريط الربط  1/4 .
![](../assets/img/minidv/splicing_tape.png)

5. مفك Phillips 1.4mm
![](../assets/img/minidv/screwdriver.png)

6. موس حاد او مقص حاد الحواف
![](../assets/img/minidv/razor.png)![](../assets/img/minidv/scissor.png)
<br>**لتنظيف رؤوس الفيديو عندما تصبح مسدودة  (7-8):**

7. قطع للمسح خالية من الوبر (لتنظيف رؤوس الفيديو)
![](../assets/img/minidv/swabs.png)

8. كحول الأيزوبروبيل (%99) (لتنظيف رؤوس الفيديو)
![](../assets/img/minidv/alcohol.png)

## معلومات تاريخية حول شريط MiniDV

شريط MiniDV هو تنسيق فيديو قدم في عام 1995. حجمة الصغير وجودتة البصرية جعلت له شعبية خاصة في المستهلك والأسواق التعليمية. كل شريط يحمل حوالي 13 جيجابايت لمدة ساعة واحدة من الفيديو. وقت التشغيل هو في المتوسط ​​حوالي 60 دقيقة إذا سجلت في التشغيل القياسي (SP) أو 90 دقيقة في التشغيل الطويل (LP).

![](../assets/img/minidv/tape.png)

مثل أشرطة الفيديو بنمط DV  الأخرى، الشريط المغناطيسي داخل كاسيت MiniDV هو 1/4 بوصة واسعة بحيث يمكن إجراء أي إصلاحات مع 1/4 بوصة بواسطة الشريط الرابط، وتستخدم عادة في العمل الصوتي. في حين نادرا ما تتطلب الإصلاحات المادية، سيتم استعراض تقنيات الإصلاح بإختصار في نهاية هذه الوثائق.

![](../assets/img/minidv/tape2.png)

أشرطة MiniDV يمكن أن يتم تشغيلها في معظم أجهزة  DVCAM. يحتوي جهاز سوني الذي تستلمه (Model HVR-M25AU)  على آلية كاسيت مزدوجة الحجم تقبل أشرطة الفيديو الرقمية الصغيرة والقياسية DigitalMaster ، DVCAM و DV. ملاحظة: لا يمكن تشغيل بعض أشرطة MiniDV ماركة باناسونيك على أجهزة سوني.

الترميز المخزن على شريط MiniDV يمكن أن يكون الفيديو الرقمي (DV)، DVCAM أو HDV. إشارة الفيديو لجميع هذه التنسيقات تكون مضغوطه أو &quot;فاقدة لبعض البيانات&quot;. ومع ذلك، فإن الإشارة الصوتية ل DV غير مضغوطة. ويمكن أن يتفاوت معدل أخذ العينات (عدد العينات السمعية في الثانية) وعمق البتات (عدد البتات المستخدمة لنقل البيانات في كل عينة سمعية).



يدعم DV الأساليب التالية من الصوت النبضي التشكيلي النبضي (PCM): 4 قنوات بمعدل 12 bits  بمعدل أخذ عينات 32 kHz  عند 16 bits مع معدل أخذ عينات قدره 48 kHz  قناتان عند 12 bits   32 kHz ونظام 2 قناة عند 16 bits  بمعدل أخذ العينات 44.1 kHz  (على غرار الأقراص المدمجة) معدل أخذ العينات:

![](../assets/img/minidv/sampling_rate.png)

DVCAM  هو نسخة شبه العملية من DV  ويمكن أن يتم تشغيلها مرة أخرى بمعدل أسرع. يتم ترميز الفيديو HDV  مع مخطط ضغط H.262/MPEG-2  ويتم ترميز الصوت ستيريو مع مخطط ضغط MPEG-1 مع طبقه من نظامين من الضغط . يتم دمج الصوت والفيديو المضغوط في تيار نقل MPEG-2. قد تكون نسبة العرض إلى الارتفاع لتيارات فيديو MiniDV  قياسية (4:3) أو شاشة عريضة (16:9):

![](../assets/img/minidv/ratio.png)

لهذا المشروع سنقوم بإلتقاط تيار بيانات الفيديو عبر وصلة FireWire التي من شأنها الحفاظ على البيانات في تنسيق أكثر دقة، بما في ذلك البيانات الوصفية الأصلية. يشار إلى FireWire أيضا باسمi.LINK.  نقل التيار عبر مخرجات الفيديو التقليدية الأخرى كمكون أو S-videoالذي من شأنه أن يغير البيانات.

![](../assets/img/minidv/s-video.png)

## نقل محتوىMiniDV  

ويسمى البرنامج الذي ستستخدمه لنقل محتوى DV  و DVCAM AVCVideoCap . انها أداة في برنامج  Apple FireWire SDK Version 26، مجموعة تطوير البرمجيات لنظام التشغيل ماك. AVCVideoCap هو مرشح ممتاز لحفظ MiniDV  لأنه ينقل إشارات البيانات الخام دون تطبيق أي تغييرات على الصورة أو الصوت. يمكن ترميز الملف الرئيسي الخام الناتج إلى أي مجموعة متنوعة من الملفات المشتقة.

ولكن AVCVideoCap  لن يقوم بالتقاط محتوى HDV. للأشرطة التي تحتوي على HDV ، سوف تستخدم DVHSCap. سيتم توضيح كل من المسارين فيما يلي أدناه.

![](../assets/img/minidv/avcvideo.png)

**توصیل الکابلات والطاقة:**

1. قم بتوصیل سلك الطاقة المرفق بموصل AC IN  في الجزء الخلفي من جهاز Sony HVR-M25AU DV deck وقم بتوصیل الطرف الآخر بمصدر الطاقة الخاص بك.
2. قم بتوصيل كابل FireWire 800/400 800/400 9-Pin/6-Pin  في المقبس i.LINK في الجزء الخلفي من سطح DV. وصلة 6-Pin  سيتم توصيلها الى سطح الاتصال سطح DV.
3. قم بتوصيل وصلة  FireWire 9-pin  إلى محول Apple FireWire Thunderbolt.
4. قم بتوصيل محول Thunderbolt في كمبيوتر ماك بوك برو الخاص بك.
5. أدر وحدة DV  قبل تشغيل الكمبيوتر.
	* قم بتحويل مفتاح الطاقة في الجزء الخلفي إلى &quot;ON&quot;.
	* اضغط على زر الطاقة في الجزء الأمامي من الجهاز.

**إعداد MiniDV  الخاص بك للنقل:**

1. تأكد من ضبط MiniDV الخاص بك إلى &quot;الوضع الآمن&quot; حتى لا يتم التسجيل على ما هو مسجل عن طريق الخطأ.
  ![](../assets/img/minidv/mode.png)
2. أدخل كاسيت MiniDV الخاص بك. قم بدفع الشريط بلطف في باب الشريط.
3. إعادة الشريط إذا لم يكن هكذا بالفعل في بداية التسجيل.
4. اضغط على &quot;تشغيل&quot; واستعرض بإيجاز مواصفات نسبة العرض إلى الارتفاع والفيديو والصوت. سوف تظهر شاشة LCD الموجودة على الجزء الأمامي من جهاز الفيديو الصورة. الصوت يمكن متابعته من خلال سماعة رأس الموصولة بالمقبس  الأخضر في الجزء الأمامي من سطح الجهاز. سيتم عرض معدل أخذ العينات السمعية لتسجيلك تلقائيا على شاشة LCD. تأكد من ضبط وضع الصوت على سطح الجهاز لتتناسب مع معدل أخذ العينات الأصلي للتسجيل. للقيام بذلك انتقل إلى: القائمة&gt; مجموعة الصوت&gt; وضع الصوت. هنا يمكنك ضبط بين 48 كيلو هرتز أو 32 كيلوهرتز.

**بدء نقل DV / DVCAM:**

1. من أجل DV  أو DVCAM  يتم فتح برنامج إلتقاط يدعى AVCVideoCap إما:
	* كتابة AVCVideoCap في حقل البحث في ماك أو،
	* Goto: **Macintosh HD&gt;Developer&gt;FireWireSDK26&gt;Applications&gt;AVCVideoCap.app**

 2. تسليط الضوء على DV  في قائمة الاجهزة المدرجه
 ![](../assets/img/minidv/screenshot.png)
 3. انقر على &quot;التقاط من الجهاز&quot;. اسم الملف الخاص بك وحدد موقع على القرص الصلب الخاص بك لحفظ الملف إلى. ثم انقر فوق &quot;حفظ&quot;
 ![](../assets/img/minidv/screenshot_2.png)
 4. بعد ذلك، تحت وضع التسجيل، حدد &quot;التحكم في الشريط&quot;، ثم حدد &quot;متابعة&quot;  
 ![](../assets/img/minidv/tape_control.png)
 5. سيبدأ MiniDV  تلقائيا في تشغيل وإرسال بيانات DV  أو DVCAM. عند اكتمال الشريط سوف تتوقف تلقائيا. إذا كنت ترغب في إيقاف الالتقاط في أي لحظة، حدد &quot; Abort Capture Now &quot;. سوف يكون ملف الفيديو الرقمي الناتج بإمتداد .DV.
![](../assets/img/minidv/screenshot3.png)

**الشروع في نقل محتوى HDV:**

1. من أجل  HDV قم بفتح برنامج الالتقاط والذي يدعى DVHSCap  عن طريق إما:
	* طباعة DVHSCap  في حقل البحث عن في ماك أو،
	* Macintosh HD>Developer>FireWireSDK26>Applications>DVHSCap.app
2. اختر &quot;التقاط من D-VHS&quot;
 ![](../assets/img/minidv/screenshot4.png)
3. اسم المشروع الخاص بك وحدد &quot;حفظ&quot; في إطار &quot;حدد التقاط ملف&quot;. حدد موقعا على محرك الأقراص الثابتة لالتقاط الفيديو.
 ![](../assets/img/minidv/screenshot5.png)
4. سوف يبدأ MiniDV  تلقائيا العمل ونقل بيانات HDV. عند اكتمال الشريط سوف تتوقف تلقائيا. إذا كنت ترغب في إيقاف الالتقاط في أي لحظة، حدد &quot;إيقاف الالتقاط&quot;. سوف يكون ملف الفيديو الرقمي الناتج بإمتداد m2t. .
![](../assets/img/minidv/screenshot6.png)

## إنشاء ملفات مباشرة سهلة الوصول  

بالإضافة إلى الملفات الخام فإن ملفات  dv. و m2t. سوف تبقي للحفظ، سوف تقوم بإنشاء ملفات MP4 أصغر للولوج السريع.

1. بدء تشغيل برنامج Adobe Media Encoder
	* اكتب أدوب Adobe Media Encoder في حقل البحث ماك سبوتليت أو
	* اذهب إلى Go to: Launchpad &gt; Adobe Media Encoder

2. اسحب ملفات dv. و m2t. التي تريد تحويلها إلى قائمة الانتظار.
![](../assets/img/minidv/access1.png)
3. حدد كل عنصر في قائمة الانتظار، وضمن &quot;تنسيق&quot; حدد H.264 من القائمة المنسدلة لمعايير الفيديو.
![](../assets/img/minidv/access2.png)
4. ضمن &quot;الضبط المسبق&quot;، حدد &quot;مكتبة UCLA - UCLA Library - Video - Streaming File.&quot; مواصفات هذا الإعداد المسبق هي:
	* Video Stream: H.264/mp4 –AVC, SD, 480p
	* Audio Stream: 32 kHz/16-bit AAC
![](../assets/img/minidv/access3.png)
 5. تحت &quot;ملف الإخراج&quot; انقر على اسم الملف لتحديد موقع لحفظ الملفات.
6. كرر الخطوات 3-5. وبمجرد الانتهاء من قائمة الانتظار للملفات الجاهزة لتحويلها، انقر على أيقونة التشغيل الخضراء لبدء الترميز. من المفضل ، معالجة الملفات في نهاية يوم العمل والسماح للعمليات بالتشغيل خلال الليل لكل ملف على حده في قائمة الانتظار.

7. وبمجرد الانتهاء من قائمة الانتظار من الملفات الجاهزة لتحويلها، انقر على أيقونة التشغيل الخضراء لبدء الترميز. من المفضل ، معالجة الملفات في نهاية يوم العمل والسماح للعمليات بالتشغيل خلال الليل لكل ملف على حده في قائمة الانتظار.
![](../assets/img/minidv/access4.png)

## إصلاح شريط MiniDV

احيانا يكون شريط MiniDV في حاجه الى الاصلاح. قد يكون الشريط ممزقا أو يحتوي الكاسيت الأصلي على مشكلة تمنع التشغيل. يمكن إصلاح الشريط الممزق ب ¼ &quot;شريط الربط. إذا كان جسم الكاسيت ذاته معطوبا، فإنه يمكن استبداله مع كاسيت جديد MiniDV فارغ.

![](../assets/img/minidv/New Picture.bmp)

1. معظم شرائط  MiniDV  تحتوى على أربعة مسامير صغيرة تقع على الجانب السفلي من الغلاف. باستخدام مفك براغي صغير فيليبس (حجم 1.4 مم تقريبا)، قم بإزالة البراغي الأربعة. يجب الحرص على عدم السماح الشريط بالداخل في حالة غير مقيده او اتلافه. وضع المسامير في مكان آمن بحيث يمكن أن إيجادها  بسهولة عند الانتهاء من الإصلاح . إذا لم يكن في الشريط الخاص بك مسامير ستحتاج إلى كسر الكاسيت , يجب فتحه بعناية فائقة بحيث يمكن إزالة بكرات الشريط داخله بأمان.
 ![](../assets/img/minidv/tape_repairing.png)   ![](../assets/img/minidv/tape2_repairing.png)
 2. ثم، يتم توصيل حواف الشريط بعنايه بقطعه صغيره من شريط الربط على الجانب اللامع. لا تضع أي شريط على سطح غير لامع أ لأن هذا الجانب يحتوي على التسجيل. تقليم بعناية أي زوائد في شريط الربط على حافة شريط MiniDV. ينصح بأن ترتدي قفازات عند التعامل مع الشريط لتجنب إتلاف سطح الشريط (على الرغم من ضعف صورة المثال أدناه).
  ![](../assets/img/minidv/tape3_repairing.png)
   <br>لمنع الشريط من التوقف أثناء التشغيل ، يمكنك تأمين المحاور بقطعة من الشريط اللاصق:
![](../assets/img/minidv/tape4_repairing.png)
 3. إذا كان جسم الكاسيت معطوبا، فيمكنك زرع البكرات في كاسيت جديد تم تفكيكه. إزالة البكرات بعناية من الكاسيت القديم ووضعه في الكاسيت السليم الجديد. إزالة أي ترهل في الشريط عن طريق لف البكرات باليد.
![](../assets/img/minidv/tape5_repairing.png)
 4. بمجرد اكتمال عملية الإصلاح، ضع غطاء الشريط في موضعه ثم أغلق مسمار الغلاف.