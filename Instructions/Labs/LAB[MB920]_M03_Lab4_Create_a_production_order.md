---
lab:
  title: 'النشاط المعملي 4: قم بإنشاء أمر إنتاج'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 527cbbf9cb2265d48ab2b2ba8fb6516632b46cf1
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116231"
---
## <a name="lab-4---create-a-production-order"></a>النشاط المعملي 4 - إنشاء أمر إنتاج

## <a name="objectives"></a>الأهداف

يحتوي أمر الإنتاج على معلومات حول ما سيتم إنتاجه والكمية المطلوب إنتاجها وتاريخ الانتهاء المخطط له. يحتوي أيضًا على معلومات حول المواد التي يجب استهلاكها والعملية التي يجب اتباعها لإنتاج العنصر.

يجب عليك إنشاء أمر إنتاج جديد لشركتك.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 5 minutes

## <a name="instructions"></a>الإرشادات

1. في صفحة Finance and Operations الرئيسية، أعلى اليسار، تحقق من أنك تعمل مع شركة USMF.

1. إذا لزم الأمر، حدد الشركة ومن القائمة، حدد **USMF**.

1. في جزء التنقل الأيسر، حدد **Modules** > **Production control** > **Production orders** > **All production orders**.

1. في القائمة العلوية، حدد **أمر إنتاج جديد**.

1. ضمن **المعرف**، في المربع **رقم العنصر**، أدخل **D0001**، ثم حدد العنصر المحدد.

1. ضمن **الإنتاج**، في مربع **التسليم**، حدد تاريخًا بعد شهر واحد من تاريخ اليوم.  
    يشير تاريخ التسليم إلى موعد انتهاء أمر الإنتاج للتسليم في الوقت المحدد. يمكن استخدام هذا التاريخ في عملية الجدولة. على سبيل المثال، يمكنك جدولة الطلب بأثر رجعي من تاريخ التسليم.

1. في مربع **Quantity**، أدخل **20**.

1. ضمن **مكونات العنصر/المسار**، يعرض حقل رقم قائمة مكونات العنصر تلقائيًا رقم أي قائمة مكونات عنصر نشطة للعنصر الحالي، ولكن يمكنك تغيير قائمة مكونات العنصر لأمر الإنتاج عن طريق تحديد قائمة مكونات عنصر نشطة من قائمة إصدارات قائمة مكونات العنصر المعتمدة. يعرض حقل رقم المسار تلقائيًا رقم أي مسار نشط للعنصر الحالي، ولكن يمكنك تغيير المسار لأمر الإنتاج بتحديد مسار نشط من قائمة إصدارات المسار المعتمدة.

    ![صورة شاشة تعرض جزء إنشاء أمر إنتاج بالكامل](./media/lp1-m4-new-production-order-pane.png)

1. حدد **Create**.