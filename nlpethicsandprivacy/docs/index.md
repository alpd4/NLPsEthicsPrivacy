# DOĞAL DİL İŞLEME UYGULAMALARINDA VERİ GİZLİLİĞİ VE KARŞILAŞILAN ETİK SORUNLAR
  
## ETİK VE VERİ GİZLİLİĞİ

Etik, yaşamda gerçekleştirilen eylemlerin doğru ve yanlış olmalarının incelenmesidir. Etik, pratik bir disiplindir. Temel amacı kişinin nasıl yaşaması gerektiğini ve yaşamını sürdürürken hangi eylemleri yapması gerektiğini belirlemektir[1].

Veri gizliliği, bir gerçek kişiye ait özel ve kişisel bilgilerin başkalarıyla ne zaman, nasıl ve ne ölçüde paylaşılacağı konularının düzenlenmesidir. Başta kişisel veriler olmak üzere hassas ve gizli verilerin de uygun şekilde işlenmesiyle ilgili bir veri koruma alanıdır[3].

Doğal Dil İşleme(kısacas NLP) uygulamalarında kullanılmak üzere toplanan verilerin kapsamı ve büyüklüğü sebebiyle, toplumda, etik ve gizlilik endişeleri görülebilir. Özellikle kişisel ve hassas nitelikli bilgilerin işlendiği durumlarda bu sorunlar daha belirgin hale gelir. Doğal Dil İşleme uygulamalarının sorumlu kullanımı bir gerekliliktir. NLP uygulamalarının, sürdürülebilir, veri gizliliği ve etik problemleri gözetiyor olması gerekmektedir.


## NLP UYGULAMALARINDA ETİK VE VERİ GİZLİLİĞİ PROBLEMLERİ 

Bu başlık altında NLP uygulamalarında karşılaşılan etik ve veri gizliliği problemleri incelenecek, çözüm yolları sunulacaktır.

### NLP Uygulamalarında Önyargı ve Eşitlik

Doğal Dil İşleme uygulamalarında ön yargı, bir NLP modelinin belirli bir grup veriyi o verilere has özelliklerine göre diğer verilerden ayrı konumlandırma veya onlara karşı ayrımcılık yapma eğilimini ifade eder. Ön yargı, NLP uygulamalarında, veri toplama, veri ön işleme ve model yapısının oluşturulması aşamalarında gelişebilir. Modelin her bir veri grubuna ayrım yapmaksızın eşit ve adil davranması gerekmektedir[2].

Bu grupların insan ve insan verilerinden oluştuğu durumlarda, toplumun belirli kesimlerine gösterilecek ayrımcılık sosyal açıdan bir felaketle sonuçlanabilmektedir. Bir NLP modelinin toplumun belirli bir kesmi hakkındaki mevcut ön yargıları ve varsayımları sürdürmemesi beklenir. NLP uygulamaları, cinsiyet, etnik köken gibi özellikleri gözetmeksizin tüm bireylere eşit davranmalıdır. Eşitlik problemi, modelin toplumdaki hassas kitleler üzerinde test edilmesi ve elde edilen çıktıların analiz edilmesi ile tespit edilebilir. Bu sayede potansiyel ön yargıların ve eşitsizliklerin belirlenmesi, belirlenen problemler için önlem alınması ve düzeltmelerin yapılması mümkün olur. 

NLP uygulamalarında modelin ön yargılı davranmasının esas sebeplerinden biri model oluşturmada kullanılan eğitim veri setindeki toplumsal ön yargıya sahip verilerdir. Eğitim veri setleri yaygın ve çeşitli bir popülasyona ait değil de toplumun sadece belirli bir kesmini kapsayacak biçimde oluşturulursa, model o kesmin dilini, kültürel yapısı öğreneceği için, bu durum, uygunsuz dil ve belirli gruplara karşı ayrımcılağa, dolayısıyla ön yargılı çıktılara ve eşitsizliğe sebebiyet verebilir. Benzer şekilde, veri ön işleme aşaması ve algoritma tasarımı süreçlerinde, modeli eğiten kişi ya da grubun belirli parametre ve belirli özellikleri tercih etmesi, istenmeyen ön yargılı çıktılara sebep verebilir. NLP modellerinin etik konularda ortaya koyduğu performansın düzenli olarak gözlenmesi bu açıdan kritik öneme sahiptir[4].

