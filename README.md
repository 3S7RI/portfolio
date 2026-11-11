# موقع معرض أعمال المصمم

## رفع الموقع على GitHub
1. افتح github.com واعمل حساب، وبعدها New repository (مثلًا اسمه portfolio) واختار Public.
2. اضغط Add file ثم Upload files، واسحب كل محتويات الفولدر (index.html و works.js وفولدر assets) واضغط Commit changes.
3. من Settings ثم Pages: اختار Branch اسمه main والفولدر / (root) واضغط Save.
4. بعد دقيقة أو اتنين الموقع هيشتغل على: https://اسم-حسابك.github.io/portfolio

## إضافة شغل جديد
1. حط الصورة (PNG أو JPG أو WebP) جوه فولدر assets/works.
2. افتح works.js وضيف سطر جديد في آخر القايمة:
   { "title": "اسم التصميم", "desc": "وصف قصير", "cat": "logo", "img": "assets/works/اسم-الصورة.png", "hero": false },
3. cat هو القسم: logo (لوجوهات) / teacher (بوسترات مدرسين) / cert (شهادات) / cloth (ملابس) / other (تانية).
4. ارفع الملفين على GitHub واستنى دقيقة.

## نصايح
- اكتب اسم الصورة بحروف إنجليزي من غير مسافات.
- خلي الصورة بنسبة 4:3 تقريبًا وحجمها أقل من 500 كيلوبايت عشان الموقع يفتح بسرعة.
- hero: true معناها الصورة تظهر في المجموعة اللي فوق في الصفحة الرئيسية (3 صور بس).
