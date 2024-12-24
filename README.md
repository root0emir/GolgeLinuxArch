<h1>Golge Linux Arch - Arch tabanlı gizlilik ve güvenlik odaklı işletim sistemi</h1>

<h3>Sürümler</h3>

-Golge Linux Arch : xfce4 masaüstü düşük iso boyutu gizlilik araçları yanlızca liveuser çalışır

-Golge Linux Debian : alternatif olarak geliştirilen debian tabanlı sürümü arch sürümü ile aynı özellikleri taşır ve hala geliştirilme aşamasındadır.

----
Siber saldırıların ve şirketlerin kullanıcı verilerini izleme çabalarının arttığı günümüzde, internette gizlilik ve güvenlik herkesin en temel hakkıdır. Gölge Linux Arch, bu ihtiyaca yanıt veren, Arch Linux tabanlı, anonimlik ve güvenlik odaklı bir işletim sistemidir.

Bu işletim sistemi, hız ve güvenlik açısından optimize edilmiştir. Sadece Live Mode'da çalışan Gölge Linux, kullanıcıların iz bırakmadan internette gezinmelerine olanak tanır. Tüm işlemler RAM'de gerçekleştirildiği için, sistem kapatıldığında veya USB çıkarıldığında tüm veriler silinir.

Gölge Linux Arch'ın Özellikleri:

Arch Tabanlı Bir Dağıtım:
Arch Linux'un düşük ISO boyutu, hız ve sürekli güncel pacman depoları sayesinde güçlü bir altyapı sunar. Kullanıcılar düzenli olarak güvenlik güncellemelerine erişebilir.

Özel Güvenlik Yapılandırması:
Gölge Linux, kötü amaçlı yazılımlara karşı dayanıklıdır. Çoğu virüs, sistemde hiçbir etki oluşturamaz.

Sadece Live User Modunda Çalışır:
Kurulum gerektirmez. Kullanıcılar USB'den bağlayarak doğrudan kullanabilir. Arch Linux'un zorlu kurulum sürecini tamamen ortadan kaldırır.

Unutkan Özellik:
Gölge Linux’un en yenilikçi ve güçlü özelliklerinden biri olan Unutkan Özellik, sistemin tamamen geçici bellek (RAM) üzerinde çalışmasını sağlar. Bu sayede, tüm kullanıcı verileri yalnızca oturum süresince RAM’de tutulur ve sistem kapatıldığında veya USB çıkarıldığında veriler tamamen silinir.

Bu özellik, kullanıcıların iz bırakmadan çalışmasına olanak tanır. Kişisel veriler fiziksel diskte hiçbir şekilde depolanmaz, böylece hem siber saldırılara hem de fiziksel veri ele geçirme girişimlerine karşı maksimum güvenlik sağlanır. Live Mode özelliğiyle taşınabilir bir yapıya sahip olan Gölge Linux, USB çıkarıldığında RAM üzerindeki tüm işlemleri ve bilgileri anında temizler.

Unutkan Özellik, özellikle hassas bilgiyle çalışan gazeteciler, araştırmacılar, siber güvenlik uzmanları ve çevrimiçi gizliliğe önem veren kullanıcılar için ideal bir çözüm sunar. Bu özellik yalnızca güvenlik sağlamakla kalmaz, aynı zamanda kullanıcı gizliliğini de en üst seviyeye çıkarır.

XFCE4 Masaüstü:
Hızlı, kullanıcı dostu ve sade bir masaüstü ortamı ile sistem performansı en üst seviyeye çıkarılmıştır.

Açık Kaynak Kodlu:
Gölge Linux tamamen açık kaynak kodludur, kullanıcılar istedikleri gibi inceleyip değişiklikler yapabilirler. Topluluk desteği de sağlanır.

Gizlilik ve Güvenlik Araçları:
Varsayılan olarak gizlilik ve güvenlik araçlarıyla birlikte gelir, kullanıcıların ekstra kurulum yapmalarına gerek kalmaz.

