---
demo:
  title: 'العرض التوضيحي 2: إنشاء فاتورة'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## العرض التوضيحي 2 - إنشاء فاتورة

1. استعرض للوصول إلى مساحة عمل  **Project management**.  
    في هذا العرض التوضيحي، سننتقل إلى عملية فوترة مشروع واحد ضمن عمليات المشروع. على الرغم من أنه من الممكن إجراء فواتير جماعية، إلا أننا سنركز، لأغراض توضيحية، على مرة واحدة فقط وعلى مشروع فعلي.سنرى أيضًا نتائج الترحيل والرؤى المالية في بيان المشروع. لنبدأ بفوترة المشروعات. 

1. في منتقي الشركة العلوي الأيمن، تحقق من أن الكيان القانوني الذي تتصل به هو **USSI**. إذا لم يكن كذلك، قم بتغيير الكيان القانوني إلى **USSI**.  
    من مساحة عمل **Project management**، يمكننا رؤية جميع المشاريع النشطة.يمكننا البحث عن مشاريع باستخدام عامل التصفية، أو في هذا المثال، سنختار Project ID معروف. 

1. في جدول  **Active projects** ، في عمود **Project ID** ، حدد **00000093 Contoso Consulting**.  

1. بعد ذلك، افتح صفحة **Project invoice proposals** لعرض جميع الفواتير السابقة التي تمت معالجتها لشركة Contoso Consulting. 

1. في جزء الإجراءات، في علامة التبويب **BILL** ، حدد  **Project invoice proposals**. 

1. في صفحة **Project invoice proposals** ، في شريط التنقل، حدد **New**، ثم **Invoice proposal**.  
    هذه فاتورة بسيطة للوقت والمواد، لذلك لا نحتاج إلى تحديد خيار مقترح الفاتورة من قاعدة الفوترة. 

    ![لقطة شاشة لصفحة مقترحات فاتورة المشروع مع تمييز مقترح فاتورة جديد.](./media/projops_invoice_1_new_invoice_proposal.png)

1. في الجزء **Create invoice proposal** ، أشر إلى المربعات الموجودة ضمن **Select transactions**.  
    من هنا، يمكننا تحديد أشياء مثل طريقة الفوترة وتاريخ الفاتورة ومصدر التمويل والمشروع.يمكننا أيضًا اختيار تضمين المشاريع الفرعية، بالإضافة إلى دمج أنواع الحركات وتواريخ البدء والانتهاء للحركات وأي أبعاد مالية نحتاجها. 

    ![لقطة شاشة لجزء إنشاء عرض فاتورة مع تمييز قسم المعاملات المحددة.](./media/projops_invoice_2_select_transactions.png)

1. من القائمة المنسدلة **Project** ، حدد **00000093 Contoso Consulting**. 

1. في هذا المثال، تأكد من تعيين **Invoice date** إلى **2/1/21** وتعيين **Start date** إلى **2/1/21**، و"end date" هو تاريخ اليوم.  
    بمجرد إجراء التحديدات، حدد زر البحث للعثور على المعاملات التي تفي بهذه المعلمات.

1. حدد **Search**.  
    بعد ذلك، لإصدار فاتورة بجميع المعاملات، حدد خيار "تحديد الجميع". سيؤدي هذا إلى تحديد العناصر التي نختارها للمصروفات والساعات.

1. ضمن علامة التبويب **Project transactions** ، حدد **Select all**.

1. حدد  **OK**. 

