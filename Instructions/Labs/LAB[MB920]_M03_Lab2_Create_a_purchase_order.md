---
lab:
  title: 'تمرين معملي 2: إنشاء أمر شراء'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# الوحدة 3: تعلم أساسيات إدارة سلسلة إمداد Microsoft Dynamics 365

## تمرين معملي 2: إنشاء أمر شراء

## إعداد المعمل

   - **الوقت المقدر**: 15 دقيقة

## الهدف

في هذا التمرين العملي‬، ستصبح عَلى دراية بواجهة المستخدم والحقول المختلفة المتاحة فِي نموذج أمر الشراء. تتعلم أيضاً كيفية إنشاء أمر شراء جديد.


## إعداد المعمل

   - **الوقت المُتوقع**: 10 دقائق

## الإرشادات

1. في صفحة التمويل والعمليات الرئيسية، أعلى اليسار، تحقق مِن أنك تعمل مع شركة **USMF**. إذا لزم الأمر،فحدد الشركة، ومن القائمة المنسدلة، حدد **USMF**.

2. في الجزء العلوي الأيسر، حدد القائمة عَلى شكل هامبرجر **توسيع جزء التنقل**.

3. حدد **الوحدات** > **التدبير والتوريد** > **أوامر الشراء‬‏‫** > **جميع أوامر الشراء‬‏‫**.

4. في صفحة **جميع أوامر الشراء**، فِي القائمة العلوية، حدد **+جديد**.

5. في جزء‬ **إنشاء أمر شراء**، حدد القائمة المنسدلة **حساب المورد**، ثم حدد **US-101**.

> [!NOTE]
> ملاحظة: عند تحديد مورد، يتم نسخ التفاصيل من سجل المورد، مثل العنوان وحساب الفاتورة وشروط التسليم ووضع التسليم كقيم افتراضية في عنوان الطلب. يمكنك تغيير هذه القيم فِي أي وقت.

6. قم بتوسيع القسم **عام** إذا لزم الأمر.

7. ضمن **أبعاد التخزين**، حدد القائمة المنسدلة **الموقع**، واستعرض قائمة المواقع.

يحدد حقل **الموقع**، جنباً إلى جنب مع حقل **المستودع**، مكان تسليم البضائع أو الخدمات المشتراة. يكون عنوان التسليم الافتراضي هو الموقع. يمكن ملء كلا الحقلين بقيم تم إعدادها للبائع المحدد، أو يمكنك تحديدها يدوياً.

8. ضمن **التواريخ**، يُستخدم حقل **تاريخ التسليم** لتحديد وقت الحاجة إلى تسليم البضائع والخدمات المشتراة.

    يمكنك تحديد تاريخ تسليم واحد للأمر، أو يمكن تحديد تواريخ تسليم فريدة لبنود الأمر الفردية. إذا كان تاريخ التسليم المحدد هنا لا يمكن الوفاء به لمنتجات أو خدمات معينة لأن لها فترات زمنية أطول، فسيتم إنشاء هذه البنود بتاريخ تسليم لاحق.

9. وسّع قسم **الإدارة**. يمكن استخدام مربع **مقدم الأمر** لتحديد مِن يقدم الأمر.

    قد يكون هذا مناسباً لمشاركته مع المورد فِي حالة الحاجة إلى الاتصال بهذا الشخص. يمكن تعيين القيمة تلقائياً إذا كان حساب المستخدم الحالي مرتبطاً باسم عَلى صفحة **المستخدمون**.

10. حدد **موافق**.

لقد تم الآن إنشاء رأس الأمر. عندما تعمل مع بنود أمر الشراء، يتم عرض ملخص لمعلومات الرأس فقط. إذا كنت بحاجة إلى عرض باقي المعلومات، فحدد **البيانات الرئيسية**.

