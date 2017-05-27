# Unturned Convert Item Picture

โปรแกรม PHP ที่จะช่วยให้คุณสามารถแปลงชื่อไฟล์รูปภาพของ Item ในเกม Unturned หลายๆไฟล์ให้เหลือเพียงแค่ตัวเลขเฉยๆในครั้งเดียวได้
เพื่อนำภาพที่ได้ไปใช้ในการทำระบบอื่นต่อไป

- - - -
### ตัวอย่าง

    Jeans_Work_2.png => 2.png
    
- - - -
### โปรแกรมที่จำเป็น
     
* Apache หรือ Software อื่นๆที่สามารถรัน PHP ได้ (AppServ,WampServer,XAMPP)
    
- - - -
### วิธีใช้งาน

1. คัดลอกไฟล์ภาพจากตัวเกม Unturned (...\Unturned\Extras\Icons\...)
2. นำไปใส่ใว้ที่โฟเดอร์ Icons ในโปรแกรม (หรือตามแต่ที่ตั่งค่าใว้)
3. ทำการรันโปรแกรมด้วย Apache หรือ Software อื่นๆที่สามารถรัน PHP ได้
4. ไฟล์ที่ถูกแก้ใขชื่อแล้วจะอยู่ในโฟเดอร์ IconsNew ในโปรแกรม (หรือตามแต่ที่ตั่งค่าใว้)

- - - -
### การตั่งค่า

ใน index.php

~~~php
// โฟเดอร์ตั่งต้นของไฟล์รูปภาพ
$dirInput = 'Icons';

// โฟเดอร์ขาออกของไฟล์รูปภาพที่ถูกเปลี่ยนชื่อแล้ว
$dirOutput = 'IconsNew';
~~~

- - - -
### Cradit

* GSV.IN.th (Art_Masster)

- - - -