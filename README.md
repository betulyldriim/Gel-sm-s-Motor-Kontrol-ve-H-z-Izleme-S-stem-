Detaylı Proje Açıklaması
Bu depo, Siemens TIA Portal ortamında geliştirilmiş, endüstriyel uygulamalara yönelik kapsamlı bir motor kontrolü ve hız izleme sistemini içermektedir. Proje, bir Siemens S7-1500 (veya S7-1200) PLC'nin programlanması ve bir Siemens HMI panelinin arayüz tasarımını bir araya getirmektedir. Temel amacı, birden fazla motorun güvenli ve verimli bir şekilde çalıştırılmasını, durdurulmasını, aşırı yük durumlarının yönetilmesini ve hız bilgilerinin gerçek zamanlı olarak izlenmesini sağlamaktır.

1. Proje Özellikleri
Bu otomasyon projesi, aşağıdaki temel özellikleri sunar:

Çoklu Motor Kontrolü: Sekiz adede kadar motorun ayrı ayrı Başlatma/Durdurma kontrolü.

Acil Durdurma Fonksiyonu: Güvenlik için entegre acil durdurma (Emergency Stop) mekanizması.

Motor Durum İzleme: Motorların çalışma, durma ve aşırı yük durumlarını gösteren LED göstergeleri.

Aşırı Yük Koruması: Motor aşırı yük durumlarının tespiti ve koruma mekanizması ile motorların zarar görmesi önlenir.

Hız Ölçümü ve Hesaplama: Yakınlık sensörü kullanarak motor hızının (RPS - Saniyedeki Devir, RPM - Dakikadaki Devir, RPH - Saatteki Devir) gerçek zamanlı ölçümü ve hassas hesaplaması.

Kullanıcı Dostu HMI Arayüzü: Motor kontrolü ve hız verilerinin kolayca görselleştirilmesi için tasarlanmış sezgisel bir HMI ekranı.

Modüler Program Yapısı: Yeniden kullanılabilir fonksiyon blokları (FB) ve veri blokları (DB) kullanılarak düzenli ve ölçeklenebilir bir PLC program yapısı. Bu, projenin bakımını ve gelecekteki genişletmelerini kolaylaştırır.

2. Kullanılan Donanım ve Yazılım
PLC: Siemens SIMATIC S7-1500 (veya S7-1200) serisi PLC (örneğin, CPU 1513-1 PN veya CPU 1214C).

HMI: Siemens SIMATIC HMI Comfort Panel (örneğin, KTP700 Comfort veya TP900 Comfort).

Sensörler: Motor hızını algılamak için endüktif yakınlık sensörleri.

Yazılım: Siemens TIA Portal V16 (veya üstü). Tüm PLC programlama, HMI tasarımı ve donanım konfigürasyonu bu entegre geliştirme ortamında yapılmıştır.

3. Proje Yapısı ve Dosyalar
Depo, TIA Portal projesinin yanı sıra projenin farklı aşamalarını ve arayüzlerini gösteren ekran görüntülerini de içermektedir. Tipik bir TIA Portal projesi aşağıdaki ana bileşenleri içerir:

PLC Programı: Program blocks altında ana organizasyon bloğu (OB1), fonksiyon blokları (FB'ler - örneğin, her bir motor için kontrol mantığı), fonksiyonlar (FC'ler) ve veri blokları (DB'ler - örneğin, motor parametreleri ve hız verileri için) bulunur.

HMI Projesi: HMI_1 altında ekranlar (Screens), bağlantılar (Connections), etiketler (Tags) ve alarmlar gibi HMI arayüzü bileşenleri yer alır.

Donanım Konfigürasyonu: PLC ve HMI'ın fiziksel bağlantıları ve modül konfigürasyonları.
