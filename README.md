# CT.Test
CT.Test-API-JAVA<br>
имеется 2 объекта - "Организация" (orgObj__c) и "Контактное лицо" (People__c)<br>
orgObj__с имеет следующие поля:<br>
-  Город     City__c         (text)<br>
-  Индекс    Index__c        (text)<br>
-  Обновить  Update__c       (checkbox)<br>
-  Описание  Description__c  (text)<br>
-  Страна    Country__c      (text)<br>
-  Улица     Street__c       (text)<br>
<br>
People__c имеет следующие поля:<br>
-  Email         (text)<br>
-  Должность     (text)<br>
-  Моб. телефон  (text)<br>
-  Организация   (lookup(организация))<br>
-  Фамилия Имя   (text)<br>
<br>
1 задача - файл testTrigger.apxt<br>
2 задача - файлы page1.vfp, myControl.apxc
