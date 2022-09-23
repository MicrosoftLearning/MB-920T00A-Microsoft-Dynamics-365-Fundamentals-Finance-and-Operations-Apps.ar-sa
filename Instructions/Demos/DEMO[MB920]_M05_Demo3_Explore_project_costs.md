---
demo:
  title: 'العرض التوضيحي 3: استكشاف تكاليف المشروع'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>العرض التوضيحي 3 - استكشف تكاليف المشروع

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. في **Dynamics 365 for Finance and Operations**، في جزء التنقل، حدد **الوحدات > إدارة المشاريع ومحاسبتها > الجداول الزمنية > جداولي الزمنية (مُحسّنة لأجهزة المحمول)** .  
    للبدء، على الرغم من أنني لست على جهاز محمول في الوقت الحالي، فسوف تتعرف على النماذج على أنها متوافقة مع الجوّال بعد أن نختار الخيار **جداولي الزمنية (مُحسّنة لأجهزة المحمول)** .

    ![لقطة شاشة لقائمة إدارة المشاريع والمحاسبة مع إبراز جداولي الزمنية (مُحسّنة لأجهزة المحمول).](./media/projops_costs_1_select_my_timesheets.png)  

    هذا التحسين هو عامل تمييز رئيسي لتطبيقات أعمال Microsoft ويساعد في ضمان وجود حد أدنى من منحنى التعلم بين استخدام الويب والهاتف المحمول.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. في صفحة **جداولي الزمنية**، حدد **جديد**.  
    سنقوم الآن بإنشاء جدول زمني جديد يعتمد على الإعدادات التي تم تكوينها.

1. في **جزء الجدول الزمني الجديد**، أشر إلى المربع **التاريخ.**  
    سيحدد التاريخ الذي تم إدخاله فترة الجدول الزمني.

1. أشر إلى **إنشاء من المفضلة**.  
    إذا كانت لديك مفضلات محفوظة، فيمكنك تحديد الإنشاء منها لتوفير الوقت.

1. عند الاكتمال، حدد **OK**.

1. في صفحة **تفاصيل جداولي الزمنية**، حدد **جديد +** .

1. في **جزء سطر الجدول الزمني الجديد**، أشر إلى مربع **الكيان القانوني.**  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. حدد قائمة **معرف المشروع.**

1. حدد أحد المشاريع المتاحة، مثل مشروع **Contoso Consulting**.

1. عند الاكتمال، حدد **OK**.  
    ستفتح شاشة الهاتف المحمول المحسّنة لإدخال الوقت ويمكنك البدء في حجز ساعاتك كل يوم للمشروع والفئة، في هذه الحالة **الخدمة**.

1. في صفحة **إدخال الوقت**، في مربع **الاثنين**، أدخل **8**.  
    هذا يمثل إدخال ساعات يوم واحد.

    ![لقطة شاشة لصفحة إدخال الوقت.](./media/projops_costs_2_mon_box.png)

1. في هذا العرض التوضيحي، سنتعرف على كيفية إنشاء إدخال الوقت والنفقات الذي سيتم تحميله على مشروع Contoso Consulting.  
    يمكنك أيضًا إدخال تعليقات داخلية وخارجية ضد المشروع لضمان فهم جميع الأطراف لطبيعة الساعات التي يتم تسجيلها.

1. سنستكشف الإدخالات بتنسيقات محسّنة للويب والعرض التقديمي للجوال، وسنرى كيف يتم استخدام سير العمل لإدارة عملية الموافقة.

1. في شريط التنقل، حدد **حفظ**.

1. في قائمة التنقل اليسرى، تحت **الجداول الزمنية،** حدد **جداولي الزمنية.**

1. في صفحة **جداولي الزمنية**، حدد إدخال الوقت الذي قمت بإنشائه مسبقًا.

1. في علامة التبويب **الجدول الزمني**، أشر إلى عمود الفئة.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. ضمن **تفاصيل السطر**، أشر إلى **التعليق الداخلي والتعليق** **الخارجي**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. في شريط التنقل، انقر فوق علامة التبويب **سير العمل**.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. في جزء **مراجعة سير عمل الجدول الزمني**، حدد **إرسال**.

1. في جزء **مراجعة سير عمل الجدول الزمني - إرسال**، أضف أي تعليقات إضافية.

1. حدد **"Submit"**.

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. في صفحة **حركات الساعة**، قم بمراجعة الصفحة.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

بعد ذلك، يمكننا التعمق في حركات الإيصال.

1. في شريط التنقل، حدد **الإيصال**.

1. في صفحة **حركات الإيصال**، أشر إلى القسمين **حساب دفتر الأستاذ** و**اسم الحساب**.  
    في هذه الأقسام يمكننا أن نرى التأثير على دفتر الأستاذ العام، وكذلك الحسابات التي سيتم استخدامها.  

لنقم الآن بإنشاء إدخال مصاريف لنفس المشروع الاستشاري لشركة Contoso.

1. في جزء التنقل، حدد **الوحدات > إدارة المصروفات > مصروفاتي > تقارير المصروفات**.

1. في صفحة **إدارة المصروفات**، في علامة التبويب **التقارير**، حدد **+ تقرير مصروفات جديد**.

1. في منتقي الشركة العلوي الأيمن، تحقق من أن الكيان القانوني الذي تتصل به هو **USSI**.

1. حدد "**OK**".

1. في صفحة **المصروفات**، حدد **+ مصروفات جديدة**.  
سيظهر خط حساب جديد.

1. في **عمود فئة المصاريف**، حدد **وقود** من قائمة **الفئة** المنسدلة.  
هنا، يمكننا إدخال المصروفات الجديدة مع تفاصيل عنها.

1. في عمود **مبلغ الحركة**، أدخل **25.00**.

1. في عمود **العملة**، حدد **الدولار الأمريكي**.

1. إذا لم يكن كذلك، قم بتغيير الكيان القانوني إلى **USSI**.  
    بمجرد إدخال جميع التفاصيل، يمكنك حفظ المصروفات.

1. حدد ⁧**⁩حفظ⁧**⁩.

1. في قائمة التنقل اليمنى، ضمن **مساحات العمل**، حدد **إدارة المصروفات**.

1. في صفحة **إدارة المصروفات**، حدد تقرير المصروفات الذي أنشأته للتو.

1. في صفحة **تقرير المصروفات**، حدد مربع **معرف المشروع** ثم حدد **00000093 Contoso Consulting**.  

بعد ذلك، يمكننا الإشارة إلى أنه سيتم تحميل الوقود على مشروع Contoso Consulting، بالإضافة إلى معلومات إضافية حول المصروفات.

1. قم بالإشارة إلى مربع **معلومات إضافية**.

1. في الجانب الأيمن السفلي من الشاشة، حدد **حفظ ومتابعة**.

1. على الجانب الأيمن من الشاشة، حدد **إرسال**.

1. في مربع **التعليق**، أضف أي تعليقات إضافية.

1. حدد **"Submit"**.

1. في **صفحة إدارة المصروفات**، أشر إلى عمود **حالة الموافقة.**  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