1. في صفحة **Invoice proposal** ، أشر إلى عمود **Invoice line amount** .  
    هنا يمكننا رؤية مبلغ الفاتورة والملخص، وساعات العمل، والمصروفات.

    ![لقطة شاشة لصفحة عرض الفاتورة مع تمييز سطر عمود مبلغ الفاتورة.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. أشر إلى علامة التبويب **Hour** . 

1. أشر إلى علامة التبويب **Expense**.  
    يمكنك أيضًا التبديل والنظر في معاملة المصروفات.  
بعد ذلك، دعنا نتحقق من زر الإجماليات لمعرفة الشكل الذي ستبدو عليه الفاتورة من منظور التكلفة والإيرادات.

1. في شريط التنقل، حدد **Totals**.

1. في صفحة **Totals**، أشر إلى عمود **GENERAL LEDGER**، وعمود **CUSTOMER** ، وعمود **Line discount**.  
    في شاشة الإجماليات، يمكننا معرفة التأثير الذي سيكون على دفتر الأستاذ العام وأي معلومات خاصة بالعميل مثل حدود الائتمان وأي خصومات وضرائب المبيعات والتأثير الصافي للفاتورة. 

1. على الجانب الأيمن من الشاشة، حدد **X** لإغلاق الصفحة.  
    نحن الآن جاهزون لإنشاء معاينة طباعة للتأكد من دقة جميع معلومات الفوترة. تستخدم بعض المؤسسات المعاينة أثناء اجتماعات مراجعة المشروع للتأكد من موافقة الجميع على الإجماليات قبل إنهاء الفاتورة. 

1. في صفحة **Invoice proposal** ، في شريط التنقل، حدد **Print preview**. 

1. في مربع الحوار، حدد **Print preview**.  
    يمكنك هنا مشاهدة مثال على معاينة الطباعة لفاتورة أولية. 

1. حدد **X** لإغلاق الصفحة.  
    بمجرد التحقق من صحة جميع المعلومات والرضا عن معاينة الطباعة للفاتورة، يمكننا نشر عرض الفاتورة.

1. في شريط التنقل، حدد **Post**.

1. حدد علامة التبويب **Parameters** .

1. ضمن **PARAMETER**، عين **Posting** إلى **Yes**.

1. ضمن **PRINT OPTIONS**، عين **Print invoice** إلى **Yes**.

1. حدد  **OK**.

1. في صفحة **Invoice** ، أشر إلى رقم **Invoice**.  
    الآن لدينا رقم فاتورة تم إنشاؤه.  
    بمجرد نشر الفاتورة، يمكننا مراجعة المعلومات في سجل الفواتير والتنقل لأسفل إلى معاملات دفتر الأستاذ.

1. استعرض للوصول إلى مساحة عمل  **Project management**.

1. في جدول **Active projects** ، حدد مشروع **00000093** **Contoso consulting**.

1. في جزء الإجراءات، في علامة التبويب **BILL** ، حدد **Invoice journals**.

1. في صفحة **Invoice journal** ، في شريط الإجراءات، حدد **Voucher**.

1. في صفحة **Voucher transactions** ، أشر إلى عمود **Ledger account**.  
    هنا نرى النتائج مرحلة في دفتر الأستاذ العام. يتم تحديد حسابات دفتر الأستاذ العام من خلال إعداد الحساب والأبعاد المالية المطبقة على كل مشروع.

1. استعرض للوصول إلى مساحة عمل **Project management** . 

1. في جدول **Active projects** ، حدد **00000093 Contoso Consulting project**.

1. في صفحة **Contoso Consulting** ، في شريط التنقل، حدد **Control**.  
    من هنا يمكننا رؤية جميع تفاصيل المشروع.  
    بعد ذلك، لنلق نظرة على البيانات المالية للمشروع في بيان المشروع.

1. حدد **Project statements**.

1. في صفحة **Project statements** ، أشر إلى قسم **PROJECT DATE** .  
يمكنك إنشاء بيان لأي نطاق تاريخ تريده.

1. حدد مربع **From date**، وأدخل **2/1/2021**.
1. 
1. حدد المربع **To date** ، وأدخل تاريخ اليوم.

1. عند الانتهاء، حدد **Calculate**.

    ![لقطة شاشة لصفحة بيانات المشروع مع تمييز خيار الحساب.](./media/projops_invoice_4_calculate.png)

1. أشر إلى **Transactions**.  
    بمجرد تحديث البيانات، يمكن لمدير المشروع اختيار التعمق أكثر في تفاصيل الحركات لاتخاذ قرارات المشروع أو إجراء التعديلات حسب الضرورة.في هذا العرض التوضيحي، قمنا بمعالجة فاتورة الوقت والمواد مع كل من معاملة الساعة والمصروفات. نظرنا إليها في المعاينة، ثم قمنا بنشر الفاتورة، وراجعنا ترحيل دفتر الأستاذ، وأخيرًا راجعنا التأثير المالي من خلال كشف المشروع هذا.
