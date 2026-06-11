โปรแกรมมี devcontainer แล้วสามารถทดสอบได้ผ่าน devcontainer เลยไม่ต้องเตรียม environment ใหม่
jdk 25 พร้อม mariadb และ postgresql สำหรับทดสอบ

คำสั่งที่ใช้
mvn spring-boot:run

กรณีที่เจอว่าไฟล์ migration ซ้ำให้ทำการล้างข้อมูลที่ folder target ก่อน
คำสั่งล้างของมูลที่ target 
mvn clean
