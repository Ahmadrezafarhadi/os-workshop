# تمرین کارگاه سیستم عامل

## چالش اول

ساخت پوشه test:

mkdir test

ساخت فایل test.txt:

touch test.txt

نوشتن متن داخل فایل:

echo -e "hello world" > test.txt

باز کردن راهنمای grep:

man grep

جستجوی گزینه count در راهنما:

text
/count

شمارش خط‌هایی که کلمه hello دارند:

grep -c "hello" test.txt

## چالش دوم

پیدا کردن فایل‌های conf در پوشه etc:

find /etc -type f -name "\*.conf"

## چالش سوم

ساخت فایل data.csv با ۲۰۰۰ خط عددی:

seq 1 2000 > data.csv

نمایش خطوط ۱۵۱۵ تا ۱۵۵۵:

head -n 1555 data.csv | tail -n 41

ابتدا ۱۵۵۵ خط اول خوانده می‌شود و بعد ۴۱ خط آخر نمایش داده می‌شود.
