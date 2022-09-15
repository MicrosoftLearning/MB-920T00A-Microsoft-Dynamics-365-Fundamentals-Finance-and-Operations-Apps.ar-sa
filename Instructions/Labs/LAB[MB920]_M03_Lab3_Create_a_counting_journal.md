---
lab:
  title: 'النشاط المعملي 3: إنشاء دفتر يومية الجرد'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>الوحدة الثالثة: تعرف على أساسيات Microsoft Dynamics 365 - Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>النشاط معملي 3 إنشاء دفتر يومية الجرد

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. في جزء التنقّل الأيسر، حدد **Modules** > **Inventory management** > **Journal entries** > **Item counting** > **Counting**.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. سيظهر نموذج دفتر يومية جرد المخزون مع معلومات العنوان والتفاصيل

![لقطة شاشة لنموذج دفتر يومية جرد المخزون مع تعبئة معلومات العنوان والتفاصيل.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. حدد **Create lines -&gt; Online** في جزء الإجراءات.

6. في جزء مربع الحوار **Create on-hand counting journal**، قم بتعيين حقول **Warehouse** و**Inventory Status**, وLocation و**License Plate** إلى **Yes**. 

![لقطة شاشة لجزء مربع الحوار Create on-hand counting journal مع تعيين الحقول كما هو موضح.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. حدد **OK** في أسفل نموذج مربع الحوار **Create on-hand counting journal**.

ستظهر الكمية الموجودة للعنصر A0001 في قسم **Journal lines** مع تقسيم لوحة Site وWarehouse وLocation وLicense.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - إذا كانت كمية **On-hand** هي نفس كمية **Counted**، فسيكون حقل **Quantity** فارغًا.

    - إذا كانت قيمة الحقل **Counted** أكثر من الحقل **On-hand**، فسيحتوي الحقل **Quantity** على قيمة موجبة.

    - إذا كانت قيمة الحقل **Counted** أقل من الحقل **On-hand**، فسيحتوي الحقل **Quantity** على قيمة سالبة.

10. حدد الزر **Validate** في جزء الإجراءات، ثم حدد الزر **Post**.

11. أغلق الصفحة وارجع إلى الصفحة الرئيسية.
