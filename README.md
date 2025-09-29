# ec2-first-project
Documentation of creating and running an EC2 server on AWS with practical screenshots.
# مشروع تشغيل سيرفر EC2 على AWS

## الهدف
إنشاء خادم (Server) باستخدام خدمة EC2 من AWS وتجهيزه بحيث يمكن الوصول له من المتصفح.

## الخطوات التي تم تنفيذها:
- إنشاء EC2 Instance
- اختيار نوع الإنستانس (مثل t3.micro)
- ضبط Security Group وفتح منفذ 80
- تشغيل السيرفر والتأكد أن حالته Running
- نسخ الـ Public IP وتجربته في المتصفح

## لقطات الشاشة

### ✅ 1) السيرفر شغال وفيه الـ Public IP
![EC2 Running](screenshots/my ec2 server)

### ✅ 2) نوع الإنستانس المستخدم (اختياري)
![Instance Type](screenshots/my instance type)

### ✅ 3) فتح الموقع من المتصفح
![Website View](screenshots/my-ec2-website)

## ملاحظات
- إذا لم يفتح الموقع، غالبًا المنفذ 80 غير مفعَّل في Security Group.
- مهم حذف أو إيقاف الموارد بعد الانتهاء لتجنب أي تكلفة على الحساب.
