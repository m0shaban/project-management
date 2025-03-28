# Project Management System

نظام إدارة مشاريع متكامل مبني بواسطة Flask

## المميزات الرئيسية

- إدارة المشاريع والمهام
- مصفوفة أيزنهاور لترتيب أولويات المهام
- إدارة الفرق والأقسام
- لوحة تحكم للمدراء
- إشعارات وتقارير متقدمة

## متطلبات التشغيل

- Python 3.13+
- Flask
- SQLAlchemy
- Database (SQLite للتطوير، PostgreSQL للإنتاج)

## كيفية التثبيت

```bash
# استنساخ المستودع
git clone https://github.com/yourusername/project-management.git

# إنشاء بيئة افتراضية
python -m venv venv
source venv/bin/activate  # لينكس/ماك
venv\Scripts\activate     # ويندوز

# تثبيت المتطلبات
pip install -r requirements.txt

# تهيئة قاعدة البيانات
flask db upgrade
flask init-db

# تشغيل التطبيق
flask run
```

## الواجهات الرئيسية

1. **لوحة التحكم**: عرض المشاريع والمهام الحالية
2. **إدارة المشاريع**: إنشاء وتعديل وحذف المشاريع
3. **إدارة المهام**: تنظيم المهام وتحديد حالتها
4. **مصفوفة أيزنهاور**: ترتيب المهام حسب الأهمية والإلحاح
5. **إدارة الفريق**: دعوة أعضاء وإدارة الأقسام

## المساهمة في المشروع

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:
1. انشاء fork للمشروع
2. إنشاء فرع جديد: `git checkout -b feature-name`
3. الالتزام بتغييراتك: `git commit -m 'إضافة ميزة جديدة'`
4. رفع الفرع: `git push origin feature-name`
5. إنشاء طلب سحب

## الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف LICENSE للتفاصيل
