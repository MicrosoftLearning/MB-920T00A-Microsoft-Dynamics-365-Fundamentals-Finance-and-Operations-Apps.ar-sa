---
title: تعليمات مستضافة عبر الإنترنت
permalink: index.html
layout: home
ms.openlocfilehash: f4e2e1489e1997cfd064aa74eb5345e302bb2424
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ar-SA
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909275"
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
