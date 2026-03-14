# Akıllı Tarım Yönetim Sistemi - Proje Akışı ve Haftalık İlerleme

Bu dosya, Algoritma Alimleri takımının haftalık proje ilerlemesini ve üyelerin görev dağılımlarını içermektedir.

## 1. Hafta (7-12 Mart)
Murat Baycan (Scrum Master / Yönetici): GitHub reposu oluşturuldu, Trello ve Discord iletişim kanalları kuruldu. Proje akış dokümanı eklendi.
Selahattin Ali Kılıç : Teknoloji araştırması ve seçimi üzerinde çalışıyor.
Ömer Akhan: Geliştirme ortamı kurulumu üzerinde çalışıyor.
Binnur Aslan: Proje analizi ve kapsam tanımı üzerinde çalışıyor.
Ülkü Tuana Kara: Gereksinim toplama ve belgeleme üzerinde çalışıyor. 

Ülkü Tuanna Kara : 
Proje konusu ve kapsamı:
Günümüzde tarım sektöründe su kaynaklarının verimli kullanılması, ürün veriminin artırılması ve çevresel etkilerin azaltılması büyük önem taşımaktadır. Akıllı Tarım Yönetim Sistemi, sensör verileri ve makine öğrenmesi teknolojilerini kullanarak tarımsal üretim süreçlerini daha verimli, sürdürülebilir ve otomatik hale getirmeyi amaçlayan bir yazılım sistemidir. Bu proje,  bahsedilen problemlere teknolojik çözümler sunmayı hedeflemektedir. 
Sistem, tarım alanına yerleştirilen sensörler aracılığıyla toprak nemi, sıcaklık, hava durumu ve diğer çevresel verileri sürekli olarak toplar. Toplanan bu veriler bir sunucuya iletilerek veritabanında saklanır ve makine öğrenmesi algoritmaları kullanılarak analiz edilir. Analiz sonuçlarına göre sistem, sulama, gübreleme ve ilaçlama gibi tarımsal işlemler için öneriler üretir veya otomatik kontrol mekanizmaları aracılığıyla bu işlemleri gerçekleştirebilir.
Kullanıcılar, geliştirilecek olan bu web tabanlı arayüz sayesinde tarım alanlarındaki sensör verilerini takip edebilir. Takip edilen bu analiz sonuçlarını görüntüleyebilir ve gerekli durumlarda müdahale edilebilir. Bu sayede çiftçiler tarım süreçlerini daha bilinçli şekilde yönetebilir ve kaynak kullanımını optimize edebilirler.
Sonuç olarak Akıllı Tarım Yönetim Sistemi, tarımsal üretimde dijital dönüşümü destekleyen, veri odaklı karar verme süreçlerini geliştiren ve üretim verimliliğini artırmayı hedefleyen yenilikçi bir çözüm sunmaktadır.
Sistem amaçları: 
Sistemin temel amaçlarından biri elde edilen verileri analiz ederek tarımsal üretim süreçlerini daha verimli hale getirmektir.
Tarımda su, gübre ve ilaç gibi kaynakların gereksiz kullanımını önlemek.
Bu sistem sensör verilerini kullanarak bazı tarımsal işlemleri otomatik hale getirmeyi hedefler.
Makine öğrenmesi algoritmaları kullanılarak geçmiş veriler analiz edilir ve gelecekte oluşabilecek durumlar hakkında tahminler yapılır. Bu sayede olası riskler önceden tespit edilebilinir. 