Tor Yönlendirme Aracı:
Gölge Linux'a özel olarak geliştirilmiş bu araç, tüm internet trafiğini Tor üzerinden yönlendirir ve DNS sızıntılarını engeller.

Siber Güvenlik Paketi:
Siber güvenlik uzmanları için gerekli temel araçları pacman depolarından kolayca yükleyebilme özelliği sunar.

Gölge Linux Debian:
Debian tabanlı alternatif bir sürüm halen geliştirilme aşamasındadır.

Hedef Kitle:

Anonimlik ve Gizliliğe Önem Veren Kullanıcılar: İnternette iz bırakmadan gezinmek isteyen bireyler.

Çevrimiçi Güvenlik Arayan Kullanıcılar: Tor ile internet trafiğini gizlemek ve güvenliği artırmak isteyenler.

Siber Saldırılardan Korunmak İsteyenler: Dijital tehditlerden uzak kalmayı hedefleyen kullanıcılar.

Taşınabilirlik Arayanlar: Live Mode özelliği sayesinde USB üzerinden taşınabilir bir işletim sistemi isteyenler.

Siber Güvenlik Uzmanları: Güçlü güvenlik araçlarıyla hızlıca testler gerçekleştirmek isteyen profesyoneller.

Gazeteciler ve Aktivistler: İnternet üzerindeki gizliliğini korumak, hassas bilgileri güvenle işlemek isteyen medya mensupları ve aktivistler.

----

<h2>Güncellemeler ve hata düzeltmeleri geçmişi</h2>

GolgeLinuxArch Version : 1.0

-Artık yanlızca liveuser olarak kullanılabiliyor amnesic işletim sistemi olarak tasarlandı her kullanımda sıfırlanarak önceki oturumda yapılan tüm işlemleri unutur, böylece iz bırakmaz.

-Ek güvenlik araçları ve yapılandırmaları eklendi.

-XFCE4 masaüstü ile hızlı basit hafif bir kullanım sunar.

Golge Linux Version : 1.1

-Hata düzeltmeleri ve yenilikler.

Golge Linux Version : 1.2

-Fazlalık paketler kaldırıldı araçların sayısı düşürüldü airootfs - cowspace sorunu üzerine çalışıyorum. Geçici çözüm için sistem başladıktan sonra terminali açıp: sudo mount -o remount,size=SIZE /run/archiso/cowspace  komutu girin SIZE yazan yere ram miktarınıza göre 
bir boyut girin. (sorun düzeltildi)

Golge Linux Version : 1.3

-Bazı Gizlilik araçları test edildi.

Golge Linux Version : 1.4 

-cowspace sorunu çözüldü kritik sistem hataları düzeltildi Golge Linux varsayılan olarak 4gb ram kullanır

Golge Linux Version : 1.5

-Gizlilik araçları sayısı çok daha fazla artırıldı

-Hatalar düzeltildi

---------------

UYARI:  Henüz geliştirilme aşamasındadır ve Arch tabanlı olduğu için yalnızca ileri seviye kullanıcılar içindir.

GolgeLinuxArch, Arch Linux tabanlı, gizlilik ve anonimlik odaklı özelleştirilmiş bir Linux dağıtımıdır. Kullanıcıların anonimliklerini ve gizliliklerini korumak için tasarlanmış bir dizi araç ve özellik sunar.

Herhangi bir sorun ya da katkı önerisi için benimle iletişime geçebilirsiniz.

GitHub: root0emir 


--------------------------------------------------------------------------------------------------------------------------------

GolgeLinuxArch

WARNING: It is still under development and, being Arch-based, is intended for advanced users only.

GolgeLinuxArch is a privacy and anonymity-focused, customized Linux distribution based on Arch Linux. It provides a set of tools and features designed to protect users' anonymity and privacy.

For any issues or contribution suggestions, feel free to contact me:

GitHub: root0emir
