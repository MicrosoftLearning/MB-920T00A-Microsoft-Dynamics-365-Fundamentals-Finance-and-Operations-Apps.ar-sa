---
lab:
  title: 'تمرين معملي 3: إنشاء دفتر يومية الجرد'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# الوحدة 3: تعلم أساسيات إدارة سلسلة إمداد Microsoft Dynamics 365

## تمرين معملي 3: إنشاء دفتر يومية الجرد

## إعداد المعمل

   - **الوقت المقدر**: 10 دقائق

## الإرشادات

1.  في **صفحة التمويل والعمليات الرئيسية**، أعلى اليمين، تحقق من أنك تعمل مع شركة **USMF**. إذا لزم الأمر،فحدد الشركة، ومن القائمة المنسدلة، حدد **USMF**. 

2.  في جزء التنقل الأيسر، حدد وحدة **إدارة المخزون** وحدد **إدخالات دفتر اليومية** > **جرد الأصناف‬** > **الجرد**. 

3.  حدد زر **إضافة جديد** في جزء الإجراءات. سيظهر جزء الحوار**إنشاء دفتر يومية مخزون**. حدد الزر **موافق**. 

4.  سيظهر نموذج **دفتر يومية جرد المخزون** مع معلومات العنوان والسطر. 

    ![لقطة شاشة لنموذج دفتر يومية جرد المخزون مع ملء معلومات العنوان والتفاصيل.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5.  في جزء الإجراءات، حدد **إنشاء سطور -&gt; المخزون الفعلي**. 

6.  في جزء مربع الحوار **إنشاء دفتر يومية جرد مخزون فعلي**، قم بتعيين حقول **المستودع** و**حالة المخزون** و**الموقع** و**رقم لوحة الترخيص** إلى **نعم**. 

    ![لقطة شاشة لجزء مربع الحوار إنشاء دفتر يومية جرد المخزون الفعلي مع تعيين الحقول كما تم وصفه.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7.  وسّع القسم **السجلات المراد ضمها** وحدد زر **المرشح**. بالنسبة لحقل **رقم العنصر**، اكتب `A0001` في حقل**    المعايير**، ثم حدد **موافق**. 

8.  حدد **موافق** في أسفل جزء مربع الحوار **إنشاء دفتر يومية جرد المخزون الفعلي‬**. 

    ستظهر الكمية الموجودة في المخزون الفعلي للعنصر **A0001** في شبكة **أسطر دفتر اليومية** مع تقسيم المكان والمستودع والموقع. 

9.  في العمود **مجرود‫** في القسم **سطر دفتر اليومية**، أدخل الأرقام التي تم جردها في كل موقع/مستودع/مكان. لاحظ ما يلي: 

    - إذا كانت الكمية **الفعلية** هي نفسها الكمية **المجرود‬‏‫ة**، فسيكون حقل **الكمية** فارغاً. 

    - إذا كانت قيمة الحقل **مجرود‬‏‫** أكبر من قيمة الحقل **فعلي**، فسيحتوي حقل **الكمية** على قيمة موجبة. 

    - إذا كانت قيمة الحقل **مجرود‬‏‫** أقل من قيمة الحقل **فعلي**، فسيحتوي حقل **الكمية** على قيمة سالبة. 

10. قم بتغيير سنة حقل **التاريخ** في كل سطر ليكون 2022. 

11. حدد الزر **التحقق من الصحة** في جزء الإجراءات، ثم حدد **موافق** في جزء مربع الحوار. 

12. حدد الزر **ترحيل**. 

13. **أغلق** الصفحة وارجع إلى الصفحة الرئيسية. 

