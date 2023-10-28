# **Задание №2**

1. 15:29:49.336262: loading io.vertx    -   Старт загрузки классов в Metaspace из внешней библиотеки io.vertx

![step1](image/step1.jpg)

2. 15:29:49.517250: loaded 529 classes  -   Закончена загрузка классов в Metaspace из внешней библиотеки io.vertx 

![step2](image/step2.jpg)

3. 15:29:52.524133: loading io.netty    -   Старт загрузки классов в Metaspace из внешней библиотеки io.netty

![step3](image/step3.jpg)

4. 15:29:52.816981: loaded 2117 classes -   Закончена загрузка классов в Metaspace из внешней библиотеки io.netty 

![step4](image/step4.jpg)

5. 15:29:55.822092: loading org.springframework -   Старт загрузки классов в Metaspace из внешней библиотеки org.springframework

![step5](image/step5.jpg)

6. 15:29:55.930187: loaded 869 classes  -   Закончена загрузка классов в Metaspace из внешней библиотеки org.springframework (память в Metaspace не увеличилась)

![step6](image/step6.jpg)

7. 15:29:58.936864: creating 5000000 objects    -   Старт создания списка из 5 млн SimpleObject в heap (куче) 

![step7](image/step7.jpg)

8. 15:29:59.076221: created -   окончание создания списка из 5 млн SimpleObject в heap (куче) 

![step8](image/step8.jpg)

9. Выделение памяти в heap (куче) для добавления в созданный список новый список из 5 мил SimpleObject

![step9](image/step9.jpg)

10. 15:30:02.081757: creating 5000000 objects    -   Старт создания нового списка из 5 млн SimpleObject в рамках выделенной памяти
11. 15:30:02.228420: created    -   окончание создания нового списка из 5 млн SimpleObject в heap (куче)

![step10](image/step10.jpg)

12. Выделение памяти в heap (куче) для добавления в созданный список новый список из 5 мил SimpleObject

![step11](image/step11.jpg)

13. 15:30:05.261295: creating 5000000 objects    -   Старт создания нового списка из 5 млн SimpleObject в рамках выделенной памяти
14. 15:30:05.372490: created    -   окончание создания нового списка из 5 млн SimpleObject в heap (куче)
