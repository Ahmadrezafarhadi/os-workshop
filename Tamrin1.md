تمرین 1 :
جستجوی پیشرفته:

    mkdir practice
    cd practice

    man ls
    /-S
    ls -S

    mv small.txt
    mv medium.txt

    ls -LS

خروجی : نمایش فایل های ساخته شده در فولدر ساخته شده

تحقیق معماری :

/bin :
محل دستورهای عمومی سیستم
/sbin :
محل دستور های ابزار های مدیریتی

ترسیم نقشه :

sudo apt install tree

tree -d -L 1 / | grep -E 'bin|sbin|etc|home|var'

خروجی :

├── bin -> usr/bin
├── etc
├── home
├── sbin -> usr/sbin
└── var
