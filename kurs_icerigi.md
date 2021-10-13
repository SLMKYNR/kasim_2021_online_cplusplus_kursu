# Online C++ Kursu İçeriği

## C++ Dilinin Genel Tanıtımı
+ C++ dilinin tarihçesi _(history of C++)_
+ C++ dili ve programlama paradigmaları
+ C++ dili standartları
+ C++98 – 03
+ C++11
+ C++14
+ C++17
+ C++20
+ eski C++ ve modern C++

## C Dili ve C++ İçindeki C Dili _(C in C++)_
+ C dilinden C++ diline geçiş
+ işlev bildirimleri ve tanımlamalarına ilişkin farklılıklar
+ türlere ve tür dönüşümlerine ilişkin farklılıklar
+ C’de geçerli C++’da geçersiz durumlar
+ C99 ve C++

## Temel Kavramlar _(Basic Concepts)_
+ tamamlanmış ve eksik türler _(complete & incomplete types)_
+ tek tanımlama kuralı _(one definition rule)_
+ ifadelerin değer kategorileri _(value categories)_
+ tanımsız davranış _(undefined behavior)_
+ derleyiciye bağlı davranışlar _(implementation defined & implementaion specified)_
+ derleyici eklentileri _(compiler extensions)_
+ kapsam ve isim arama _(scope & name lookup)_
+ erişim kontrolü _(access control)_
+ çift anlamlılık hatası _(ambiguity)_

## İlk Değer Verme _(Initialization)_
+ eş biçimli ilk değer verme _(uniform initialization)_
  + daraltıcı dönüşümler _(narrowing conversions)_
  + _most vexing parse_
+ doğrudan ilk değer verme _(direct intialization)_
+ değerle başlatma _(value initialization)_
+ kopyalama ile ilk değer verme _(copy initialization)_
+ varsayılan ilk değer verme _(default initialization)_
+ bileşiklere ilk değer verme _(aggregate initialization)_

## Tür Çıkarımı _(Type Deduction)_
+ auto belirteci ile tür çıkarımı _(auto type deduction)_
+ decltype belirteci ile tür çıkarımı _(decltype type deduction)_
+ sonradan gelen geri dönüş türü _(trailing  return type)_
+ auto geri dönüş değeri türü _(auto return type)_

## enum Sınıfları _(enum Classes)_
+ geleneksel enum türleri _(conventional enum types)_
+ baz tür seçimi _(underlying type)_
+ tür dönüşümleri _(type conversions)_
+ enum sınıfları ve kapsam _(enum classes & scope)_

## Sabit İfadeleri _(Constant Expressions)_
+ const anahtar sözcüğü ve const semantiği _(const qualifier and const semantics)_
+ const nesneler _(const objects)_
+ constexpr anahtar sözcüğü _(constexpr specifier)_
+ constexpr işlevler _(constexpr functions)_

## İşlevlerin Varsayılan Argüman Alması _(Default Arguments)_

## Referans Semantiği (Reference Semantics)
+ sol taraf referansları _(L value references)_
+ sağ taraf referansları _(R value references)_
+ referanslar ve const semantiği _(references & const semantics)_
+ referanslar ile göstericilerin karşılaştırılması _(differences between pointers & references)_
+ parametresi referans olan işlevler _(function with reference parameters)_
+ referans döndüren işlevler _(function returning references)_

## İşlev Yüklemesi _(Function Overloading)_
+ genel kurallar
+ yüklenmiş işlev çözümlenmesi _(function overload resolution)_
+ const yüklemesi _(const overloading)_
+ extern “C” bildirimi _(extern C declarations)_
+ işlev yüklemesinde dikkat edilmesi gereken durumlar

## Tür Dönüştürme Operatörleri _(Type-cast Operators)_
+ static_cast<> operatörü
+ const_cast<> operatörü
+ reinterpret_cast<> operatörü
+ dynamic_cast<> operatörü 

## Sınıflara giriş _(Introduction to Classes)_
+ sınıf kapsamı _(class scope)_
sınıflar ve isim arama _(classes & name lookup)_
+ erişim kontrolü ve veri gizleme _(access control & data hiding)_
  + public öğeler _(public members)_
  + private öğeler _(private members)_
  + protected öğeler _(protected members)_
