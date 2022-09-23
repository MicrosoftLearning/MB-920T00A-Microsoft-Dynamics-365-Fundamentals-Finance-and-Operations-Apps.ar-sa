---
lab:
  title: 'النشاط المعملي 2: إنشاء أوامر شراء'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>الوحدة الثالثة: تعرف على أساسيات Microsoft Dynamics 365 - Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>النشاط معملي 2 - إنشاء أمر شراء

## <a name="objectives"></a>الأهداف

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>إعداد النشاط المعملي

   - **الزمن المقدر**: 10 دقائق

## <a name="instructions"></a>الإرشادات

1. في صفحة Finance and Operations الرئيسية، أعلى اليسار، تحقق من أنك تعمل مع شركة USMF.

1. إذا لزم الأمر، حدد الشركة، ومن القائمة، حدد **USMF**.

1. في الجزء العلوي الأيسر، حدد القائمة على شكل هامبرجر **توسيع جزء التنقل**.

1. حدد **الوحدات** > **التدبير والتوريد** > **أوامر الشراء** > **كل أوامر الشراء**.

1. في صفحة كل أوامر الشراء، في القائمة العلوية، حدد **+ جديد**.

1. في جزء إنشاء أمر شراء، حدد قائمة **حساب المورد**، ثم حدد **US-101**.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. قم بتوسيع القسم **عام.**

1. ضمن **أبعاد التخزين**، حدد قائمة **الموقع**، وراجع قائمة المواقع.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. ضمن **التواريخ**، يتم استخدام حقل تاريخ التسليم لتحديد وقت الحاجة إلى تسليم البضائع والخدمات المشتراة.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. من المعتاد أن يتم إنشاء أوامر الشراء تلقائيًا كنتيجة للتخطيط الرئيسي والتسليم المباشر والعمليات الأخرى.

1. حدد "**OK**".

1. عند إنشائه يدويًا، يتم عادةً إنشاء أمر الشراء بواسطة وكيل الشراء.

    ![صورة شاشة تعرض موقع قائمة الرأس](./media/lp1-m3-purchase-order-header-option.png)

1. ضمن **سطور أمر الشراء**، في القائمة، حدد **سطر أمر الشراء**.

    ![صورة شاشة توضح موقع خيار قائمة سطر أمر الشراء](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. ضمن **العرض**، حدد **الأبعاد**.

1. قم بإنشاء أمر شراء باستخدام شركة USMF.

1. في جزء عرض الأبعاد، ضمن **أبعاد المنتج**، حدد خانة الاختيار **اللون.**

1. اختياري: إذا حددت مفتاح تبديل حفظ الإعداد، فسيتم أيضًا عرض الأبعاد التي اخترتها على شبكة سطر الأمر في المرة التالية التي تفتح فيها صفحة أمر الشراء.

1. حدد "**OK**".

1. حدد قائمة الخلية **رقم العنصر**، ثم حدد **T0004**.

1. تذكر أنه يمكنك أيضًا الكتابة في مربع التصفية بدلاً من التمرير عبر القائمة.

1. يتم إنشاء بنود الأمر للمنتجات والخدمات عن طريق تحديد رقم عنصر أو كمصروفات عن طريق تحديد فئة تدبير.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. حدد **قائمة الألوان**، وراجع الخيارات المتاحة، ثم حدد أحد الألوان أو مجموعات الألوان.

1. عادةً ما يتم ملء الموقع والمستودع بقيم من رأس الأمر، ولكن من الممكن تجاوز الحقول إذا كانت هناك حاجة لتسليم بعض السطور إلى مواقع مختلفة.

1. في مربع **الكمية**، أدخل **10**.

1. يتم ملء الكمية تلقائيًا بالحد الأدنى لكمية الطلب للمنتج إذا تم إعداده، أو بالقيمة 1.

1. بعض المعلومات الإضافية:

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. أسفل سطور أمر الشراء، في أسفل الصفحة، حدد **تفاصيل السطر**.

1. حدد علامة التبويب **التسليم**.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. أغلق صفحة سطر أمر الشراء.

1. في صفحة جميع أوامر الشراء، استخدم ميزة التصفية وابحث عن أمر الشراء الجديد.

1. عند الانتهاء، أغلق صفحة جميع أوامر الشراء وعُد إلى الصفحة الرئيسية.
