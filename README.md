# OOAD-WEEK08

## แก้ไขเพิ่มเติม (code and picture)

![](http://www.plantuml.com/plantuml/img/imf8BCbCpIknuhA2iNHrxJGSKt8pIqfIKpHHXHCB2l8pyqfoWVnYDAdanBpad5G5F2eA4Yk18WeWe_CoYqkAW59bgGekgGM9HM3rLdWbaKmeoKXLA80OZ6oVGd5oHcfAQKvcNheLSQgmU8bORTYzgv2IdroINwHWXSH43Ku0)

1.At Hospital

Code :

:Patient:

:Patient:-->(Admitted)

:Patient:-->(appointments)

:Patient:-->(cancle appointments)

:Patient:-->(pay)

: Administrative Department:

: Administrative Department:-->(pay)

: the patient appointment scheduling:

: the patient appointment scheduling:-->(appointments)

: the patient appointment scheduling:-->(cancle appointments)

: doctor :

: doctor :-->(Admitted)
-------------------------------------------------------------------------------------

![](http://www.plantuml.com/plantuml/img/dP5D2W8n38NtSuhkd5dq0bru0YyHQwo1_a2IBWGFxpYjoY3eu2hmtlSIaZZHUiAipjhzo1X85DcS2njVAWlADBWZnKWv6BdEPlf6Dfc15yWpWcAtZGU5M4B53svJimIKbI0RoZEMGAdaQNZBBRUJbM_jxNSoejVAVqNxyRP7tQ4DQpi9FcQ_BgJ5A8A_hB6nQxrQwvul6-u0)

2.At school

Code : 

:student:-->(register for courses)

:billing system:-->(register for courses)

:registrar:-->(create course catalogue)

:registrar:-->(register for courses)

:registrar:-->(maintian information)

(maintian course's information)--|>(maintian information)

(maintian lecture's information)--|>(maintian information)

(maintian student's information)--|>(maintian information)

:Lecturer:-->(selecte course to teach)

:Lecturer:--(teach)

(teach)--:student:

-------------------------------------------------------------------------------------------------------

![](http://www.plantuml.com/plantuml/img/iyfDBKhEICmhiUAooas54Bgw6acbbGe5HVaffSabcbmeF5rTEojKFK0HZOB4IaqkX3X8g2WrEJMpB5KXDpyl5IY9nWUfI4ajo2_EB86fW9bLdbcIaLAKM9wOeya50000)

3.At store

code :

:merchant:

:me:

:me:--(buy product)

(buy product)-->:merchant:

:me:-->(pay)

:merchant:-->(receive money)

(receive money)-->(deposit money)

:me:-->(withdrawal)

-------------------------------------------------------------------------------------------------------
![](http://www.plantuml.com/plantuml/img/iyhDpxNYid99J06IkQbGfeAkhePFVbcg9XU4qjMriq8e14hc9XOLLG9b8JH26aG2fPDp4i6Q8JHO6cWq0000)

4.At home

code :

:mom:

:Dad:

:me:

:Dad: --(Love)

(Love)-->:mom:

:Dad:--(marry)

(marry)-->:mom:

:mom:--(clave)

(clave)-->:me:

-------------------------------------------------------------------------------------------------------------------------------------
![](http://www.plantuml.com/plantuml/img/ROvB2e0m34JtEKMMkiW5YhZn0buXI56nFzf8yVR-Ajsu2ZFlCGH0XUZdoDRgg8Zw9iTLD9Qo1L33diH_L9RLRPWN5ipivERis1n97ZnhmQduly9es5tTUpkYkWvGFA96s6mOYbh3FL2_RKy0)

5.at software company

Code :

:programmer:-->(write program)

:Customer:-->(think what want)

:analyst:-->(get customer want)

:analyst:-->(Plan)

(Plan)<--:Customer:

analyst--(talk plan)

(talk plan)-->(programmer)

## Use Case Diagram (ภาษาไทย)
* บรรยายเรื่อง UML โดย อ.ปานใจ  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/0eq2FGEQul8/0.jpg)](http://www.youtube.com/watch?v=0eq2FGEQul8 "บรรยายเรื่อง UML โดย อ.ปานใจ  " target="_blank") 

* เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case   

[![IMAGE ALT TEXT](http://img.youtube.com/vi/u9sNT6x0Mlo/0.jpg)](http://www.youtube.com/watch?v=u9sNT6x0Mlo "เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case " target="_blank") 

* How to draw a UML Use Case Diagram

[![IMAGE ALT TEXT](http://img.youtube.com/vi/UzprPX82Nac/0.jpg)](http://www.youtube.com/watch?v=UzprPX82Nac "How to draw a UML Use Case Diagram" target="_blank") 

## Use Case Diagram Tutorial (VTC)

* 3.01_Use Case Basics  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/tLJXJLfLCCM/0.jpg)](http://www.youtube.com/watch?v=tLJXJLfLCCM " 3.01_Use Case Basics " target="_blank") 

* 3.02_Modeling Use Case Elements  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/_JCsqdNf8bA/0.jpg)](http://www.youtube.com/watch?v=_JCsqdNf8bA " 3.02_Modeling Use Case Elements " target="_blank") 
 
* 3.03_A Use Case Diagram for an ATM  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/SmcBTsPsbIY/0.jpg)](http://www.youtube.com/watch?v=SmcBTsPsbIY " 3.03_A Use Case Diagram for an ATM" target="_blank") 

 

* 3.04_The ''include'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/q7O2EAZ_s7M/0.jpg)](http://www.youtube.com/watch?v=q7O2EAZ_s7M " 3.04_The ''include'' Dependency " target="_blank") 

 

* 3.05_The ''extend'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/bL_Bl_Xl7wQ/0.jpg)](http://www.youtube.com/watch?v=bL_Bl_Xl7wQ " 3.05_The ''extend'' Dependency" target="_blank") 

 
* 3.06_Generalization  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/x5LkaZlLT28/0.jpg)](http://www.youtube.com/watch?v=x5LkaZlLT28 " 3.06_Generalization" target="_blank") 

 
* 3.07_Putting It All Together  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/gYmOzpU7DDI/0.jpg)](http://www.youtube.com/watch?v=gYmOzpU7DDI " 3.07_Putting It All Together" target="_blank") 


 
