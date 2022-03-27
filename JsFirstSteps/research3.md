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