+ sınıfların öğeleri _(class members)_
  + sınıfların veri öğeleri _(data members of classes)_
    + non-static veri öğeleri _(non-static data members)_
    + mutable veri öğeleri _(mutable data members)_
    + static veri öğeleri _(static data members)_ 
  + sınıfların üye işlevleri
    + non-static üye işlevler
    + const üye işlevler
    + static üye işlevler
  + this göstericisi ve \*this
  + sınıfların tür öğeleri _(type members)_
+ sınıfların kurucu işlevleri _(constructors)_
  + kurucu işlev ilk değer verme listesi _(constructor initializer list)_
  + delege eden kurucu işlevler _(delegating constructors)_
  + explicit kurucu işlevler _(explicit constructors)_
+ sınıfların sonlandırıcı işlevleri _(destructors)_
+ üye işlevlerin çağrılması _(member function calls)_
+  sınıflar ve const doğruluğu _(classes & const correctness)_
  + const sınıf nesneleri _(const objects)_
  + const üye fonksiyonlar _(const member fuctions)_
+ geçici sınıf nesneleri _(temporary objects)_
+ otomatik tür dönüşümleri _(implicit type conversions)_
+ mutable anahtar sözcüğü _(mutable keyword)_
+ friend bildirimi _(friend declarations)_ 
  + friend bildirimi ve veri gizleme _(friend declarations)_
  + global işlevlere friend bildirimi _(friend global function declarations)_
  + sınıfların üye işlevlerine friend bildirimi _(friend class member function declrations)_
  + sınıflara friend bildirimi _(friend class declarations)_
  + avukat-müvekkil idiyomu _(attorney-client idiom)_


## Sınıfların Özel Üye İşlevleri ve Kopyalama İşlemleri _(Special Member Functions & Copy Control)_
+ sınıfların özel işlevleri
  + default constructor _(varsayılan kurucu işlev)_
  + destructor _(sonlandırıcı işlev)_
  + copy constructor _(kopyalayan kurucu işlev)_
  + move constructor _(taşıyan kurucu işlev)_
  + copy assignment _(kopyalayan atama işlevi)_
  + move assignment _(taşıyan atama işlevi)_
+ özel işlevlerin default edilmesi
+ özel işlevlerin delete edilmesi
+ sınıflar ve taşıma semantiği _(move semantics)_
+ _rule of zero_
+ _rule of five_
+ kopyala takas et idiyomu _(copy & swap idiom)_
+ kopyalamanın eliminasyonu _(copy elision)_
  + zorunlu kopyalama eliminasyonu _(mandatory copy elision)_
## Operatör Yüklemesi _(Operator Overloading)_

+ operatör yüklemesine ilişkin genel kurallar
+ üye operatör fonksiyonları _(member operator functions)_
+ global operatör fonksiyonları _(global operator functions)_
+ aritmetik operatörlerin yüklenmesi
+ karşılaştırma operatörlerinin yüklenmesi _(overloading of relational operators)_
+ "++" ve "--" operatörlerinin yüklenmesi
+ ok operatörü ve içerik operatörlerinin yüklenmesi 
+ [] operatörünün yüklenmesi
+ fonksiyon çağrı operatörünün yüklenmesi
+ tür dönüştürme operatör fonksiyonları _(type-cast operator functions)_
+ programcının tanımladığı sabitler _(user-defined literals)_

## Dinamik Ömürlü Nesneler _(Dynamic Objects)_
+ new ve delete ifadeleri _(new & delete expressions)_ 
+ new[] ve delete [] ifadeleri
+ operator new işlevleri
+ operator delete işlevleri
+ operator new ve operator delete işlevlerinin yüklenmesi
+ std::bad_alloc
+ std::set_new_handler ve std::get_new_handler
+ placement new operatörleri
+ nothrow new

## Tür Eş İsimleri _(Type Alias)_
+ typedef bildirimleri _(typedef declarations)_
+ using bildirimleri _(using declarations)_

