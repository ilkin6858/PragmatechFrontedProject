Sual1: Dəyişən təyin edərkən ya da dəyər mənimsədərkən boşluqlardan istifadə etsək bu mənə error olaraq qayıdar mı? let a=5; let a= 5; bu iki formada yazılışlardan hansısa error verəcək mi?
    --xeyir error vermiyecek ammaki usdunluk olaraq bosluqdan istifade edilmekdedir.



Sual2:  Bütün proqramlaşdırma dillərində olduğu kimi Js-də xüsusi simvollardan istifadə edir. () və {} mötərizələri V8Engine tərəfindən necə analiz olunur? Bu mötərizələr tərcümə prosesində necə başa düşülür?

     --() bu moterize if for looplarda ve funksiyalar istifade edilir. if ve forda () moterizede serti yzmaq ucun istifade olunur.Funksiyalarda ise daxiline parametir ve arguman gondermek ucun ve en esasida funksiyani isletmek ucun lazim olur.



Sual3: let StudentName; let studentName; let studentname yazılışları arasında Javascript üçün hər hansı fərq varmı? Qısacası Javascript Case Sensitive dildir?

    ----- beli javascript Case Sensitive dildir.yeni boyuk kicik herfe hessasdir.yuxarida yazdiqiniz deyisen adlarinin her biri ferqli deyisendir.V8Engine terefinden ferqli sekilde tercume olunur ve yaddasda ferqli yerlerde yerlesir.
    Javascripde  camalCase adlandirma usulu daha cox populiyardir.Mende camalCase istifade edirem.



Sual4:  Javascriptdə kod yazarkən indentation hansı hallarda istifadə olunur və mən kod yazarkən indentation istifadə etməyə məcburammı?

  -- identation istifade elemek mecburi deyil ammaki bizim bir coxlu sayda kod yazmaqimiz gelecekde yazdiqimiz kodlar artan qarisiqliqa yol acacaq. ve seyfeni yuklenmesi suretlenmis olacaq.


Sual5: let x=5; kodlarının v8engine tərəfindən tərcümə edilərək maşın dilinə çevrilmə prosesini necə təsəvüür edirsiniz?

    --V8Engine kodu tercume edir ve stackda x adinda bir yer teyin olunur ve hemin yerin daxilne 5 number tipi yerlesdirilir.




Sual6:   primitive və reference data tipləri deyə iki kategoriyaya ayrılma səbəbi nə ola bilər?

      --cunki her ikisinin v8Engine terefinden tercume olunma ve yaddasda saxlanilma prosesi ferqlidir




Sual7:  bu iki tip arasında fərqli xüsusiyyətlər nədir?

        -- primitiv data tipleri deyerlerine gore muqayise oluna biler.amma referasn tiplerde bu olmur,
        -- primitiv data tiplerinin icerisini deyisdire bilmirik,amma referansda bunlar mumkundur.
        --primitib tipler stackda yerlesir, referanslarda gostericisi stackda, melumatin  ise heapda yerlesir.
        --primitiv data tiplerini  deyisdirmek olmur,meselen let word="javascript"  deyisenin icerisindeki j herfini deyisdire bilmirk
        --primitiv data tipleri deyerlerine gore muqayise olunur, referans tipler ise deyerlerine  mmuqayise oluna bilmir,yalniz referanslarina gore muqayise olunur.
        --primitiv dapa tipkerinnin daxilinde 1 deyer tuta bilirik, refereranslarda  moterezelerin icinde 1 den cox deyer tuta bilirik.
        --primitiv data tiplerinde yalniz 1 nov melumat ola biler, referanslarda ferqli melumat novlerini saxlamaq mumkundu ise string, number, undefined ves ola bilir,



Sual8:   bu data tiplərin yaddaşdakı yeri ilə əlaqədar senarilərinizi yazın. Yəni kod v8 enginə-nə ötürüldüyü zaman o kodun başına nə iş gəlir?

      -- primitib tipde yazilan kod meselen let name="ilkin" kodunu v8Engine yaddasda ona yeni stackda name adinda yer bron edir ve onun daxiline "ilkin" melumatini yerlesdirir.