Fonksiyonel Gereksinimler :
Sensör verisi toplama: Sistem, tarım alanında bulunan sensörlerden toprak nemi verisini toplayabilmelidir. Sistem, sensörlerden sıcaklık ve nem gibi çevresel verileri alabilmelidir. Sistem, sensörlerden gelen verileri belirli zaman aralıklarında otomatik olarak almalıdır.
Veri Saklama : Sistem, sensörlerden gelen tüm verileri veritabanında saklamalıdır. Sistem, geçmiş sensör verilerini saklayarak daha sonra analiz edilmesini sağlamalıdır.
Veri Analizi: Sistem, toplanan sensör verilerini analiz edebilmelidir. Sistem, makine öğrenmesi algoritmaları kullanarak tarımsal süreçler hakkında tahminler oluşturmalıdır.
Sulama Öneri Sistemi :  Sistem, toprak nem seviyesine göre sulama önerisi oluşturmalıdır. Sistem, gerektiğinde sulama işlemini otomatik olarak başlatabilmelidir (sistem donanımı destekliyorsa).
Kullanıcı Yönetimi: Sistem kullanıcıların kayıt olmasını sağlamalıdır. Sistem kullanıcıların giriş yapmasını sağlamalıdır. Sistem kullanıcı bilgilerini güvenli şekilde saklamalıdır.
Web Arayüzü: Sistem, kullanıcıların sensör verilerini web arayüzü üzerinden görüntülemesine izin vermelidir. Sistem, kullanıcıların geçmiş sensör verilerini grafik veya rapor olarak görüntülemesini sağlamalıdır.
Mobil Uygulama: Sistem, kullanıcıların mobil uygulama üzerinden sensör verilerini görüntülemesini sağlamalıdır. Sistem, kullanıcıya gerekli durumlarda bildirim göndermelidir.
Bildirim Sistemi :  Sistem, toprak nemi kritik seviyeye düştüğünde kullanıcıya bildirim göndermelidir. Sistem, sistem tarafından oluşturulan önerileri kullanıcıya iletmelidir.




Teknik Gereksinimler :
Sunucu Tarafı Gereksinimler: Sistemin arka planında çalışan ve sensör verilerini işleyen sunucu tarafı yazılımı Python programlama dili kullanılarak geliştirilecektir. Python, veri analizi ve makine öğrenmesi uygulamaları için güçlü kütüphanelere sahip olduğu için tercih edilmektedir.
Makine Öğrenmesi Gereksinimleri: Sistem, sensörlerden elde edilen verileri analiz etmek ve tarımsal tahminler oluşturmak amacıyla makine öğrenmesi algoritmaları kullanacaktır. Bu amaçla TensorFlow kütüphanesi kullanılacaktır.
TensorFlow ile geliştirilecek modeller şu amaçlarla kullanılabilir:
-Toprak nemi analizleri
-Sulama önerisi oluşturma
-Bitki sağlığı tahmini
-Verim tahmini
Sensör Veri İletişim Gereksinimleri: Tarım alanına yerleştirilen sensörlerden elde edilen verilerin sisteme iletilmesi için MQTT (Message Queuing Telemetry Transport) protokolü kullanılacaktır.
Veritabanı Gereksinimleri: Sistem, sensör verilerini, kullanıcı bilgilerini ve analiz sonuçlarını saklamak için PostgreSQL veritabanını kullanacaktır. PostgreSQL veritabanı şu verileri saklayacaktır:
-Sensör verileri
-Kullanıcı hesapları
-Sistem tarafından üretilen analiz sonuçları
-Geçmiş veri kayıtları
Web Arayüzü Gereksinimleri:  Kullanıcıların sistemdeki verileri görüntüleyebilmesi ve yönetebilmesi için React tabanlı bir web arayüzü geliştirilecektir.
Web arayüzü sayesinde kullanıcılar:
-Sensör verilerini görüntüleyebilir
-Analiz sonuçlarını inceleyebilir
-Sistem önerilerini takip edebilir.


Mobil Uygulama Gereksinimleri:  Sisteme mobil cihazlardan erişim sağlamak için React Native kullanılarak bir mobil uygulama geliştirilecektir. Mobil uygulama kullanıcıların:
-Sensör verilerini görüntülemesine
-Bildirim almasına
-Tarım süreçlerini takip etmesine olanak sağlar.
Geliştirme Ortamı Gereksinimleri:  Projenin geliştirilmesi için aşağıdaki araçlar kullanılacaktır:
-Visual Studio Code → Kod geliştirme ortamı
-Python → Backend geliştirme
-Node.js → Frontend geliştirme için gerekli ortam
-PostgreSQL → Veritabanı yönetimi

