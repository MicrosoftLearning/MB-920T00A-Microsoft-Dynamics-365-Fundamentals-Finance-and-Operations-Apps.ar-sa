---
lab:
  title: 'النشاط المعملي 2: تكامل Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116223"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>الوحدة الأولى: استكشاف الإمكانات الأساسية لتطبيقات التمويل والعمليات من Dynamics 365

## <a name="lab-2---excel-integration"></a>النشاط المعملي 2 - تكامل Excel

الآن بعد أن أصبحت على دراية بتطبيقات التمويل والعمليات، استغرق بعض الوقت لاستكشاف سيناريو تكامل Excel.

### <a name="task-1-create-template"></a>المهمة #1: إنشاء قالب

1. افتح الصفحة الرئيسية Finance and Operations. 

2. انتقل إلى **Modules** > **Common** > **Common** > **Office Integration** > **Excel Workbook** **Designer**. لاحظ أن معظم التنقل يتم عبر الوحدات، لذلك لا يتم تحديد ذلك عادةً.

3. ابحث عن **VendorGroup** في عامل التصفية.

4. من قائمة الحقول المتوفرة، حدد الحقول **Vendor group** و **Description** و **Terms of payment** وانقلها إلى مربع الحقل المحدد عن طريق تحديد السهم الأيمن.

5. في جزء الإجراءات، حدد الزر **Create workbook**.

6. على اليمين، في لوحة **Save To**، حدد الزر **Download**.

7. نزل الملف عن طريق تحديد **Save As** وتخزينه في مجلد **Downloads**.

8. انتقل إلى **Common** > **Office Integration** > **Document** **templates**.

9. حدد **"جديد"**.

10. في اللوحة اليمنى، في قسم **Upload template**، حدد الزر **Browse** وحدد الملف الذي تم تنزيله مسبقًا (إذا استخدمت الاسم الافتراضي، فهو DynamicsWorkbook).

11. في حقل **Template name**، أدخل **CustomVendorGroup**.

12. حدد **OK**، ثم حدد **Save**.

### <a name="task-2-open-in-excel"></a>المهمة رقم 2: فتح في Excel

1. انتقل إلى **Procurement and sourcing** > **Setup** > **Vendors** > **Vendor groups**.

2. حدد **Open in Microsoft Office** > **Open in Excel** للعثور على القالب الجديد، CustomVendorGroup، الذي قمت بتحميله.

3. حدد **CustomVendorGroup** وقم بتنزيل قالب Excel.

4. احفظ قالب Excel الذي تم تنزيله ثم افتحه، واسمح به إذا لزم الأمر، وأغلق التنشيط، وحدد **Enable editing**. ثق بهذه الوظيفة الإضافية، ثم سجل الدخول (باستخدام بيانات الاعتماد نفسها، إذا طلب منك ذلك).

ستظهر جميع البيانات الموجودة في جدول Vendor group في جدول بيانات Excel.

5. أدخل سجلاً جديدًا.

6. أدخل **100** في حقل **Vendor group**،و **Insurance Vendor** في حقل **Description**، و **Net10** في حقل **Terms of payment**.

7. حدد الزر **Publish** في تطبيق الوظيفة الإضافية لـ Microsoft Dynamics Office.

8. افتح نموذج **Vendor group** للتحقق من إضافة السجل الجديد.

