# Akıllı Tarım Yönetim Sistemi - Proje Akışı ve Haftalık İlerleme

Bu dosya, Algoritma Alimleri takımının haftalık proje ilerlemesini ve üyelerin görev dağılımlarını içermektedir.

## 1. Hafta (7-12 Mart)
Murat Baycan (Scrum Master / Yönetici): GitHub reposu oluşturuldu, Trello ve Discord iletişim kanalları kuruldu. Proje akış dokümanı eklendi.
Selahattin Ali Kılıç : Teknoloji araştırması ve seçimi üzerinde çalışıyor.
Ömer Akhan: Geliştirme ortamı kurulumu üzerinde çalışıyor.
Binnur Aslan: Proje analizi ve kapsam tanımı üzerinde çalışıyor.
Ülkü Tuana Kara: Gereksinim toplama ve belgeleme üzerinde çalışıyor. 

Selahattin Ali Kılıç:
1. Projenin Amacı 
Akıllı tarım sistemleri sensörlerden elde edilen çevresel verileri analiz ederek tarımsal üretim 
süreçlerini daha verimli hale getirmeyi amaçlayan sistemlerdir. Bu projede amaç; toprak 
nemi, hava durumu ve bitki sağlığı gibi verileri analiz ederek sulama, gübreleme ve hastalık 
yönetimi gibi süreçleri optimize eden bir sistem tasarlamaktır. Sensörlerden elde edilen veriler 
analiz edilerek çiftçilere doğru zamanda doğru müdahaleyi yapabilmeleri için öneriler 
sunulacaktır. 
2. Sistem İçin Gerekli Teknolojiler 
Akıllı tarım sistemi geliştirirken farklı yazılım ve donanım teknolojilerinin birlikte 
kullanılması gerekmektedir. Bu sistemde sensörlerden veri toplanması, verilerin işlenmesi, 
analiz edilmesi ve kullanıcıya sunulması için çeşitli teknolojilere ihtiyaç duyulmaktadır. 
Bu proje kapsamında aşağıdaki teknoloji alanları kullanılacaktır: 
 Backend geliştirme 
 Sensör veri iletişimi 
 Makine öğrenmesi 
 Veritabanı yönetimi 
 Kullanıcı arayüzü 
3. Teknoloji Analizi 
Backend – Python 
Python veri analizi ve makine öğrenmesi alanlarında oldukça yaygın kullanılan bir 
programlama dilidir. Geniş kütüphane desteği sayesinde sensör verilerinin işlenmesi ve 
sistemin backend tarafının geliştirilmesi için uygun bir seçenektir. 
Makine Öğrenmesi – TensorFlow 
TensorFlow yapay zeka ve makine öğrenmesi uygulamaları geliştirmek için kullanılan güçlü 
bir kütüphanedir. Sensörlerden elde edilen veriler kullanılarak sulama tahmini, bitki stres 
analizi ve verim tahmini gibi modeller oluşturulabilir. 
Sensör Veri İletişimi – MQTT 
MQTT, IoT sistemleri için geliştirilmiş hafif bir iletişim protokolüdür. Sensörlerden gelen 
verilerin düşük bant genişliği kullanarak hızlı ve güvenilir bir şekilde sisteme aktarılmasını 
sağlar. 
Veritabanı – PostgreSQL 
PostgreSQL güçlü ve güvenilir bir açık kaynak veritabanı sistemidir. Sensörlerden elde edilen 
verilerin saklanması, yönetilmesi ve analiz edilmesi için uygun bir altyapı sunar.
Web Arayüzü – React 
React modern web uygulamaları geliştirmek için kullanılan popüler bir JavaScript 
kütüphanesidir. Kullanıcıların sensör verilerini grafikler, bildirimler ve analiz sonuçları 
şeklinde görüntüleyebileceği bir arayüz geliştirmek için kullanılabilir. 
4. Sektör Görüşü (Uzman Görüşü) 
Akıllı tarım alanında çalışan bir sektör uzmanından alınan bilgilere göre akıllı tarım 
sistemlerinde çevresel verileri toplamak amacıyla çeşitli sensörler kullanılmaktadır. Bunlar 
arasında toprak nem ve sıcaklık sensörleri, EC ve pH sensörleri, iklim sensörleri (hava 
sıcaklığı, nem, yağış miktarı ve rüzgar hızı gibi parametreleri ölçen sensörler) ve NDVI 
sensörleri bulunmaktadır. Son dönemlerde hastalık ve zararlı popülasyonlarını tespit etmek 
amacıyla yapay zeka destekli sensörler de kullanılmaya başlanmıştır. 
Sensörlerden elde edilen veriler genellikle mobil uygulamalar veya bilgisayar sistemleri 
üzerinden çiftçiler ve mühendisler tarafından anlık olarak takip edilmektedir. Bu sistemlerin 
temel amacı iklim değişikliği, kuraklık ve aşırı hava olaylarına karşı verim ve kaliteyi 
korumaktır. Ayrıca su, gübre ve pestisit kullanımını optimize ederek maliyetlerin azaltılması 
ve doğal kaynakların korunması hedeflenmektedir. 
Yapay zekâ tarım sektöründe özellikle hastalık ve zararlı tahmini, sulama optimizasyonu, 
bitki stres analizi, verim tahmini ve hasat sonrası süreçlerde kullanılmaktadır. Bununla birlikte 
akıllı tarım teknolojilerinin yaygınlaşmasının önündeki en önemli zorluklardan biri 
geliştiriciler ile çiftçiler arasındaki teknoloji bilgi farkıdır. Ayrıca arazi koşullarındaki altyapı 
eksiklikleri, enerji sorunları ve donanımın arazi şartlarına uyumu da önemli zorluklar arasında 
yer almaktadır. 
Bu bilgiler akıllı tarım alanında faaliyet gösteren bir şirkette çalışan sektör uzmanı ile yapılan 
görüşmeden elde edilmiştir. 
5. Önerilen Teknoloji Yığını 
Yapılan araştırmalar sonucunda bu proje için aşağıdaki teknoloji yığınının kullanılması 
önerilmektedir: 
 Backend → Python 
 Makine Öğrenmesi → TensorFlow 
 Sensör Veri İletişimi → MQTT 
 Veritabanı → PostgreSQL 
 Web Arayüzü → React 
Bu teknoloji yığını sensör verilerinin toplanması, analiz edilmesi ve kullanıcıya sunulması için 
ölçeklenebilir ve sürdürülebilir bir altyapı sağlayacaktır.
