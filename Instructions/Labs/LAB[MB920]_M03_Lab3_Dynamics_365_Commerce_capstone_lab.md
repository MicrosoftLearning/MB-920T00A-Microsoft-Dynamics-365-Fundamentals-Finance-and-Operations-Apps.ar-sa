---
lab:
  title: 'النشاط المعملي 3: النشاط المعملي لمشروع التخرّج Dynamics 365 Commerce'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: c498966dc4b2bba78b4e0d27077c4b346666323f
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909156"
---
## <a name="lab-3---dynamics-365-commerce-capstone-lab"></a>المعمل 3 - معمل مشروع التخرّج Dynamics 365 Commerce

## <a name="objective"></a>الهدف

خلال هذا التمرين المعملي، سوف تستكشف أساسيات إعداد المقر الرئيسي للتجارة. تشمل الميزات الأساسية إعداد قناة البيع بالتجزئة وإنشاء عملية فرز وتكوين خصم البيع بالتجزئة.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 30 دقيقة 

## <a name="instructions"></a>الإرشادات

## <a name="exercise-1-explore-commerce-headquarters"></a>التمرين 1: استكشاف المقرات التجارية

### <a name="create-a-new-store"></a>إنشاء متجر جديد

1. في الصفحة المقصودة، أعلى اليسار، تحقق من تحديد شركة **USRT**.

1. إذا لم يكن الأمر كذلك، فحدد الشركة المدرجة حاليًا ثم أدخل **USRT**.

1. باستخدام جزء التنقل، حدد **الوحدات** > **البيع بالتجزئة والتجارة** > **القنوات** > **المتاجر** > **جميع المتاجر**.

1. في Action Pane، حدد  **+New** لإنشاء متجر جديد.

1. في نافذة السجل الجديد، استخدم الإعدادات الموجودة في الجدول التالي لتحديث القيم:

    | **الإعداد**| **القيمة**|
    | :--- | :--- |
    | الاسم| متجر سياتل فلاجشيب|
    | رقم المتاجر| 000098|
    | المستودع| سياتل|
    | مستودع الشحن| سياتل|
    | المنطقة الزمنية للمتجر| (GMT-08: 00) توقيت المحيط الهادئ|
    | ملف تعريف الوظائف| FN001|
    | البحث في المخزون| نعم|
    | ملف تعريف القناة| افتراضي|
    | ملفات التعريف غير المتصل| افتراضي|
    | مجموعة ضريبة المبيعات| واشنطن|
    | استخدم الضرائب المستندة إلى الوجهة| نعم|
    | دفتر عناوين العميل| RetailCust|
    | دفتر عناوين الموظف| سياتل|
    | العميل الافتراضي| 3002|

1. في جزء الإجراءات، حدد **حفظ**.

1. حدد علامة التبويب السريعة **بيان/إغلاق** ثم أدخل التحديثات التالية:

    | إعداد| القيمة|
    | :--- | :--- |
    | حساب مبلغ البيان| الأخير|
    | أقصى فرق > الترحيل| 100.00|

1. حدد علامة التبويب السريعة **الأبعاد المالية** ثم أدخل التحديثات التالية:

    | إعداد| القيمة|
    | :--- | :--- |
    | وحدة العمل| 004|
    | قناة البيع بالتجزئة| 000210|

1. حدد علامة التبويب السريعة **تخطيط الشاشة**.

1. في مربع **Screen layout ID**، أدخل  **A2CP16:9C**.

1. في جزء الإجراءات، حدد **حفظ**.

1. في Action Pane، حدد  **Set-up**، ثم في علامة تبويب **COPY**، حدد **Copy all**.

1. في جزء **Copy all**، حدد قائمة **From store** ثم حدد **ANNAPOL**.

1. إذا لزم الأمر، حدد قائمة **To store** ثم حدد **00098**.

1. حدد  **OK**.

1. تحقق من ظهور رسالة النجاح ثم أغلق الصفحة.

### <a name="add-a-group-of-products-to-an-assortment-and-publish"></a>أضف مجموعة من المنتجات إلى عملية فرز وانشرها

1. باستخدام جزء التنقل، حدد  **Modules** > **Organization administration** > **Organizations** > **Organization hierarchies**.

1. في قائمة التنقل، حدد **متاجر البيع بالتجزئة حسب المنطقة**.

1. في Action Pane، حدد  **View**.

1. في صفحة Hierarchy designer page، في Action Pane، حدد  **Edit**.

1. في الإطار المتجانب **West**، حدد أيقونة علامة الحذف ( **...** ).

1. في صفحة Hierarchy designer، حدد  **Insert** > **Retail channel**.

1. في جزء **قناة البيع بالتجزئة**، حدد **متجر سياتل فلاجشيب** ثم حدد **موافق**.

1. في جزء الإجراءات، حدد **حفظ**.

