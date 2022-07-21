---
lab:
  title: 'النشاط المعملي 2: إنشاء فرز منتج'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: d6c414c266f0403139dc31de38f602b5a0290ef5
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909270"
---
## <a name="lab-2---create-a-product-assortment"></a>المعمل 2 - إنشاء عملية فرز منتج

## <a name="objectives"></a>الأهداف

تحتاج إلى إنشاء مجموعة متنوعة من المنتجات ذات الصلة التي تم تخصيصها لقناة تجارية محددة والتي سيتم إتاحتها في تاريخ لاحق.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 10 دقائق

## <a name="instructions"></a>الإرشادات

1. في صفحة Finance and Operations، في أعلى اليسار، حدد القائمة على شكل هامبرجر **توسيع جزء التنقل**.

1. في جزء التنقل، حدد **البيع بالتجزئة والتجارة** > **الكتالوجات وعمليات الفرز** > **عمليات الفرز**.

1. انتظر حتى يتم تحميل الصفحة.

1. في صفحة عمليات الفرز، حدد **+ جديد**.

1. في جزء سجل جديد، قم بتوسيع **عام**.

1. حدد مربع **تاريخ السريان**، ثم حدد تاريخًا في المستقبل.

1. في مربع **اسم عملية الفرز**، أدخل اسمًا لعملية الفرز الجديدة. على سبيل المثال، **موسم الربيع الجديد**.

1. اضبط **تاريخ انتهاء الصلاحية** على **أبدًا**.

1. يمكن استخدام تاريخ انتهاء الصلاحية لإلغاء تنشيط عملية فرز منشورة تلقائيًا.

1. قم بتوسيع **قنوات التجارة**.

1. في قائمة قنوات التجارة، حدد **+ إضافة سطر**.

1. في اختيار عقد المؤسسة، حدد قائمة **التسلسل الهرمي للمؤسسة**، ثم حدد **متاجر البيع بالتجزئة حسب النوع (Fabrikam)** .

1. في قائمة عقد المؤسسة المتاحة، حدد متصل، ثم حدد إضافة ![أيقونة السهم الأيمن](./media/d365-fo-add-org-node-icon.png) لإضافتها إلى **عُقد المؤسسة المحددة**.  
  سيؤدي هذا إلى إضافة العقدة الأصلية وجميع العقد الفرعية.

1. أضف العقدة الرئيسية **المركز التجاري**، ثم حدد **موافق**.

1. تحقق من إضافة العقدتين إلى قنوات التجارة.

1. قم بتوسيع **المنتجات**.

1. في قائمة المنتجات، حدد **+ إضافة سطر**.

1. حدد **قائمة الفئة**، وحدد **الرياضات الجماعية (الرياضات الجماعية)** ، ثم حدد **موافق**.

1. سيؤدي هذا إلى إضافة جميع العناصر الفرعية للفئة الأصل.

1. راجع العمود الأخير المسمى **نوع السطر**. بشكل افتراضي، سيتم تضمين كافة العناصر.

1. حدد **+ إضافة سطر**، وحدد قائمة **الفئة**، وقم بتوسيع **الرياضات الجماعية (الرياضات الجماعية)** ، وحدد **البيسبول**، ثم حدد **موافق**.

1. لاستبعاد عنصر من فئة أكبر مضمنة بالفعل، في هذه الحالة الرياضات الجماعية، في عمود نوع السطر، قم بتغيير القيمة إلى **استبعاد**.

1. باستخدام صف فئة البيسبول، حدد قائمة **المنتجات**.

1. عندما يتم تحديد منتجات ضمن فئة، يمكنك تحديد منتج معين لتضمينه أو استبعاده. حدد **ملعب البيسبول للكبار**.

1. لإزالة منتج مضاف، احذف محتويات مربع المنتج، ثم اضغط على مفتاح Tab في لوحة المفاتيح أو حدد منطقة أخرى من الصفحة.

1. في القائمة العلوية، حدد **حفظ**.

1. في القائمة العلوية، حدد **نشر**.

1. راجع المعلومات الموجودة في مربع الحوار، ثم حدد **نعم**.

1. ستصبح تشكيلة المنتجات التي تم إنشاؤها حديثًا متاحة في تاريخ السريان.