1 - Javascript kodları necə formada yazıla bilər?
   --javascript kodlari  2 formada yazıla bilər: inline və externel: ilk olaraq HTML daxilində  <body></body> təqinin daxilində ən sonda və ən yuxarda <head></head> təqində yaza  bilərik burada <script></script> təqi ilə yazılır.Çalışmaq lazımdırki  js kodlarını ən sonda yazaq, kodlarin yoxunma sirasi yuxaridan asaqi olduqu üçün.

   --external ise ayrica olaraq app,js adinda fayl yaradiriq ve brauzerde islemi ucun html ile  <script src="app.js"></script> seklinde qosa bilerik.External ile yaradilan fayli head ve ya body daxilinde caqira bilerik.hec bir ferqi yoxdu.

2 - Javascript kodlarının script tagları daxilində yazmaqla ayrı fayl formatında yazıb import etmek arasında nə fərq var?

    -- html daxilinde script ile yazilan js kodlari  ve html uzunun teqleri yazildiqin ucun bir muddentden sonra kodlarin sayi artdiqi ucun qarisiqliq yarada biler meselen: sonradan 300-400 kodun icerisinde her hansisa kodu deyisdirmek isdesek kodu axdarib tapmaqa vaxt cox gedecek ve kodun oxumasinin suretini zeiflede biler.


 3 - Madem mənim brauzerimdə V8-Engine yüklüdür niyə html kodu daxilində yazılan javascript kodları işləmir?

    --script yazmasaq  html o kodları js kpdu kimi tanımır 
       brauzerler HTML olmadan islemir.Yeni brauzere melumat gondermek ucun HTML-den istifade olunur.
      v8-Engine olmadan js brauzerde islemir, 


 4 - ";" hansı hallarda istifadə edilir?

     -- "" bu isare string tipli melumatlardan istifaa etmek ucun bize komey edir.
        ; vergul ise her hansi kodun bitmeyini bildirir.Meselen bir setirde  console.log("hello");  alert("name")    bu sekilde yazan zaman ; bize lazim olur.


5 -  Javascript-də comment yazmaq üçün neçə üsul var.

    -- jsde yorum yazmaq ucun 2 cure yol var.
    // tekce hemin setirde bize yorum yazir.
   /*   */ isdediyimiz qeder kodu yoruma ala bilerik.


 6 -  let,var,const ifadələri arasında fərqlər nədir?
       let ve const ECMAScript 6 ile gelen yeni deyisen elan etme usullaridir.Bundan var ile deyisen elan olunur.

       -- var ile deyiseni yeniden elan ede bilirik ve melumati yenileyede bilirik.

       -- let de deyisen yeniden elana bilmez amma daxildeki melumat yenilene biler.

       -- const ise sabit deyiskendir,icerisindeki melumati yenileye bilmerik eyer const ile deyisen elan olunubsa vacibdirki deyisenin         icerisine melumat qoyaq eks halda undefined deyil, error qaytaracaq.

       -- gelek esas ferqlerine: var global ve functional scopedir, yeni funksiya daxilinde var ile deyisen elan olunanda,funksiya xaricinde    caqirilila bilmez .

       -- Amma if,switch ve for while dongulerinde elan olunan var deyiseni global scopedir, 

       -- varin diger esas ferqi oz scopunda yuxari qalxma xususiyyetidir (variable hoisting).  Meselen console.log(ad); var ad="ilkin"; netice undefined olacaq, cunki ad deyisenin deyeri deyesenle birlikde yuxari qalxmir yalniz elan olunan deyisen yuxari qalxir. amma let ise error verecek

       -- let ve const ise block scopedir.



      


 7 -  dəyişən təyin edərkən adlandırma qaydaları nələrdir?
   
      -- deyisen teyin javascripitn acar sozlerinden istifade elemek qadaqandir.
      -- deyisen reqemle baslaya bilmez,
      -- deyisen - ile baslaya bilez.amma sonda veya ortada yazila biler.
      -- $ _ teyin elemek olar.


       



 8 -  let x=5;x=7 yazıldığı zaman nəticə 7 olur.Belə olan halda 5 dəyərinin aqibəti nə olur? Yaddaşda yer tutur mu 5 dəyəri yoxsa başqa proses mi gedir?.
     -- let x=5 yazan stackda yer tutur amma x=daxiline yeniden deyer qoyduqda biz onun evvelki deyeri yaddasdan silinir ve yeni deyer yaddasa qeyd olunur.



 9 -  5 dəyəri yaddasa yazılarkən 2-li say sisteminə çevrilir və ona görə yaddaşda tutduğu yer hesablanır.Bəs 5.34 dəyərinin yaddaşda tutduğu yeri necə hesablamaq olar?




 10 - undefined, NaN və null dəyərlərinin yaddaşda nə qədər yer tutduğunu araşdırın


 11 -  let a; bu formada dəyişən təyin etmişəm.
           Bu dəyişən yaddaşda stack-da mı yoxsa heap-də mi yerləşir
              Bu dəyişən yaddaşda yer tuturmu? Tutursa nə qədər yer tutur?
                 
                 --let a stack yaddasinda yerlesecek.


                 



12 -  Ümumiyyətlə sizə görə bir məlumat növünü başqa məlumat növünə çevirmək nəyə lazımdır?

    -- meselen "5" + 10  emeliyyatinin neticesi 510 olacaq , amma bize lazimdirki bunlari toplasin bu zaman biz number mestodunndan istifade edirik.



13 -  Type Conversion necə formada həyata keçirilir?



14 -  Type Conversion metodlarının siyahısını çıxarın
     -- Tostring, ToNumber, ToBoolean;