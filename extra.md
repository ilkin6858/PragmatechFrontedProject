##movzular JAVASCRIPT 1.Translator ve assembler nədir? Compiler və interpreter ilə aralarındakı fərqlər nələrdir? -Interpreter,compiler, assembler, translater; bunlarin isi bizim kompda yazdiqimiz ifadeleri tercume eliyib, masin diline cevirmekdir. -Assembler, dusuk seviyyeli proqramlasdirma dilidir, yeni insan diline yaxin olmayan dildir.Her hansi bir proqram dili insan diline ne qeder cox yaxin olarsa, yuksek seviyyeli dil kimi qebul edilir.Insan diline uzaq olan dil asaqi seviyyeli dil hesab olunur.

-Translator; -Proqram dilini kompiterin basa dusduyu masin diline cevirmek ucun translatordon(tercumeci) ve compilyatorden(tertibatci) istifade olunur. -Her bir proqramlasdirma dilinin ozunun transloru ve kompilyatoru olur. -Proqramlasdir dili ile hazir proqram deyil, ancaq algoritma benzer metin yaradilir. Bunuda masinin basa dusduyu dile cevirmek ucun kompiterde translator ve kompilyatorlar olur

-Compiler ve interpreter arasindaki ferqler; interpreter; her bir ifadeni sira ile tekbe-tek tercume edir menbe kodunu tehlil etmek ucun daha az vaxt aparirlar icra muddeti compilere nisbeten daha yavasdir yaddasi semerelidir,cunki her bir ara obyekt kodu yaranmir JS, python,php,ryby kimi diller interpreterden istifade edirler. error olan setire qeder oz isini icare edir

-compiler; -evvelce isini qarantiyaya alir,butun programi oxuyur eyer hardasa error olmasa, dahasonra ise onu butovlukde masin
koduna cevirir -tertib eden(compiler) menbe kodunu tehlil etmek ucun daha cox vaxt aparir,Amma icra muddeti interpretere(tercumeci)
nisbeten daha suretlidir. -Elave elaqe teleb eden araliq obyekt kodu yaradir, buna gorede daha cox yaddas teleb olunur -Java,C++ dilleri compilerden istifade edir

2.Rəqəm və ədədlərin maşın dilinə tərcümə olunma prosesini bilirik. Bəs hərflər və simvollar necə tərcümə olunur?

-herfler ve simvollari masin diline cevirmek ucun UNICODE deyilen bir sistem var.Hemin sistemde butun herflerin ve simvollarin reqem ile qarsiliqi var.meselen a herfinin reqem ile qarsiliqi 97-dir.Sonra ise 97 reqemini ceviririk binary codeye(masin diline)

3.Günümüzdə istifadə olunan Js,PHP,Python və C# dillərində ortaq istifadə olunan data növləri hansılardır və qısaca izahatlarını yazın. -ortaq data tipləri: string:metin tipli melumatlari ekrana eks edir. number; integer-tam edelerden ibaretdir. boolean; İki dəyərdən hər hansı biri: doğru və ya yalan doğru və yalan.true or false.

4.Type Conversion ya da Type Casting nədir? Hansı hallarda ehtiyac duyulur -- bir melumat novunu basqa melumaat novune cevirir.Meselen reqem olan 5-i, yazi olan 5-e tercume elemis oluruk.

5.Operator precedence nədir və əhəmiyyətini izah edin -operatorlarin ir birinden ustun olub olmadiqini yoxlayir 6.Automatic Type Conversion ve Type Conversion Methodlar arasındakı fərqləri izah edin. 7.Implicit ve Explicit type conversiton nədir? -Metod yazmadan cevirme isine baxir.yeni biz metod yazmadan avtomatik olaraq ozu cevirir –buna impilicit typeconversation deyilir. -Explicit type conversitionda ise, biz ozumuz metod yazaraq ceviririk.