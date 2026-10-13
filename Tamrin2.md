تمرین 2 :

معماری یک خطی :
mkdir -p projects/assets/css projects/assets/pages projects/assets/py

ازمایشگاه پیوندها :
echo "Hello" > info.txt
ln info.txt h_info.txt
ln -s info.txt s_info.txt
rm info.txt
cat h_info.txt -> Hello
cat s_info.txt -> cat: s_info.txt: No such file or directory

با حذف فایل اصلی هاردلینک همچنان قابل استفاده است
اما سافت‌ لینک شکسته می‌شود، چون مقصد آن دیگر وجود ندارد.

جستجو در كتابخانه :

    man rm
    /force -> -f , --force
    touch test.txt
    rm -f test.txt

سوئیچ -f یا --force برای حذف اجباری فایل‌ها بدون درخواست تأیید استفاده می‌شود همچنین اگر فایل وجود نداشته باشد خطای مربوط به نبودن فایل نمایش داده نمی‌شود.
