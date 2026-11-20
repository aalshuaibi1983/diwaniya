# الديوانية — دليل التشغيل

رابط الأعضاء: https://aalshuaibi1983.github.io/diwaniya/
رابط المدير: https://aalshuaibi1983.github.io/diwaniya/?admin


## الملفات
- `index.html` — الواجهة كاملة (للأعضاء + وضع المدير)
- `data.json` — ملف البيانات (يتحدث تلقائياً عند الضغط على «نشر»)

## 1) الرفع على GitHub
1. أنشئ مستودعاً **عاماً (Public)** باسم `estiraha` (أو استخدم المستودع الموجود).
2. ارفع الملفين `index.html` و `data.json`: ‏Add file ← Upload files ← Commit.
3. ‏Settings ← Pages ← Source: **Deploy from a branch** ← Branch: `main` / root ← Save.
4. بعد دقيقة يصبح الرابط: `https://اسم-الحساب.github.io/estiraha/`

## 2) رمز النشر (Token) — مرة واحدة فقط
1. من GitHub: ‏Settings ← Developer settings ← Personal access tokens ← **Fine-grained tokens** ← Generate new token.
2. ‏Repository access: **Only select repositories** ← اختر `estiraha`.
3. ‏Permissions ← Repository permissions ← **Contents: Read and write**.
4. انسخ الرمز (يبدأ بـ `github_pat_`).

## 3) أول دخول للمدير
1. افتح: `https://اسم-الحساب.github.io/estiraha/?admin`
2. أنشئ رقماً سرياً.
3. من **الإعدادات**: اسم الصندوق، اسم المدير، الرصيد الافتتاحي، قيمة القطة الشهرية.
4. في قسم **النشر على GitHub**: اسم الحساب واسم المستودع والرمز ← «حفظ ونشر الآن».
5. أضف الأعضاء (عدة أسماء دفعة واحدة، كل اسم في سطر) — تُنشر تلقائياً.
6. من الإعدادات اضغط «إضافة التذكير لتقويم الجوال» ليصلك تنبيه يوم 27 من كل شهر.

> الرمز يُحفظ على جوال المدير فقط ولا يُنشر. وحتى لو عرف أحدٌ الرقم السري لا يستطيع تعديل ما يراه الأعضاء دون هذا الرمز.

## 4) الربط مع Google Sites
‏Insert ← **Embed** ← By URL ← الصق رابط GitHub Pages ← اختر «Whole page» ← Publish.
الأعضاء يفتحون رابط Google Sites كالمعتاد. **المدير يستخدم رابط GitHub مباشرة** (مع `?admin`) لأن Google Sites يمنع تحميل ومشاركة ملفات PDF من داخل الصفحة المضمّنة.

## ملاحظات
- رقم الجوال اختياري، ويُحفظ في `data.json` العام — لا تضفه إلا بموافقة صاحبه.
- السنة الجديدة: الإعدادات ← «إضافة سنة جديدة» (يُرحّل الرصيد تلقائياً).
- **التحديث فوري:** بعد إكمال إعدادات النشر، يُنشر كل تعديل تلقائياً خلال ثانية، وصفحة الأعضاء المفتوحة تتحدث وحدها خلال 10 ثوانٍ تقريباً دون إعادة تحميل.
- خذ نسخة احتياطية من الإعدادات بين حين وآخر.
