چالش اول :
mkdir test
ساخت فولدر تست
mkdir test.txt
ساخت فایل تست
echo -e "hello wolrd" > test.txt
داخل فایل تست یک خط متن وارد کردیم
man grep
راهنمای گرپ را باز کردیم
/count
grep -c "hello" test.txt
کلمه سلام رو از فایل تست پیدا میکنه

چالش دوم :
find /etc -type f -name "\*.conf"
پیدا کردن فایل CONF با جزئیات و مشخصات

چالش سوم :
seq 1 2000 > data.csv
داخل فایل DATA.CSV 2000 خط عدد 1 ریخیتیم
head -n 1555 data.csv | tail -n 50
از بالا تا پایین 50 تا خط بیا پایین