NLP'de eşitliği sürdürebilmenin yollarından biri de modellerin şeffaf, denetlenmesi kolay tasarlanması ve modelin karar verme sürecinin herkes için anlaşılabilir ve açık olmasının sağlanmasıdır. Bu sayede potansiyel ön yargılı çıktıların, izlediği yol kullanıcılar tarafından takip edilebilecektir. NLP'de eşitliğin sürdürülmesi, Doğal Dil İşleme uygulamalarına güven oluşturulmasına katkı sağlayacaktır. Teknolojinin gelişimi ve toplum tarafından destek görmesi için bu durum çok önemlidir.

NLP uygulamalarında karşılaşılabilecek bazı önyargı çeşitleri aşağıda listelenmiştir:

* Temsil Yanlılığı: Nüfusun bir bölümünün verilerde yoğun şekilde temsil edilmesi veya aşırı derecede görmezden gelinmesi durumunda ortaya çıkar.

* Tarihsel Önyargı: Toplumda tarihler boyunca yerleşmiş ve kalıplaşmış ön yargıların varlığı sebebiyle ortaya çıkar. Ayrımcı bir çıktı üretilmesine sebep olur.

* Öğrenme Önyargısı: Toplum içindeki az temsil edilen, dolayısıyla yetersiz veri elde edilen grupları etkiler.

* Değerlendirme Önyargısı: Sınırlı bir popülasyon üzerinde spesifik bir amaç için tasarlanan modellerin, tüm nüfusu temsil etmekte başarısız olduğu durumu ifade eder. 

* Toplama Önyargısı: Çeşitli kitlelere arasında ortak paylaşılan özelliklere odaklanıldığında, bu kitleler arasındaki farklılıkların dikkate alınmaması durumudur.

* Dağıtım Önyargısı: Veri hattının dışında meydana gelen bir önyargı türüdür. Amaçlanan sorun ile çözüme yaklaşım yöntemi arasında bir uyumsuzluk olduğunda gözlemlenir.


### NLP Uygulamalarında Sosyal Sorumluluk ve Sürdürülebilirlik

NLP uygulamalarının yaygınlaşan kullanımı, uygulamaların kanunlar ve toplum önünde hesap verebilir olması gerekliliğini ortaya çıkarmıştır[5].

NLP uygulamalarının küresel iklime etkisi, NLP modellerin eğitimi ve çalıştırılması için kullanılan ve giderek artan yüksek miktardaki enerji ve kaynaklar göz önüne alındığında göz ardı edilmemesi gereken bir konudur. Doğal Dil İşleme uygulamalarındaki gelişimin sağlanması ve kitlelerce destek görmesi için mevcut ve geliştirilecek uygulamaların sürdürülebilirliğinin sağlanması gerekmektedir.

NLP uygulamalarının topluma bir etkisi de yanlış bilginin yayılması tehlikesidir. Eğitim veri setlerinde kullanılan verilerdeki yanlış ve yanıltıcı veriler dolayısıyla NLP modelleri, toplum üzerinde kötü etkiler yaratabilecek yanlış çıktılar üretebilmektedir. Model geliştiricileri, bu yanlış ve yanıltıcı verileri tanımlanıp veri setinin filtrelenmesi sorumluluğunu üstlenmelidir.

NLP uygulamaları ve geliştiriciler, sürdürülebilirlik ve kanun ve toplum önünde hesap verilebilirlik sorumluluklarını yerine getirmediği takdirde toplumsal tepki görebilmekte ve kanunsal yaptırımlarla karşılaşabilmektedir.


### NLP Uygulamalarında Veri Gizliliği

Dünya genelinde düzenleyici kurumlar, nüfusun kişisel ve hassas verilerinin korunması ve işlenmesi eylemlerini çeşitli yönetmelik ve kanunlar ile düzenlemiştir[1]. Örneğin, Genel Veri Koruma Yönetmeliği(GDPR), Avrupa genelinde AB vatandaşlarının kişisel verilerini korumaya yönelik oluşturulmuş yönetmeliktir. Benzer şekilde Türkiye’de yürürlüğe konan Kişisel Verilerin Korunması Kanununun(KVKK) amacı kişisel verilerin işlenmesinde, kişilerin temel hak ve özgürlüklerini korumak; kişisel verileri işleyen gerçek ve tüzel kişilerin yükümlülükleri ile uyacakları usul ve esasları düzenlemek, kişilerin mahremiyetini korumak ve kişisel veri güvenliğini sağlamak olarak belirtilmiştir[7].