## İsim Alanları _(Namespaces)_
+ isim alanlarının oluşturulması
+ isim alanları ve isim arama _(namespaces & name lookup)_ 
+ çözünürlük operatörü ve isim alanları _(scope resoşution operator & namespaces)_ 
+ using bildirimi _(using declaration)_
+ using namespace direktifi _(using namespace directive)_ 
+ argümana bağlı isim arama _(argument dependent lookup)_
+ isimsiz isim alanı _(unnamed namespace)_
+ içsel isim alanları _(nested namespaces)_
+ inline isim alanları _(inline namespaces)_
+ isim alanı eş ismi _(namespace alias)_
+ işlev yüklemesi ve isim alanları _(function overloading & namespaces)_ 

## Sınıflar ve Kalıtım _(Classes & Inheritance)_
+ nesne yönelimli programlama ve kalıtım _(OOP & inheritance)_
+ public kalıtımı _(public inheritance)_
+ çalışma zamanı çok biçimliliği _(runtime polymorphism)_
  + sanal işlevler _(virtual function)_
  + saf sanal işlevler _(pure virtual function)_
  + sanal sonlandırıcı işlev _(virtual destructor)_
  + sanal kurucu işlev idiyomu _(virtual constructor idiom)_
  + override bağlamsal anahtar sözcüğü _(override contextual keyword)_
  + nesne dilimlenmesi _(object slicing)_
  + sanal olmayan arayüz idiyomu _(non-virtual interface idiom)_
+ final bağlamsal anahtar sözcüğü _(final contextual keyword)_ 
  + final sınıflar _(final classes)_
  + _final override_
+ çoklu kalıtım _multiple inheritance)_
  + çoklu kalıtımda kapsam ve isim arama_(multiple inheritance & name lookup)_ 
  + çoklu kalıtımda sınıfın özel işlevleri
  + elmas formasyonu _(diamond formation)_
  + sanal kalıtım _(virtual inheritance)_
  + çoklu kalıtım ve kalıtımla alınan kurucu işlevler
  + çoklu kalıtımda kopyalama ve taşıma işlemleri
+ private kalıtımı _(private inheritance)_
+ protected kalıtımı _(protected inheritance)_
+ sınıf içi using bildirimi _(using declarations in class definitions)_
+ kalıtımla alınan kurucu işlevler _(inherited constructors)_

## Olağan Dışı Durumların İşlenmesi _(Exception Handling)_
+ exception güvenliği _(exception safety) _
+ hata nesnelerinin gönderilmesi _(throwing exception objects)_
  + throw deyimi _(throw statement)_
  + rethrow deyimi _(rethrow statement)_
+ try blokları _(try blocks)_
+ catch blokları _(cathc blocks)_
  + catch all
+ yakalanamayan hata nesnesi _(uncaught exception)_
+ std::terminate
+ std::set_terminate
+ hata nesnesinin yeniden gönderilmesi _(rethrow statement)_
+ yığının geri sarımı _(stack unwinding)_
+ kurucu işlevlerden exception gönderimi
+ sonlandırıcı işlevler ve hata gönderimi
+ exception handling ve kalıtım _(eception handling & inheritance)_
+ exception handling ve dinamik ömürlü sınıf nesneleri _(eception handling & dynamic objects)_
+ exception  güvenliği için akıllı göstericilerin kullanımı _(eception handling & smart pointers)_
+ işlev try blokları _(function try block)_
+ noexcept belirleyicisi _(noexcept specifier)_
+ beklenmeyen hata nesnesi _(unexpected excetion)_
+ std::unexpected_exception
+ std::exception sınıfı ve hiyerarşisi
  + std::exception sınıfı ve what sanal fonksiyonu
  + std::logic_error
    + std::invalid_argument
    + std::domain_error
    + std::length_error
    + std::out_of_range
    + std::future_error
  + std::runtime_error
    + std::range_error
    + std::overflow_error
    + std::underflow_error
  + std::system_error
  + std::regex_error
  + std::bad_alloc
  + std::bad_typeid
  + std::bad_cast
  + std::bad_exception
  + std::bad_weak_ptr
  + std::bad_function_call