1. في مربع الحوار، راجع المعلومات ثم حدد **إغلاق**.

1. في Action Pane، حدد  **Publish**.

1. في جزء **نشر التغييرات**، في مربع **تاريخ السريان**، حدد اليوم الأول من الشهر الحالي.

1. في مربع **Describe changes**، أدخل  **Addition of Seattle Flagship Store**  ثم حدد  **Publish**.

1. في مربع الحوار، راجع المعلومات ثم حدد **إغلاق**.

1. في جزء الإجراءات، حدد **حفظ**.

1. في مربع الحوار، راجع المعلومات ثم حدد **إغلاق**.

1. أغلق الصفحة.

1. باستخدام جزء التنقل، حدد  **Modules** > **Retail and Commerce** > **Catalogs and assortments** > **Assortments**.

1. في صفحة Assortments، حدد  **AW-Outlet**.

1. في Action Pane، حدد  **Edit**.

1. في مربع الحوار، حدد  **Yes**  لتأكيد تحديد التحرير.

1. في صفحة AW-Outlet، حدد علامة التبويب السريعة **قناة التجارة**.

1. على شريط الأدوات، حدد  **+Add line**.

1. في جزء **Choose organization nodes**، حدد قائمة **Organization hierarchy** ثم حدد  **Retail Stores by Region**.

1. ضمن **AVAILABLE ORGANIZATION NODES**، حدد  **Seattle Flagship Store** ثم حدد أيقونة السهم الأيمن **Add** لإضافتها إلى **SELECTED ORGANIZATION NODES**.

1. حدد  **OK**.

1. في Action Pane، حدد  **Publish**.

1. في مربع الحوار، راجع المعلومات ثم حدد  **Yes**.

1. في Action Pane، حدد  **Edit**.

1. في مربع حوار **confirmation**، حدد  **Yes**.

1. في صفحة AW-Outlet، حدد علامة تبويب **المنتجات**.

1. في صفحة AW-Outlet، حدد **+ إضافة سطر**.

1. حدد قائمة **Category**، وحدد  **Team Sports**، ثم حدد  **OK**.

1. في Action Pane، حدد  **Publish**.  

### <a name="run-the-retail-scheduler-job-for-products"></a>قم بتشغيل وظيفة جدولة البيع بالتجزئة للمنتجات

1. باستخدام جزء التنقل، حدد  **Modules** > **Retail and Commerce** > **Retail and Commerce IT** > **Distribution schedule**.

1. في قائمة التنقل، حدد  **1040 (Products)** .

1. في Action Pane، حدد  **Run now**.

1. في جزء **Incremental sync with schedule '1040'** ، راجع المعلومات ثم حدد  **OK**.

### <a name="create-a-new-product-discount"></a>قم بإنشاء خصم منتج جديد

1. باستخدام جزء التنقل، حدد  **Modules** > **Retail and Commerce** > **Pricing and discounts** > **All discounts**.

1. في Action Pane، حدد  **New** > **Discount**.

1. في صفحة Discounts، في مربع **Name**، أدخل  **Store Opening**.

1. في علامة التبويب السريعة **Details**، في مربع **Description**، أدخل  **Store Opening 20% Off**.

1. في علامة التبويب السريعة **Price/discount**، في مربع **Discount percentage**، أدخل  **20.00**.

1. في علامة التبويب السريعة **فترة السريان**، في مربع **تاريخ السريان**، أدخل تاريخًا من الشهر السابق.

1. في مربع **تاريخ انتهاء الصلاحية**، أدخل تاريخًا بعد أسبوع واحد من التاريخ الحالي.

1. في علامة التبويب السريعة **السطور**، في شريط الأدوات، حدد **+ إضافة**.

1. ضمن عمود **الفئة**، حدد القائمة، وحدد **الرياضات الجماعية**، ثم حدد **موافق**.

1. في جزء الإجراءات، حدد **حفظ**.

1. في Action Pane، حدد  **Price groups**.

1. في صفحة Price groups، حدد قائمة **Price groups** ثم حدد  **West**.

1. في جزء الإجراءات، حدد **حفظ**.

1. باستخدام جزء التنقل، حدد  **Modules** > **Retail and Commerce** > **Pricing and discounts** > **All discounts**.

1. في قائمة التنقل، حدد  **ST100101**.

1. في علامة التبويب السريعة **General**، حدد قائمة **Status** ثم حدد  **Enabled**.

1. في جزء الإجراءات، حدد **حفظ**.

1. أغلق النموذج.

1. باستخدام جزء التنقل، حدد  **Modules** > **Retail and Commerce** > **Retail and Commerce IT** > **Distribution schedule**.

1. في قائمة التنقل، حدد  **1020 (Products)** .

1. في Action Pane، حدد  **Run now**.

1. في جزء **Incremental sync with schedule '1020'** ، راجع المعلومات ثم حدد  **OK**.