Doğal Dil İşleme uygulamalarının oluşturulmasında kişisel bilgiler, sağlık kayıtları gibi hassas nitelikli veriler toplanabilmektedir. Bunların yanında telif hakları gibi gizli veriler de NLP uygulamalarında kullanılabilmektedir[6]. Toplanan bu kişisel veriler işlenip saklandığı için veri gizliliği, doğal dil işleme uygulamalarında ele alınması gereken çok önemli bir etik konudur. Bu verilerin kötü ve uygun olmayan amaçlarla kullanılması, ciddi gizlilik ihlallerine ve bireylerin ve toplumun zarar görmesine yol açabilir.

NLP'de veri gizliliğinin sağlanması için uygun veri koruma ve veri güvenliği önlemlerinin alınması gerekmektedir. Kullanılacak veriler, şifrelenebilir, güvenli depolama alanlarında saklanabilir ve bu alanlara eriim için yetkilendirme yapılabilir. Bu sayede, verilerin yetkisiz kişilerce ulaşılmasının ve kötüye kullanımının önüne geçilebilir. Verileri toplamadan ve işlemeden önce bireylerın bu konuda bilgilendirilmesi ve onaylarının alınması gerekmektedir. Bireyler kişisel verilerinin, ne şekilde ne sebeple ve nasıl kullanılacağı konusunda açık ve kapsamlı şekilde bilgilendirilmelidir. Kanun ve yönetmelirde belirtildiği üzere, bireyin her an verilerinin toplanması, saklanılması ve işlenmesi onayından vazgeçme veya verilerinin silinmesini talep etme haklarına saygı duyulmalıdır.

NLP uygulamalarında veri gizliliğinin sağlanması için bir diğer yol ise toplanan verilerin anonimleştirilmesidir. Verilerin anonimleştirilmesi, verilerin işlenmeden önce, bu verilerden bireyleri tanımlayıcı kişisel ve hassas nitelikli bilgilerin çıkarılması işlemidir. Bu sayede, bireylerin gizliliğinin korunması ve kişisel verilerinin uygun olmayan amaçlarla kullanılması önlenebilir.


## SONUÇ

Sonuç olarak, Doğal Dil İşleme uygulamaları geliştirirken, uygulamanın gerçek dünyadaki etkisinin farkında olmamız ve amaçladığımız hedefler ile elde edilen sonuçlar arasındaki ilişkiyi analiz edebilmemiz gerekmektedir. NLP uygulamalarının sorumlu kullanımı, ön yargı, eşitlik ve veri gizliliği konularının gözetilmesini ve bu alanlarda doğan etik sonuçların dikkate alınmasını gerektirir. Bu etik konularının göz ardı edilmemesi kritiktir.

Eşit, toplum etiğine uyumlu, mevcut düzenlemelere ve bireylerin veri gizliliğine saygılı NLP modellerinim varlığı toplumsal ve kurumların Doğal Dil İşleme uygulamalarına olan güven, destek ve saygısını arttıracaktır. Bu durumun, NLP uygulamalarının gelişimini hızlandıracak bir bir etki yaratabileceği gerçeği unutulmamalıdır. Teknolojideki gelişimin devam etmesi için bu teknolojinin gerektirdiği yüksek enerji ve ortaya koyduğu çevresel etkinin dikkate alınması, toplum ve NLP uygulamaları için uzun vadede önemlidir.


## KAYNAKÇA

1.	The ethics of artificial intelligence: Issues and initiatives, Study from Panel for the Future of Science and Technology, European Parliamentary Research Service, Scientific Foresight Unit (STOA), PE 634.452, Mart 2020.
2.	Ethics in Natural Language Processing, https://web.archive.org/web/20231220011711/https://dida.do/blog/ethics-in-natural-language-processing, Marty Oelschläger, Aralık 2021.
3.	The Social Impact of Natural Language Processing, Dirk Hovy, Shannon L. Spruit.
4.	Ethical Considerations in Artificial Intelligence Courses, Emanuelle Burton et al., 2017
5.	Towards Climate Awareness in NLP Research, Daniel Hershcovich and Nicolas Webersinke and Mathias Kraus and Julia Anna Bingler and Markus Leippold, arXiv ön baskısı, 2205.05071, 2022.
6. Ethics and Privacy in AI and Big Data: Implementing Responsible Research and Innovation, Bernd Carsten Stahl et al., IEEE Security & Privacy, vol. 16, 2018.
7. Kişisel Verilerin Korunması Kanunu, Resmî Gazete, 07.04.2016, Türkiye.

## ÖĞRENCİ BİLGİLERİ
    Alperen Demir, Erciyes Universitesi, 1030510268