+ kendi hata sınıflarımızı oluşturmak
+ exception garantileri _(eception guarantees)_
  + _basic exception guarantee_
  + _strong exception gurantee_
  + _no throw gurantee_
+ std::current_exception
+ std::exception_ptr
+ std::rethrow_exception

## Çalışma Zamanında Tür Belirlenmesi _(run-time type information)_
+ dynamic_cast operatörü
+ typeid operatörü
+ std::typeinfo sınıfı
+ std::bad_typeid

## std::string sınıfı
+ genel kavramlar
+ string::size_type
+ string::npos
+ arama işlevleri
+ set işlemleri
+ erişim işlemleri
+ karşılaştırma işlevleri
+ sayısal dönüşüm işlevleri
+ small string optimization

## Bileşik Nesneler _(Composition)_
+ öğe olan nesneler ve özel işlevler, kopyalama kontrolü.
+ öğe olan nesneler ve erişim kontrolü
+ bileşik nesnelerin kullanıldığı temalar

## İçsel türler _(Type Members)_
+ sınıf içinde yapılan eş isim bildirimleri
+ içsel sınıflar _(nested classes)_
+ _pimpl_ idiyomu

## Şablonlar _(Templates)_
+ şablon tür parametreleri _(template type parameters)_
+ şablon sabit parametreleri _(template non-type parameters)_
+ şablon şablon parametreleri _(template template parameters)_
+ şablon argümanları _(template arguments)_
+ şablonlardan kod üretimi _(template instantiation)_
+ fonksiyon şablonları _(function templates)_
  + fonksiyon şablonlarında tür çıkarımı _(function template argument deduction)_
  + fonksiyon şablonlarının yüklenmesi _(function template overloading)_
+ sınıf şablonları _(class templates)_
+ kurucu işlev ile tür çıkarımı _(CTAD)_
+ üye şablonlar _(member templates)_
+ şablonların özelleştirilmesi _(template specialization)_
  + tam özelleştirme _(explicit/full specialization)_
  + kısmi özelleştirme _(partial specialization)_
+ _sfinae_
+ değişken sayıda parametreli şablonlar _(variadic templates)_
+ mükemmel gönderim _(perfect forwarding)_
+ katlama ifadeleri _(fold expressions)_
+ _if constexpr_
+ değişken şablonları _(variable templates)_
+ eş isim şablonları _(alias templates)_

## İteratörler _(Iterators)_
+ aralık kavramı _(ranges)_
+ iteratörlerin kategorileri _(iterator categories)_
  + input iterator
  + output iterator
  + forward iterator
  + bidirectional iterator
  + random access iterator
+ kapların begin ve end işlevleri
+ global begin ve end işlevleri
+ iterator işlevleri
  + std::next
  + std::prev
  + std::iter_swap
  + std::advance
  + std::distance
+ iterator uyumlandırıcıları _(iterator adaptors)_
  + akım iteratörleri _(stream iterators)_
    + istream_iterator
    + ostream_iterator
    + istreambuf_iterator
    + ostreambuf_iterator
  + reverse iterators
  + move iterators
  + insert iterators
    + back_insert_iterator
    + front_insert_iterator
    + insert_iterator
+ iterator traits

## Kaplar _(Containers)_
+ STL kapları ve veri yapıları _(STL containers & data structures) _
+ sıralı kaplar _(sequence containers)_
  + std::vector
  + std::deque
  + std::string
  + std::array
  + std::list
  + std::forward_list
+ ilişkisel kaplar _(associative containers)_
  + std::set
  + std::multiset
  + std::map
  + std::multimap
+ sırasız ilişkisel kaplar _(unordered containers)_
  + std::unordered_set
  + std::unordered_multiset
  + std::unordered_map
  + std::unordered_multimap
+ kapların tür öğeleri _(type members of containers)_
+ kapların emplace işlevleri

## Kap Uyumlandırıcıları _(Container Adaptors)_
+ stack
+ queue
+ priority_queue

