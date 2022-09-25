---
demo:
  title: 'العرض التوضيحي 2: إنشاء فاتورة'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>العرض التوضيحي 2 - إنشاء فاتورة

1. استعرض للوصول إلى مساحة عمل  **Project management**.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1. في جدول  **Active projects** ، في عمود **Project ID** ، حدد **00000093 Contoso Consulting**.  

1. بعد ذلك، افتح صفحة **Project invoice proposals** لعرض جميع الفواتير السابقة التي تمت معالجتها لشركة Contoso Consulting. 

1. في جزء الإجراءات، في علامة التبويب **BILL** ، حدد  **Project invoice proposals**. 

1. في صفحة **Project invoice proposals** ، في شريط التنقل، حدد **New**، ثم **Invoice proposal**.  
    هذه فاتورة بسيطة للوقت والمواد، لذلك لا نحتاج إلى تحديد خيار مقترح الفاتورة من قاعدة الفوترة. 

    ![لقطة شاشة لصفحة مقترحات فواتير المشروع مع تمييز مقترح فاتورة جديد.](./media/projops_invoice_1_new_invoice_proposal.png)

1. في الجزء **Create invoice proposal** ، أشر إلى المربعات الموجودة ضمن **Select transactions**.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![لقطة شاشة لجزء إنشاء مقترح فاتورة مع تمييز قسم "تحديد الحركات".](./media/projops_invoice_2_select_transactions.png)

1. من القائمة المنسدلة **Project** ، حدد **00000093 Contoso Consulting**. 

1. في هذا المثال، تأكد من تعيين **Invoice date** إلى **2/1/21** وتعيين **Start date** إلى **2/1/21**، و"end date" هو تاريخ اليوم.  
    بمجرد إجراء التحديدات، حدد زر البحث للعثور على الحركات التي تلبي هذه المعايير.

1. حدد **Search**.  
    في هذا العرض التوضيحي، سننتقل إلى عملية فوترة مشروع واحد ضمن عمليات المشروع.

1. ضمن علامة التبويب **Project transactions** ، حدد **Select all**.

1. حدد  **OK**. 

1. في صفحة **Invoice proposal** ، أشر إلى عمود **Invoice line amount** .  
    هنا يمكننا رؤية مبلغ الفاتورة والملخص، وساعات العمل، والمصروفات.

    ![لقطة شاشة لصفحة مقترح الفاتورة مع تمييز عمود مبلغ سطر الفاتورة.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. أشر إلى علامة التبويب **Hour** . 

1. أشر إلى علامة التبويب **Expense**.  
    يمكنك أيضًا التبديل وإلقاء نظرة على حركة المصروفات.  
بعد ذلك، لنتحقق من زر الإجماليات لنرى كيف ستبدو الفاتورة من منظور التكلفة والإيرادات.

1. في شريط التنقل، حدد **Totals**.

1. في صفحة **Totals**، أشر إلى عمود **GENERAL LEDGER**، وعمود **CUSTOMER** ، وعمود **Line discount**.  
    في شاشة الإجماليات، يمكننا معرفة التأثير الذي سيكون على دفتر الأستاذ العام وأي معلومات خاصة بالعميل مثل حدود الائتمان وأي خصومات وضرائب المبيعات والتأثير الصافي للفاتورة. 

1. على الجانب الأيمن من الشاشة، حدد **X** لإغلاق الصفحة.  
    على الرغم من أنه من الممكن إجراء فواتير جماعية، إلا أننا سنركز، لأغراض توضيحية، على مرة واحدة فقط وعلى مشروع فعلي. 

1. في صفحة **Invoice proposal** ، في شريط التنقل، حدد **Print preview**. 

1. في مربع الحوار، حدد **Print preview**.  
    يمكنك هنا مشاهدة مثال على معاينة الطباعة لفاتورة أولية. 

1. حدد **X** لإغلاق الصفحة.  
    بمجرد أن نتحقق من صحة جميع المعلومات ونكون راضيين عن معاينة طباعة الفاتورة، يمكننا ترحيل مقترح الفاتورة.

1. في شريط التنقل، حدد **Post**.

1. حدد علامة التبويب **Parameters** .

1. ضمن **PARAMETER**، عين **Posting** إلى **Yes**.

1. ضمن **PRINT OPTIONS**، عين **Print invoice** إلى **Yes**.

1. حدد  **OK**.

1. في صفحة **Invoice** ، أشر إلى رقم **Invoice**.  
    الآن لدينا رقم فاتورة تم إنشاؤه.  
    بعد ترحيل الفاتورة، يمكننا مراجعة المعلومات الموجودة في دفتر يومية الفواتير والانتقال إلى حركات دفتر الأستاذ.

1. استعرض للوصول إلى مساحة عمل  **Project management**.

1. في جدول **Active projects** ، حدد مشروع **00000093** **Contoso consulting**.

1. في جزء الإجراءات، في علامة التبويب **BILL** ، حدد **Invoice journals**.

1. في صفحة **Invoice journal** ، في شريط الإجراءات، حدد **Voucher**.

1. في صفحة **Voucher transactions** ، أشر إلى عمود **Ledger account**.  
    سنرى أيضًا نتائج الترحيل والرؤى المالية في بيان المشروع.

1. استعرض للوصول إلى مساحة عمل **Project management** . 

1. في جدول **Active projects** ، حدد **00000093 Contoso Consulting project**.

1. في صفحة **Contoso Consulting** ، في شريط التنقل، حدد **Control**.  
    من هنا يمكننا رؤية جميع تفاصيل المشروع.  
    بعد ذلك، هيا نلقي نظرة على البيانات المالية للمشروع في كشف المشروع.

1. حدد **Project statements**.

1. في صفحة **Project statements** ، أشر إلى قسم **PROJECT DATE** .  
يمكنك إنشاء كشف لأي نطاق زمني تريده.

1. حدد مربع **From date**، وأدخل **2/1/2021**.
1. 
1. حدد المربع **To date** ، وأدخل تاريخ اليوم.

1. عند الانتهاء، حدد **Calculate**.

    ![لقطة شاشة لصفحة كشوف المشروع مع تمييز خيار الحساب.](./media/projops_invoice_4_calculate.png)

1. أشر إلى **Transactions**.  
    لنبدأ بفوترة المشروع.
