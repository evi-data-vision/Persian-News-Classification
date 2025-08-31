# 📰 Persian News Classification (SVM / Traditional NLP)

این پروژه اخبار فارسی را با استفاده از روش‌های پردازش زبان طبیعی کلاسیک و الگوریتم **SVM** دسته‌بندی می‌کند. 
پیش‌پردازش متن فارسی با ابزارهای **Hazm** و/یا **Parsivar** انجام شده و ویژگی‌ها با روش‌هایی مثل **TF‑IDF** استخراج می‌شوند. نوت‌بوک در Google Colab/لوکال قابل اجراست.

---

## 📂 ساختار پروژه
- `Persian_News.ipynb`: نوت‌بوک اصلی شامل:
  - دانلود دیتاست (Kaggle یا منبع دیگر)
  - پاک‌سازی متن و نرمال‌سازی فارسی (حذف علائم/اعداد/فاصله‌های اضافی، normalize، stemming/lemmatization در صورت استفاده)
  - استخراج ویژگی‌ها (Bag-of-Words / TF‑IDF)
  - آموزش و ارزیابی مدل (SVM)

> 📌 توجه: اگر در کد مسیرهای Colab مثل `/content/...` وجود دارد، هنگام اجرا مطابق محیط خود تنظیم کنید.
> برای دانلود خودکار از Kaggle به `kaggle.json` در مسیر `~/.kaggle/` نیاز دارید (آن را عمومی نکنید).

---

## 🧰 تکنولوژی‌ها
- Python 3.x
- Pandas
- scikit-learn (برای TF‑IDF و SVM)
- Hazm و/یا Parsivar (برای پردازش متن فارسی)
- (اختیاری) Google Colab

---

## 📥 نصب و اجرا
1. مخزن را کلون کنید:

```bash
git clone https://github.com/evi-data-vision/Persian-News-Classification.git
cd Persian-News-Classification
pip install -r requirements.txt
```

---
