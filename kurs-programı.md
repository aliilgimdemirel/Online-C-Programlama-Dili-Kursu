# C Programlama Dili Kursu İçeriği

+ __Kursun Tanıtımı__
+ __C Programlama Dilinin Genel Tanıtımı__
	+ programlama dillerini birbirinden ayıran kriterler
		+ declarative ve imperative diller
		+ programlama paradigmaları
		+ seviye (level)
		+ mülkiyet
		+ statik ve dinamik tür kavramları
		+ prosedürel programlama ve C dili
	+ C dilinin kullanım alanları
	+ C dilinin temel özellikleri
	+ C dilinin tarihsel gelişimi ve C Standartları
		+ Klasik C
		+ C89
		+ C99
		+ C11
	+ C ve C++ ilişkisi

+ __Temel Kavramlar__
	+ atom (token) kavramı
		+ atom kategorileri
			+ anahtar sözcükler (keywords)
			+ isimler (identifiers)
			+ sabitler (constants - literals)
			+ string literalleri (string literals)
			+ operatörler (operators)
		+ atomlarına ayırma (tokenizing)
		+ en uzun atom kuralı (maximum munch)
	+ sayı sistemleri
		+ işaretli ve işaretsiz ikilik sayı sistemi
		+ dönüşümler
		+ bire tümleme işlemi
		+ ikiye tümleme işlemi
		+ onaltılık sayı sistemi
		+ sekizlik sayı sistemi
	+ nesneler (objects)
		+ tür (type) kavramı
		+ nesnelerin bellek alanları (storage)
		+ temel türler (fundemantal types)
		+ programcı tarafından tanımlanan türler (user defined types)
	+ ifadeler (expressions)
		+ ifade kategorileri (value categories)
			+ sol taraf değeri ifadesi (L value expression)
			+ sağ taraf değeri ifadesi (R value expression)
		+ sabit ifadesi (constant expression)
		
+ __Bir C Programı Oluşturmak__
	+ metin düzenleyici programlar ve text dosyaları
	+ kaynak dosya ve çeviri birimi
	+ derleyici program ve derleme süreci
		+ derleyici bulgu iletileri
		+ tanımsız davranış (undefined behavior)
		+ derleyiciye bağlı durumlar (implementation defined behavior)
		+ derleyici programların lojik kontrolleri
		+ derleyiciler ve kod optimizasyonu
		+ derleyici eklentileri (compiler extensions)
	+ önişlemci program (preprocessor)
	+ bağlayıcı program (linker) bağlama zamanı
	+ ide’ler ve yardımcı programlar
		+ statik kod analizi yapan programlar
		+ hata ayıklayıcı programlar
		
+ __Veri Türleri (Data Types)__
	+ varsayılan türler (fundemental types)
		+ tamsayı türleri (integer types)
		+ gerçek sayı türleri (floating types)
	+ programcı tarafından oluşturulan türler (user defined types)
	
+ __Bildirim ve Tanımlama (Declarations & Definitions)__
	+ bildirimler ve deyimler (declarations and statements)
	+ ilk değer verme (initialization)
	+ bildirim listesi
	+ tanımlama (definition)
+ __Kapsam ve İsim arama (Scope & Name Lookup)__
	+ kapsam (scope)
		+ kapsam kategorileri
			+ block scope
			+ file scope
			+ function prototype scope
			+ function scope
	+ isim arama (name lookup)
	+ isim çakışmaları (name collision)
	
+ __Ömür Kavramı (Storage Duration)__
	+ otomatik ömür (automatic storage class)
	+ statik ömür (static storage class)
	+ dinamik ömür (dynamic storage class)
	
+ __İşlevler (Functions)__
	+ işlevlerin tanımlanması (function definitions)
		+ işlevlerin parametre değişkenleri
		+ işlevlerin geri dönüş değerleri
		+ değerle çağrı (call by value)
		+ referansla çağrılan işlevler (call by reference)
		+ void işlevler
	+ return deyimi (return statement)
		+ ifadeli ve ifadesiz return deyimleri
	+ saf (pure) ve saf olmayan (impure) işlevler
	+ işlevlerin çağrılması (function calls)
		+ işlev çağrılarından elde edilen değerlerin kullanılması
	+ inline işlevler (inline functions)
	+ işlevlerin bildirilmesi (function declarations)
	
+ __Standart Kütüphane (Standard Library)__
	+ standart kütüphanenin varlık nedenleri
		+ ortak arayüz (common interface) ilkesi
		+ taşınabilirlik (portability)
		+ kodların tekrar kullanımı (code reuse)
	+ standart formatlı giriş çıkış işlevleri
		+ standart giriş akımı (standard input stream)
		+ standart çıkış akımları (standard output stream)
		+ standart hata akımı (standard error stream)
		+ akımların yönlendirilmesi (direction of the streams)
		+ printf işlevi
		+ scanf işlevi
	+ standart formatsız giriş ve çıkış işlemleri
		+ getchar
		+ putchar
	+ standart başlık dosyaları
	+ standart math kütüphanesi

+ __Operatörler (Operators)__
	+ temel kavramlar
		+ operatörlerin değer üretmesi
		+ operatör önceliği
		+ öncelik yönü (associativity)
		+ yan etki (side effect)
		+ yan etki noktası (sequence point)
	+ aritmetik operatörler
		+ toplama, çıkarma, çarpma, bölme ve kalan operatörleri
		+ işaret operatörleri (sign operators)
		+ artırma ve eksiltme operatörleri (increment & decrement operators)
	+ karşılaştırma operatörleri
		+ karşılaştırma idiyomları
		+ tipik hatalar
	+ lojik operatörler
		+ lojik yorumlama
		+ kısa devre davranışı
		+ tipik hatalar
		+ lojik ifadeler
		+ idiyomlar
	+ atama operatörleri
		+ atama operatörlerinin değer üretmesi
		+ yalın atama operatörü
		+ işlemli atama (compound assignment) operatörleri
		+ idiyomlar
	+ virgül operatörü
	+ öncelik operatörü
+ __Sabitler (Constants)__
	+ sabitlerin türleri
		+ tamsayı sabitleri (integer constants)
		+ gerçek sayı sabitleri (floating constants)
			+ üstel (scientific) notasyon
		+ karakter sabitleri
			+ kaçış sekansları (escape sequences)
			
+ __Kontrol Deyimleri__
	+ if deyimi
		+ genel sentaks
		+ else if merdiveni
		+ tipik yapılan hatalar
		+ test işlevleri
	+ döngü deyimleri
		+ while döngü deyimi
		+ do while döngü deyimi
		+ for döngü deyimi
		+ break deyimi
		+ continue deyimi
		+ iç içe döngüler
		+ döngü idiyomları
	+ switch deyimi
	+ goto deyimi
