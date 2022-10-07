---
lab:
  title: 'النشاط المعملي 3: إنشاء دفتر يومية الجرد'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>الوحدة الثالثة: تعرف على أساسيات Microsoft Dynamics 365 - Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>النشاط معملي 3 إنشاء دفتر يومية الجرد

1. في صفحة Finance and Operations الرئيسية، أعلى اليمين، تحقق من أنك تعمل مع شركة **USMF**. إذا لزم الأمر، حدد الشركة ومن القائمة المنسدلة، حدد **USMF**.

2. في جزء التنقّل الأيسر، حدد **Modules** > **Inventory management** > **Journal entries** > **Item counting** > **Counting**.

3. حدد زر **+New** في جزء الإجراءات. سيظهر نموذج الحوار **Create inventory journal** مع الزر **OK** في الأسفل. حدد الزر **موافق**.

4. سيظهر نموذج دفتر يومية جرد المخزون مع معلومات العنوان والتفاصيل

![لقطة شاشة لنموذج دفتر يومية جرد المخزون مع تعبئة معلومات العنوان والتفاصيل.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. حدد **Create lines -&gt; Online** في جزء الإجراءات.

6. في جزء مربع الحوار **Create on-hand counting journal**، قم بتعيين حقول **Warehouse** و**Inventory Status**, وLocation و**License Plate** إلى **Yes**. 

![لقطة شاشة لجزء مربع الحوار Create on-hand counting journal مع تعيين الحقول كما هو موضح.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. قم بتوسيع القسم **Record to include** وحدد الارتباط **Filter**. في الحقل **Item number**، حدد **A0001**، ثم حدد **OK**.

8. حدد **OK** في أسفل نموذج مربع الحوار **Create on-hand counting journal**.

ستظهر الكمية الموجودة للعنصر A0001 في قسم **Journal lines** مع تقسيم لوحة Site وWarehouse وLocation وLicense.

9. في العمود **Counted** من قسم **Journal line**، أدخل الأرقام التي تم حسابها في كل لوحة Site/Warehouse/Location/License. لاحظ ما يلي:

    - إذا كانت كمية **On-hand** هي نفس كمية **Counted**، فسيكون حقل **Quantity** فارغًا.

    - إذا كانت قيمة الحقل **Counted** أكثر من الحقل **On-hand**، فسيحتوي الحقل **Quantity** على قيمة موجبة.

    - إذا كانت قيمة الحقل **Counted** أقل من الحقل **On-hand**، فسيحتوي الحقل **Quantity** على قيمة سالبة.

10. حدد الزر **Validate** في جزء الإجراءات، ثم حدد الزر **Post**.

11. أغلق الصفحة وارجع إلى الصفحة الرئيسية.