![لقطة الشاشة توضح عنوان الطلب حيث يتم عرض ملخص معلومات الطلب. يتم تمييز كلمة العنوان.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. ضمن **‬‏‫بنود أمر الشراء‬‏‫**، فِي القائمة، حدد **بند أمر الشراء**.

![لقطة شاشة تصور بنود أوامر الشراء.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. ضمن **العرض**، حدد **الأبعاد**.

    يمكن أن تكون المنتجات متباينة حسب الأبعاد، مثل اللون أو الحجم أو النمط. يمكن أيضاً إعداد المنتجات لاستخدام أبعاد التخزين، مثل الموقع والمستودع. وهناك أيضًا أبعاد للتعقب اختيارية، مثل الدفعة والأرقام التسلسلية. لتحسين كفاءة إدخال الأمر، يمكنك إضافة حقول الأبعاد التي تستخدمها بشكل شائع مباشرةً إلى شبكة الأمر.

13. في جزء **عرض الأبعاد**، ضمن ‏‫**أبعاد المنتج**، حدد خانة اختيار **اللون**.

اختياري: إذا حددت مفتاح تبديل **حفظ الإعداد**، فستظهر الأبعاد التي حددتها أيضاً فِي شبكة بند الأمر فِي المرة التالية التي تفتح فيها صفحة أمر الشراء.

14. حدد **موافق**.

15. حدد القائمة المنسدلة خلية **رقم الصنف**، ثم حدد **T0004**.

تذكّر أنه يمكنك أيضاً الكتابة فِي مربع التصفية بدلاً مِن التمرير عبر القائمة.

يتم إنشاء بنود الأمر للمنتجات والخدمات عن طريق تحديد رقم صنف أو كمصروفات عن طريق تحديد فئة تدبير.

تُستخدم فئة التدبير لإضافة البنود حيث يتم إنفاق الأصناف المشتراة كمصروفات مباشرة، بدلاً مِن الانتقال إلى المخزون. إذا كنت بحاجة إلى إجراء عملية شراء، فيمكنك القيام بذلك عن طريق إنشاء بند أمر شراء يحدد فئة تدبير، بدلاً مِن إنشاء بند برقم صنف. يمكن أيضاً ربط الأصناف بفئة تدبير وفي هذه الحالة، يتم عرض فئة التدبير كمعلومات فقط.

16. حدد القائمة المنسدلة **اللون**، وراجع الخيارات المتاحة، ثم حدد أحد الألوان أو مجموعات الألوان.

17. عادةً ما يتم ملء **الموقع** و**المستودع** بقيم مِن البيانات الرئيسية للأمر، ولكن مِن الممكن تجاوز الحقول إذا كانت هناك حاجة لتسليم بعض البنود إلى مواقع مختلفة.

18. في مربع **الكمية**، أدخِل **10**.

    يتم ملء **الكمية** تلقائياً بالحد الأدنى لكمية الأمر للمنتج إذا تم إعداده، أو بالقيمة **1**.

19. بعض المعلومات الإضافية:

- **الوحدة**: يشير إلى وحدة القياس للكمية المطلوبة. عادةً، يتم توفير الوحدة تلقائياً مِن وحدة الشراء عَلى البيانات الرئيسية للمنتج.

- **سعر الوحدة**: يحتوي عَلى قيمة إما مِن اتفاقية شراء أو اتفاقية تجارة. من الممكن تغيير سعر الوحدة فِي بنود الأمر الفردية - فمثلاً، إذا تم التفاوض عَلى سعر فريد مع المورد.

- **الخصم**: يمثل مبلغ خصم لكل وحدة. وبالتالي، فإن هذا الخصم يقلل مِن سعر الوحدة بالخصم. عادةً ما يتم توفير هذا الخصم تلقائياً مِن اتفاقيات الشراء أو اتفاقيات التجارة، ولكن مِن الممكن تجاوز البنود الفردية إذا تم التفاوض عَلى خصومات فريدة مع المورد.

- **نسبة الخصم**: عند إدخاله، يؤدي ذلك إلى تقليل المبلغ الصافي للبند وفقًا لذلك. عادةً ما يتم توفير نسبة الخصم تلقائياً مِن اتفاقيات الشراء أو اتفاقيات التجارة، ولكن مِن الممكن تجاوز البنود الفردية إذا تم التفاوض عَلى نسبة خصم فريدة مع المورد.

- **المبلغ الصافي**: يتم حسابه مِن الحقول الأخرى فِي البند، بما فِي ذلك الكمية وسعر الوحدة والخصم والنسبة المئوية للخصم. من الممكن تغيير صافي المبلغ، لكن حقول سعر الوحدة والخصم والنسبة المئوية للخصم فارغة. عندما تقوم بعد ذلك بالنشر باتجاه البند، فإن المبلغ الذي تم ترحيله سيكون متناسبًا مع المبلغ الصافي. يتم استخدام حقل المبلغ الصافي لعرض المبلغ الصافي للبند فقط.

20. ضمن بنود أمر الشراء، فِي أسفل الصفحة، حدد **تفاصيل البند**.

21. حدد علامة التبويب **التسليم**.

    يمكن تعيين تاريخ تسليم فريد لكل بند أمر. يكون التاريخ مكتسباً مِن الحقل الموجود فِي رأس أمر الشراء، ولكن يمكنك تغيير ذلك.

22. أغلق صفحة **بند أمر الشراء**.

23. في صفحة "**All purchase orders**"، استخدم ميزة "التصفية" وابحث عن أمر الشراء الجديد.

24. عند الانتهاء، أغلق صفحة "**All purchase orders**" وعُد إلى الصفحة الرئيسية.

