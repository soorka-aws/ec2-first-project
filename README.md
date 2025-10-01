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
![EC2 Running](screenshots/my-ec2-instance.png)
### ✅ 2) نوع الإنستانس المستخدم (اختياري)
![Instance Type](screenshots/my-ec2-type.png)
### ✅ 3) فتح الموقع من المتصفح
![Website View](screenshots/my-ec2-website.png)
ملاحظات
- إذا لم يفتح الموقع، غالبًا المنفذ 80 غير مفعَّل في Security Group.
- مهم حذف أو إيقاف الموارد بعد الانتهاء لتجنب أي تكلفة على الحساب.
---

### 🛡️ Security Group Configuration

#### أثناء إنشاء الـEC2
![Security Group During Creation](screenshots/security-group-during-creation.png)

#### بعد تشغيل الـEC2
![Security Group After Running](screenshots/security-group-after-running.png)
## 🟠 S3 Static Website Hosting

### 1. إنشاء البكت
![S3 Bucket Creation](screenshots/my-s3-bucket.png)

### 2. إعدادات Public Access
![S3 Public Access Settings](screenshots/s3-public-access.png)

### 3. تفعيل Static Website Hosting
![S3 Static Website Configuration](screenshots/s3-static-hosting.png)

### 4. صفحة الموقع بعد التشغيل
![S3 Website Live](screenshots/s3-website-live.png)
