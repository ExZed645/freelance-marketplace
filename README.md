# freelance-marketplace
نام پروژه: پلتفرم فریلنسری
اعضای تیم: سید مهدی موسوی نیا
پایگاه داده انتخابی: PostgreSQL
لینک برد جیرا: https://mosavimehdi645.atlassian.net/jira/software/projects/SCRUM/boards/1?sprintStarted=true&filter=&groupBy=none
هدف پروژه: طراحی و پیاده‌سازی پلتفرم فریلنسری جهت ارتباط کارفرمایان و فریلنسران
checking pull request



Design decisions:
برای مدیریت ادمین‌ها از ستون is_admin در جدول کاربران استفاده شده است و اعمال محدودیت عدم ثبت پروژه/پیشنهاد توسط مدیران، در لایه بیزینس‌لاژیک (Application Layer) برنامه‌نویسی کنترل می‌شود.
