Arasdirma movzular:

Sual01: Javascript proqramlaşdırma dili hansı sahələrdə istifadə olunur?

     --Hazırda javascript bir çox sahələrdə istifadə olunur.Veb,oyun,mobil,dekstop, server.


Sual02: Aşağıdakı proqramlaşdırma terminlərinin qısa acıqlamasını yazın
    compilers-- yazilan kodlari komputerin basa dusulmesi ucun  tercume edib masin diline cevirir.Kodlari butov bir sekilde oxuyur ve kodda bir error olarsa ve hemin 1 errora gore butun  kodlar icra olunmayacaq


    interpreters--yazilan kodlari yuxaridan asaqi setir be setir oxuyub tercume edir.Eyer hansisa setirde error varsa hemin setire kimi kodlari icra edecek ondan yazilan kodlari icra etmeyecek.


    translators--Yazilan kodlari komputerin anladiqi kodlara cevirmek ucun bize tercumeci lazimdir.Buna Translator deyilir ve bunun 3 novu vardir.Compiler,Interpreter ve Assembler.

    assemblers--asaqi seviyyleri proagramlasdirma dilidir,yeniki insan diline yaxin olmayan ancaq masin diline yaxin olan dildir.Her hansi bir programlasdirma dili insan diline ne qeder cox yaxin olarsa, o qeder yuksek seviyyleri dil kimi qebul olunur

programming paradigms--paradigmalar 2 qurupa bolunur.Dekarativlilik ve imperativlilik.
imperativlilik programlasdirma, adeten emirli program deyirler,burda emirler setir be setir verilir.
Dekarativlilik ise 


debugging--yazilan koddu tek-tek yoxlayaraq deqiqliyine emin olmaqdir,ve ya yazilan kodda sehv varsa deyisiklik etmekdir.


boolean--mentiqi operatorlarda istifade olunan sozlerdir (AND, OR, NOT or AND NOT).


char--yalniz bir simvol yadda saxlamaqa icaze verir


null--menasi teyin olunmayan demekdir, var=null


command-line interface--komputere melumat oturmek ve ondan meluamat goturmek ucun interfysde emirlerden istifade olunur.Meselen terminal


low-level language--Asaqi seviyyleri diller,insan diline uzaq, masin diline yaxin olan dillerdir.Meselen assembler.Asaqi seviyyeli diller masin diline yaxin olduqu ucun onlari basa dusmek ve onlarda kod yazmaq daha cetindir.


high-level language--Sintaktisi ve strukturuna  gore insan diline yaxin olan ancaq masin diline uzaq olan diller hesab olunur.Meselen Java,Python,javascript ves.Bu Dillerde proqram yazmaq ve oyrenmek daha asandir



markup language--İsareleme dili adlanir.Seyfenin icindeki melumatlari formalasdirmaqa ve asandlasdirmaqa komek eden,sade sozlerden ve teqlerden ibaret olan komputer dilidir.Bu programlasdirma dili deyil,meselen HTML.


Sual03: Veb səhifəsinin işləmə prinsipini anlayabilmək üçün aşağıdakı mövhumları araşdıraraq yazın

İnternet ve intranet arasındakı fərqlər nədir?  --internet her kes ucun el catandir ve her kes qosula biler,melumat paylasa biler,limitsiz istifade oluna bilir.Tehlukesiz deyil,

intranet--her kes ucun el catan deyil,istifadeci mehdudiyyeti var,her hansi bir sirkete aid ola biler,internet ile muqayisede daha tehlukesizdir.Yalniz icaze verilen sexsler istifade ede biler.

Server-side və client-side ifadələrinin mənası nədir?--    client-side:Client resurslardan istifade eden terefdir. Vebsaytın HTML, CSS, JavaScript kodları oxunduqdan sonra, istifadəçi səhifəni görə bilir. Bu da o deməkdir ki, kodların çox olduğu təqdirdə istifadəçi uzun müddət səhifəni görmək üçün gözləməlidir.

Server-side--İstifadəçi vebsayta daxil olarkən JavaScript kodları oxunmasa belə, səhifənin vizual tərəfini görə bilir. CSR`dən fərqli olaraq, istifadəçi saytı görmək üçün uzun müddət gözləmir, saytın bütün funksionallıqlarından istifadə etmək üçün gözləyir, lakin vizual olaraq gördüyü üçün bunu hiss etmir.


Server nədir və necə işləyir?--Server ozunde coxlu melumat saxliyan ve coxlu adrese melumat gonderen ana platofrmadir.Internetde gorduyumuz her bir melumat hansisa server uzeroinden bize oturulur.
Client Serverden ozune lazim olan melumatlari tapilib ozune gonderilmesini teleb edir.Yeniki Servere sorqu gonnderir mene hansisa fayil,sekil ve ya melumat lazimdi.Onu tap ve mene gonder.Bu proses request prosesi adlanir.Server ise ondan teleb olunan melumati cliente catdirir.Bu ise response adlanir.Yeni cliente resurslarla temin eden terefdir.Server Sebekede bas veren emal prosesini heyata keciren esas sistemdir(Esas komputer).Daha yuksek xususiyyetlere malik olan,xususi qurqularla techiz olunan komputerdir.Clientler ise adi bizim bildiyimiz komputerlerdir.

Domain nədir və necə işləyir?--Domain saytin esas olan ad hissesidir.Meselen facebook.com. Azercell.az.Her bir olkenin ozune mexsus domaini olur.180 domain adi var.Her bir domainin ozune mexsus menasi var.Domainin islemesi ucun mutleq sekil hostinge ehtiyyaci var,hosting olmasa hec bir sekilde sayt olmayacaq.Yalniz mail kimi istifade elemek olar.


HTTP nədir və nəyə lazımdır:Serverler ve istifadeciler arasinda melumat axinin nece bir sekilde olacaqini deskil eden protollardan birisidir.Internet saytlarini bir axdaris ile aninda qarsimiza cixardan sebeblerden biride bu protokol sayesindedir.Her hansi bir internet saytina girmek ucun,saytin adresini yazdiqimizda HTTP ile servere bir istek gonderilir ve server bu isteye cavab verende internet saytina girmis oluruq.


URL və URI ifadələri arasındakı fərqləri izah edin.

URL--Internetdeki menbeleri tapmaq ucun genis sekilde istifade olunur. Şəbəkə yerini və ya əsas giriş mexanizmini təsvir edərək fiziki yerin təqdimatını almaq üçün bir metod teqdim edir.

URI-- Resursların vahid identifikasiyasına imkan verir. Bir URI əlavə olaraq bir axtarış yeri, bir ad və ya hər ikisi olaraq qruplaşdırılır, yəni bir URL, URN və ya hər ikisini təsvir edə bilər. URI-də termin identifikatoru, əməliyyatı yerinə yetirmək üçün istifadə edilən texnikaya, yerləşmə, ad və ya kontekstə baxmayaraq, mənbələrin fərqinə işarə edir. 


