---
title: تعليمات مستضافة عبر الإنترنت
permalink: index.html
layout: home
---

# <a name="content-directory"></a>دليل المحتوى

تم سرد الارتباطات التشعبية لكل من التدريبات والعروض التوضيحية المعملية أدناه.

## <a name="labs"></a>الأنشطة المعملية

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| الوحدة النمطية | التمرين المعملي |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## <a name="demos"></a>العروض التوضيحية

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| الوحدة النمطية | Demo |
| --- | --- | 
{% للنشاط في العرض التوضيحي %}| {{ activity.demo.module }} | [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
