# Nesneye-Dayali-Programlama2-Vize


Veri Girişi (Input):

Yönetici sisteme araç ekler (Örn: 34 ABC 12, Fiat Egea, 1000 TL).

Başlangıçta tüm araçların statüsü MÜSAİT olarak veritabanına işlenir.

Kiralama (Process):

Kullanıcı bir araç seçer. Sistem arka planda UPDATE sorgusu çalıştırarak aracın durumunu KİRADA yapar ve o anın tarihini kaydeder.

Artık o araç, başkası tarafından kiralanamaz (Listede görünmez veya pasif görünür).

Teslim Alma (Output):

Araç geri geldiğinde sistem sorar: "Kaç gün kaldı?".

Girilen gün sayısı ile aracın gunluk_ucret değeri çarpılır ve ekrana Ödenecek Tutar: X TL yazdırılır.

Araç tekrar MÜSAİT moduna döner.

Kullanılan OOP Kavramları:

Class & Object: Her araç ve müşteri birer nesnedir.

Inheritance (Kalıtım): Arac sınıfından türetilen BinekArac ve TicariArac sınıfları.

Interface/Abstract: Fiyat hesaplama metodunun şablon olarak tanımlanması.
