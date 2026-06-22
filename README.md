# stock-market-analysis
Analysis of S&amp;P 500 stock prices and trends using Python and Pandas
# 📈 Stock Market Analysis (S&P 500)

تحلیل روند قیمت سهام شرکت‌های بزرگ بورس آمریکا طی ۵ سال با Python و Pandas

## 📌 درباره پروژه
این پروژه روند قیمت سهام چند شرکت بزرگ (اپل، گوگل، آمازون، مایکروسافت) را در بازه ۲۰۱۳ تا ۲۰۱۸ تحلیل می‌کند و رشد آن‌ها را با تکنیک نرمال‌سازی مقایسه می‌کند.

## 📊 دیتاست
- منبع: [Kaggle - S&P 500 Stock Data](https://www.kaggle.com/datasets/camnugent/sandp500)
- تعداد رکورد: ۶۱۹,۰۴۰
- تعداد شرکت: ۵۰۵
- بازه زمانی: ۲۰۱۳ تا ۲۰۱۸

## 🛠 ابزارها
Python | Pandas | NumPy | Matplotlib

## 🔎 یافته‌های کلیدی
- سهام اپل (AAPL) در این بازه ۱۳۵٪ رشد داشته است
- بالاترین قیمت اپل ۱۷۹.۲۶ دلار در تاریخ ۱۸ ژانویه ۲۰۱۸ ثبت شده است
- مقایسه مستقیم قیمت‌های خام بین شرکت‌ها گمراه‌کننده است؛ نرمال‌سازی برای مقایسه رشد واقعی ضروری است
- آمازون و گوگل بالاترین قیمت مطلق را داشتند اما الگوی رشد مشابهی با سایر سهام نشان دادند

## 📈 نمودارها
- `aapl_price_trend.png` — روند قیمت اپل
- `stock_comparison.png` — مقایسه چند شرکت

## 🚀 اجرا
```bash
pip install pandas numpy matplotlib
jupyter notebook stock_analysis.ipynb
```
**نکته:** فایل داده باید از [Kaggle](https://www.kaggle.com/datasets/camnugent/sandp500) دانلود و در پوشه پروژه قرار گیرد.

## 🔭 مراحل بعدی
- پیش‌بینی قیمت آینده با مدل‌های رگرسیون
- محاسبه میانگین متحرک (Moving Average) و نوسان‌پذیری
- ساخت یک سیگنال معاملاتی ساده

## 👩‍💻 توسعه‌دهنده
Hannaneh Sepehri — MSc AI Student