Sual9:  data tiplərin bu formada iki kategoriyaya ayrılması sadəcə javascript dilinə xas xüsusiyyətdir yoxsa digər dillərdə də eyni yanaşma mövcuddur mu?

     --her bir pragramlasdirma dilinin ozune mexsus data tipleri var



Sual10:  Bu mövzunu öyrənmək proqramçı olaraq sizə nə qata bilər? Yəni bu mövzunu qavramağınız sizə nə fayda verəcək?




NaN, null, undefined in Javascript.

    

Sual11: Bu tiplər başqa hansı dillərdə mövcuddur?
 
    ----- bu tipler yalniz javascriptde mexsus olan tipdi.




Sual12: NaN null və undefined bunlardan hansı data tipdir və növləri nədir? Primitive yoxsa reference tip olub olmadığı haqqında nə deyə bilərsiz?

     ---null ve undefined data tipdir, NaN Number data tipinin novudur.Bunlar primitive data tiplerdir.


Sual13: expression deyiləndə nə başa düşməyim lazımdır?

        --javascript expression ifadeler anlamina gelir.

Sual14: operator və expression arasında fərqlər nələrdir?

        --operator emeliyyatlari yerine yetirmek ucun istifade olunur.



Sual15: function ümumiyyətlə nə üçün istifadə edilir?
 
    --funksiyalar mueyyen bir isi yerine yetirmek ucun bir kod blokudu.
    --tekrarlanmanin qarsini ala bilmek ucun istifade olunur ve cetin olan bir isi parcalara ayririb gormek ucun.



Sual15:  function istifadə etmənin kod yazarkən gətirdiyi faydalar?

      --Funksiya kodu təkrar istifadə edilə bilən edir. biz onu bir dəfə bəyan edib, dəfələrlə istifadə edə bilərik.
      --Funksiya proqramı asanlaşdırır, çünki hər bir kiçik tapşırıq bir funksiyaya bölünür.
      --Function increases readability.



Sual16:  necə formada function təyin etmək olar?

        --- funksiyani oz adi ile teyin elemek olur.
        --- funksiyani deyisenin icerisine yerlesdirib teyin elemek olur.



Sual17:scope anlayışı nədir? 

 --deyisenlere muraciet etmek ucun mueyyenlesdirilmis bir qayada-qanundur


Sual18:void və return function nədir? Hansı hallarda istifadə olunur?

  --void funksiyalara neticesi olmayan funksiyalarda demek olar,yeni hec bir deyer qaytarmir ekranda gosderirmir,
  --return funksiyalarda ise ekrana netice qaytaran funskiyalardir


Sual19:function icra olunduğu zaman yaddaşda necə yer tutur?

   -- funksiyalar referenas tipler olduqu ucun, onlarin daxilindeki melumatlar heapda yerlesir,funskiyalarin adi stackda yerlesir, 




   Day19 [ 19 March 2022]  Mövzular və Araşdırma

Sual20: Proqramlaşdırma dillərinin dizayn olunması deyiləndə ağlınıza nə gəlir? Yəni bir proqramlaşdırma dili necə dizayn edilə bilər?

    --proqramlasdirma dilinin dizayn olunmasi onun developerler terefinden nece dizayn olunmasina baqldir,
    her programladirma dilinin dizayn olunmasi ferqlidir,Meselen javascriptde funskiyanin yazilmasi ile her hansisa bir compiler c# olan dilde funksiya yazilmasi ferqlidir.



Sual20:Öz həyatınızda imperativ və deklarativ yanaşmaya aid nümunələr tapın?

       -- dekarativ yanasmada esas olan son neticedir,meselen restaranda yemey sifarisi vermek dekarativdir,
       --imperativlikde ise gorulecek is onemlidir, her isi ozumuz gormelik oluruq,meselen c pragramlasdirma dilinde gorulen her is imperativdir



