
# 4kings

เป็นเว็บไซต์คัดสรรสถาบัน 4kings โดยในหลังบ้านจะเลือกใช้ภาษา Python เป็นหลักในการเขียนฝั่ง Server และในการคำนวณการคัดสรรสถาบันจะใช้ Machine learning เข้ามาช่วยโดยจะใช้ NLP(Natural Language Processing) มาคำนวณ ซึ่งจะใช้เป็น library ของคนไทย คือ PyThaiNLP เพื่อรับข้อมูลเป็นภาษาไทยและคำนวณผลลัพท์ออกมา และการรับส่งข้อมูลก็จะใช้ Websocket ทำให้สามารถส่งและรับข้อมูลได้แบบ Real time ภายในเว็บก็จะมีการตรวจจับ error ต่างๆก่อนส่งข้อมูล หน้าเว็บไซต์ก็รองรับการแสดงผลแบบ Responsive

# วิธีติดตั้ง
ติดตั้ง Python ลงเครื่อง
[Python](https://www.python.org/downloads/)

เปิด command prompt เลือก file path ที่ต้องการจะเก็บไฟล์ไว้ และเข้าถึงไฟล์ผ่านคำสั่ง cd
```bash
cd filepath
```
clone ไฟล์จาก git ลงเครื่อง
```bash
git clone https://github.com/ArmNonthakon/4kings.git
```
เข้าไปในไฟล์โฟลเดอร์
```bash
cd 4kings
```
ติดตั้ง dependency ต่างๆ
```bash
pip install fastapi uvicorn[standard] numpy pythainlp websocket 
```
run คำสั่ง
```bash
python -m uvicorn main:app --reload
```
run web on port [127.0.0.1:8000](http://127.0.0.1:8000/)
## Link url
หรือคลิกที่ link [4kings-click me!!](https://deploy-4kings.onrender.com/)
## เครดิต

 - [PyThaiNLP](https://pythainlp.github.io/)


