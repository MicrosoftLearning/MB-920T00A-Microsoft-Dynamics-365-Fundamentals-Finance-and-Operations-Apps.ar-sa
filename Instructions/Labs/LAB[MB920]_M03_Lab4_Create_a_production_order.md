---
lab:
  title: 'النشاط المعملي 4: قم بإنشاء أمر إنتاج'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>النشاط المعملي 4 - إنشاء أمر إنتاج

## <a name="objectives"></a>الأهداف

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

يجب عليك إنشاء أمر إنتاج جديد لشركتك.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 5 minutes

## <a name="instructions"></a>الإرشادات

1. في صفحة Finance and Operations الرئيسية، أعلى اليسار، تحقق من أنك تعمل مع شركة USMF.

1. إذا لزم الأمر، حدد الشركة ومن القائمة، حدد **USMF**.

1. في جزء التنقل الأيسر، حدد **Modules** > **Production control** > **Production orders** > **All production orders**.

1. في القائمة العلوية، حدد **أمر إنتاج جديد**.

1. ضمن **المعرف**، في المربع **رقم العنصر**، أدخل **D0001**، ثم حدد العنصر المحدد.

1. ضمن **الإنتاج**، في مربع **التسليم**، حدد تاريخًا بعد شهر واحد من تاريخ اليوم.  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. في مربع **Quantity**، أدخل **20**.

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![صورة شاشة تعرض جزء إنشاء أمر إنتاج بالكامل](./media/lp1-m4-new-production-order-pane.png)

1. حدد **Create**.