Sual21:Deklarativ yanaşma və funksiyalar arasında əlaqəni necə qura bilərsiniz?

    -- dekarativ yanasmada gorulen isin neticesi maraqladir, funksiyada toplama emeliyyatinin yerine yetirilmesi imperativ, funksiyanin caqirilmasi ve toplamaninmyerine yetirilmesi ise dekarativdir,



Sual22:imperative və deklarative yanaşmaya aid kod nümunələri yazın özünüz üçün .Düzgün olub olmadığını yoldaşlarınızla analiz edin.



Sual23:Function necə formada təyin olunur?
   
     --funksiyanin teyin edilmesi function acar sozu ve yaninda gorulecek isin adi (){};



Sual24:Fərqli formada function təyin etmə sizcə hansı hallarda lazım ola bilər?

    


Sual25:function scope və global scope arasında fərqlər nədir?   

     --function scole elan olunan deyisenler yalniz hemin funksiya daxilinde kecirlidir, globalda caqirila bilmez.
     --Global scopda elan olunan deyisen ise function scopeda caqirila biler, hetda icerisinde deyise bilerik.


Sual26:function ramdə necə yer tutur?

  --function referanslar olduqu ucun function icra olunan zaman heapda yerlesir, amma funksiyanin adi stackda gosderilir.


 Sual27:Javascript kodlarının arxa planda işləmə prinsipi necədir?

  --kod yazdiqimiz zaman v8Enginee yazdiqimiz kodlari tercume edir masin diline yaddasda yerlesdirir.
  yaddasda yerlesme sekiledeki primitiv tipler stackda yerlesdirilir, referans tipler ise heapda yerlesdirilir.


 Sual28:Allocate memory-use memory- release memory ifadələri nə deməkdir?
     
     --yaddas 3 hisseden ibaretdir.1-cisi Allocate memory menasi yaddasda yer ayirmaq demekdir.yeni biz deyerleri elan eden zaman onlar ucun yaddasda yer ayrilir,bu proses Allocate memory adlanir.

     --use memory:yaddasda evvelceden Allocate olunmus melumatin interpret terefinden oxunmasi ve terdcume olunma prosesidir ve hemin melumatlardan istifade olunma prosesi

     --release memory:artiq melumatlara ehdiyyacimiz olmuyanda,yaddasdan melumatlar atilir,bu proses garbage collection adlanir.
    


Sual29:Static allocation vs dynamic allocation?

   --Static allocation-primitiv melumatlarin stcakda yerlesdirirlmesi prosesi adlanir,bura reqemler,stringler  aiddir.ve obyekleri ve funskiyali adlari yerlesdirilir.

   --dynamic allocation- heapda saxlanilan referans tipleridir,bura obyektler,funksiyalar ves 

Sual30:garbage collection nədir?

     --javascript high level dil olduqu ucun yaddasin temizlenmesini ozu avtomatik olaraq heyata kecirilir,
     jvascript melumatlari istifade eledikden sonra lazim olmayan melumatlari zibil qutusuna bosaldir.bu proses garbage collection adlanir.

Sual41:hoisting nədir?

     --funksiyanin icrasindan evvel ekrana cap olunmasi, deyisenin ise console.log edib daha sonra  elan olunmasidir,evvel , bu kodda bezen errorlara getirib cixardir.istifade edilmesi meslehet gorulmur

Sual42:scope və hoisting ifadələri arasında fərq nədir?

    --scopeler gorulen isler hemin scope daxilinde ve globalda  olur,hoistingde ise oz scopelerinden yuxaride icra olunur.






    
Day20-21 [ 26-27 March 2022]


Sual43:void və return function nədir?

    --



Sual44:return keyword-unun var olma məqsədi nədir?

    --


Sual45:block scope vs function scope vs global scope fərqlər nədir?

  --



 Sual46:function literal nədir?

   --index->value vs key->value fərqləri nədir


Sual47:
while loop?
for loop?
for in loop?s
    

    

    








