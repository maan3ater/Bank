تمرین سوم درس مباحث ویژه در برنامه نویسی
هستی سالک چهارشنبه 13:30

۱. منابع پروژه (Resources)
این پروژه دو منبع اصلی دارد:
 کاربران (Users): ذخیره اطلاعات کاربران.
 وظایف (Tasks): ذخیره اطلاعات وظایف کاربران.
۲. آدرس‌های مربوط به کاربران (Users Endpoints)

/users    	GET   	200
/users	    POST	  201
/users/{id}	DELETE	204
۳. آدرس‌های مربوط به وظایف (Tasks Endpoints)

/tasks    	GET   	200
/tasks    	POST   	201
/tasks/{id}	PUT   	200
/tasks/{id}	DELETE	204
۴. دیاگرام معماری (Architecture Diagram)

flowchart TD
A[رابط کاربری] --> B[بخش سرور و API]
B --> C[پایگاه داده]
