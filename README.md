﻿#(For PayU Turkey)
------

#CMS Opencart için Modüldür (Ortak Ödeme Modülüdür)
======

(1.5.х Versiyonları için test edilmiştir )

IPN : http://{domainadınız}/index.php?route=payment/payu/callback

#Kurulumu
------------
1. Klasörün içinde ki 'admin' ve 'catalog' dosyalarını hostunuza yollayın.Dosyalarınız hiç bir değişiklik yapmayacaktır.
2. Admin paneline girin
- Eklentilerden -> ödeme yöntemlerini seçin
3. PayU Methodunu bulun
- Kur butonuna basın
- Düzenle butonuna basın 
- İceriği doldurun.Yardım almak için screen shotu kullanabilirsiniz.

Mağazanızın döviz birimini doğru ayarladığınızdan emin olun zira eğer USD yada EUR olarak kullanıyorsanız PayU ödemeyi TRY (TL) sına çevirerek alacaktır.Arada döviz kurundan kaynaklı zarara uğrayabilirsiniz.

![Screenshot][1]

========================
# English manual 
---------

Module for CMS Opencart ( Live update version )

( Checked on version 1.5.х )

IPN : http://{domain of site }/index.php?route=payment/payu/callback

Installation

1. Copy folders 'admin' and 'catalog' to main folder of your site
2. Enter to admin panel
- Choose  "Extentions" -> "Payment"
3. Find a method "PayU" 
- Push the button  "Install" 
- Push the button "Change"
- Enter your personal settings
Exemple of settings you can watching on screenshot


[1]: https://raw.github.com/PayUDevCenter/Opencart-1.5-for-Turkey/master/screenshot.png

