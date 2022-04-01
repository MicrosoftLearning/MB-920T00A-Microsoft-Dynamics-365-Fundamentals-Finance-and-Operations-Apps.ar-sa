---
lab:
  title: 'النشاط المعملي 5: قم بإنشاء مستودع'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 919ea602b0768683acd845dd184b3bf5a0364fd0
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909172"
---
# <a name="module-1-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>الوحدة الأولى: تعرف على أساسيات Microsoft Dynamics 365 - Supply Chain Management

## <a name="lab-5---create-a-warehouse"></a>المعمل 5 - إنشاء مستودع

## <a name="objectives"></a>الأهداف
يمنحك نظام إدارة المستودعات في Supply Chain Management طرقًا مرنة لتحديد تخطيط المستودع الخاص بك لتلبية الاحتياجات المتغيرة، بحيث يمكنك تحقيق الكفاءة المثلى للمستودع.

- يمكنك إنشاء مناطق تخزين ذات أولوية عالية ومنخفضة الأولوية لوضع البضائع على النحو الأمثل.
- يمكنك تقسيم المستودع الخاص بك إلى مناطق لتلبية احتياجات التخزين المختلفة، مثل متطلبات درجة الحرارة، أو معدلات الدوران المختلفة للعناصر.
- يمكنك تحديد مواقع المستودعات على أي مستوى (على سبيل المثال، الموقع والمستودع والممر والحامل والرف وموضع الصندوق).
- يمكنك تجميع المواقع باستخدام إعدادات قيود السعة المادية.
- يمكنك التحكم في كيفية تخزين العناصر وانتقاءها، استنادًا إلى القواعد المحددة بواسطة الاستعلام.

لاستخدام إدارة المستودعات في Supply Chain Management، يجب عليك إنشاء مستودع وتمكينه لأنشطة إدارة المستودعات الأكثر تقدمًا أو تخصصًا.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 10 دقائق

## <a name="instructions"></a>الإرشادات

1. في صفحة Finance and Operations الرئيسية، أعلى اليسار، تحقق من أنك تعمل مع شركة USMF.

1. إذا لزم الأمر، حدد الشركة، ومن القائمة، حدد **USMF**.

1. في جزء التنقل الأيمن، حدد **Modules** > **Inventory management** > **Setup** > **Inventory breakdown** > **Warehouses**.

    ![صورة شاشة تعرض التنقل في وحدة المستودعات](./media/lp1-m3-warehouses-module-navigation.png)

1. في صفحة المستودعات، في القائمة العلوية، حدد **New**.

1. في **Warehouse**، أدخل **101**.

1. في حقل **Name**، أدخل **Overflow Warehouse**.

1. حدد قائمة **Site**، ثم حدد **3 Home foam production**.

1. وسّع **Location names**.  
    تحدد الخيارات الموجودة في هذا القسم التنسيق الافتراضي لأسماء المواقع.

1. اضبط خياري **Include aisle** و **Include rack** على **Yes**.

1. في مربع **Format**، للحامل، أدخل قيمة.  
    على سبيل المثال، إذا كان يجب أن يحتوي تنسيق اسم موقع الحامل على OVFL، فيمكنك إدخال هذه القيمة في مربع التنسيق.

1. ضمن **LEVEL**، اضبط خيار **Include shelf** على **Yes**.

1. في حقل **Format**، للحامل، أدخل **-##** .

1. في القائمة العلوية، حدد **Warehouse**.

    ![صورة شاشة تعرض خيار قائمة المستودعات مميزًا](./media/lp1-m3-warehouses-menu-option.png)

1. ضمن **Maintain**، حدد **Location Wizard**.

1. في صفحة الترحيب، راجع المعلومات ثم في الزاوية اليمنى السفلية، حدد **Next**.

1. ألغ تحديد مربعات الاختيار **Outbound docks** و **Bulk locations**.

1. حدد **Next** وراجع المعلومات.

1. تابع إلى كل صفحة ثم، عند الانتهاء، حدد **Finish**.

1. أغلق الصفحة وارجع إلى الصفحة الرئيسية.