Performans Gereksinimleri : 
Veri İşleme Hızı:  Sistem, sensörlerden gelen verileri en fazla 5 saniye içinde işleyebilmelidir. Sistem, sensörlerden gelen verileri gerçek zamanlıya yakın bir şekilde analiz edebilmelidir.
Sistem Kapasitesi: Sistem aynı anda en az 1000 sensörden gelen veriyi işleyebilmelidir. Sistem aynı anda birden fazla kullanıcının web veya mobil uygulama üzerinden sisteme erişmesini desteklemelidir.
Sistem Yanıt Süresi: Sensör verileri sistemde düzenli aralıklarla güncellenmeli ve kullanıcı arayüzüne yansıtılmalıdır.
Sistem Güvenilirliği: Sistem kesintisiz çalışabilmeli ve veri kaybını önleyecek mekanizmalara sahip olmalıdır. Sistem arızası durumunda veriler güvenli şekilde korunmalıdır.
Ölçeklenebilirlik: Sistem ileride sensör sayısı arttığında veya kullanıcı sayısı yükseldiğinde performans kaybı yaşamadan çalışabilecek şekilde tasarlanmalıdır.

Güvenlik Gereksinimleri: 
Kullanıcı Kimlik Doğrulama: Sisteme erişen kullanıcılar giriş yapmadan sistem özelliklerini kullanamamalıdır. Kullanıcılar sisteme kullanıcı adı ve şifre ile giriş yapmalıdır. Kullanıcıların hesap bilgileri güvenli şekilde saklanmalıdır.
Yetkilendirme: Sistem farklı kullanıcı rollerini desteklemelidir. Kullanıcılar yalnızca kendi yetkileri dahilindeki işlemleri gerçekleştirebilmelidir.
Veri Güvenliği: Kullanıcı şifreleri veritabanında şifrelenmiş (hashlenmiş) olarak saklanmalıdır. Hassas veriler güvenli şekilde depolanmalıdır. Sistem veri kaybını önlemek için düzenli veri yedekleme mekanizmasına sahip olmalıdır.
Güvenli Veri İletişimi: Sensörlerden gelen veriler güvenli bir iletişim protokolü üzerinden gönderilmelidir. Web ve mobil uygulama ile sunucu arasındaki veri iletişimi HTTPS kullanılarak yapılmalıdır.
API Güvenliği: Sistem API’lerine erişim kimlik doğrulama tokenları ile korunmalıdır. Yetkisiz kullanıcıların API erişimi engellenmelidir.
Sistem Koruması: Sistem yetkisiz erişim girişimlerini tespit edebilmelidir. Sistem saldırılara karşı temel güvenlik önlemlerine sahip olmalıdır.

Gereksinim Önceliklendirmesi
Yüksek Öncelikli Gereksinimler
Bu gereksinimler sistemin temel çalışmasını sağlayan ve mutlaka gerçekleştirilmesi gereken özelliklerdir. Sistem bu özellikler olmadan çalışamaz.
-Sensörlerden veri toplama sistemi
-Sensör verilerinin veritabanında saklanması
-Sensör verilerinin analiz edilmesi
-Toprak nemine göre sulama önerisi oluşturulması
-Kullanıcı kayıt ve giriş sistemi
-Web arayüzü üzerinden sensör verilerinin görüntülenmesi
-Sensör verilerinin düzenli olarak güncellenmesi
Orta Öncelikli Gereksinimler
Bu gereksinimler sistemin kullanımını geliştiren ve kullanıcı deneyimini artıran özelliklerdir. Ancak sistem temel işlevlerini bu özellikler olmadan da gerçekleştirebilir.
-Mobil uygulama üzerinden sensör verilerinin görüntülenmesi
-Kullanıcılara bildirim gönderme sistemi
-Sensör verilerinin grafik ve rapor olarak gösterilmesi
-Makine öğrenmesi ile tahmin analizlerinin yapılması
Düşük Öncelikli Gereksinimler
Bu gereksinimler sistemin gelişmiş özelliklerini içerir ve projenin ilerleyen aşamalarında geliştirilebilir.
-Gelişmiş veri analiz raporları
-Uzun vadeli tarım verim tahminleri
-Kullanıcıların farklı tarım alanlarını karşılaştırabilmesi
-Gelişmiş veri görselleştirme araçları