## Algoritmalar _(Algorithms)_
+ algoritmaların temel özellikleri ve genel ilkeler
+ salt okuyan algoritmalar _non-modifying algorithms)_
+ kap öğelerini değiştiren algoritmalar _(modifying algorithms)_
+ kap öğelerini konumlandıran algoritmalar _(mutating algorithms)_
+ sıralama ile ilgili algoritmalar _(sorting algorithms)_
+ sıralanmış aralıklar üzerinde koşturulan algoritmalar _(sorted range algorithms)_
+ nümerik algoritmalar _(numeric algorithms)_
+ algoritmaların lambda ifadelerini kullanması _(algorithms & lambda expressions)

## Lambda İfadeleri _(Lambda Expressions)_
+ kapanış türleri ve kapanış nesneleri _(closure types and closure objects)_
+ lambda ifadeleri ve tür çıkarımı _(lambda expressions and type deduction)_
+ lambda yakalama ifadeleri _(lambda captures)_
+ _lambda init capture_
+ capture this 
+ capture _*this_
+ mutable lambdalar
+ trailing return type
+ constexpr lambda ifadeleri
+ templated lambda (C++20)
+ lambda expressions in unevaluated context
+ genelleştirilmiş lambda ifadeleri _(generalized lambda expressions)_
+ algoritmalarda lambda ifadelerinin kullanımı
+ lambda ifadeleri C++11/14/17/20
+ lambda idiyomları _(lambda idioms)_

## Akıllı Gösterici Sınıfları _(Standard Smart Pointer Classes)_
+ unique_ptr sınıfı
  + std::make_unique işlev şablonu
  + std::default_delete & custom deleters
  + tipik hatalar
+ shared_ptr sınıfı
  + referans sayımı _(reference counting)_
  + std::make_shared işlev şablonu
  + weak_ptr sınıfı

## Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
+ giriş çıkış akımlarına ilişkin standart sınıflar _(standard stream classes)_
+ global akım nesneleri _(global stream objects)_
+ formatlı giriş çıkış işlemleri _(formatted input output)_
+ << ve >> operatörlerinin yüklenmesi _(inserter & extractors)_
+ formatlama ve formatlama işlemleri _(formatting)_
+ manipülatörler _(manipulators)_
+ akımın durumu _(condition states)_
+ string akımları _(stringstreams)_
+ dosya işlemleri _(file operations)_
+ formatsız giriş ve çıkış işlemleri _(unformatted input output)_
+ bellek üstünde yapılan giriş çıkış işlemleri _(in-memory input/output operations)_

## Bazı önemli STL Öğelerinin Tanıtımı
+ std::pair
+ std::tuple
+ std::initializer_list
+ std::bitset
+ std::regex
+ type_traits kütüphanesi
+ std::allocator
+ std::ratio
+ std::chrono
+ standart random kütüphanesi
+ std::string_view sınıfı
+ std::optional sınıfı
+ std::variant sınıfı
+ std::any sınıfı
+ std::byte
+ std::invoke

## Tamamlayıcı Araçlar ve Sentaks Öğeleri
+ static_assert 
+ decltype(auto)
+ declval
+ üye fonksiyon göstericileri _(member function pointers)_
+ ham string sabitleri _(raw string literals)_
+ ikilik sayı sisteminde yazılan sabitler _(binary literals)_
+ basamak ayırıcısı _(digit seperator)_
+ ilk değer vermeli if deyimi _(if with initializer)_
+ ilk değer vermeli switch  deyimi _(if with initializer)_
+ alignas belirteci _(alignas specifier)_
+ alignof operatörü _(alignof operator)_
+ yapısal bağlama _(structural binding) (C++17)_
+ attribute’lar _(attributes)_

## Concurrency
+ memory model
+ thread’ler ve thread yönetimi
+ std::this_thread isim alanı _(this\_thread namespace)_
+ data race kavramı ve data_race’den kaçınma
+ standart mutex sınıfları ve mutex işlemleri
+ lock_guard ve unique_lock sınıfları
+ std::condition_variable sınıfı
+ std::future ve std::promise sınıfları
+ std::async işlevi
+ atomik türler _(atomic types)_
+ görev tabanlı _(task based)_ programlama
+ std::packaged_task sınıfı
+ paralel STL algoritmaları _(parallel STL algoerithms)__
