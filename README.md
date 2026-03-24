Araç Yoğunluğuna Göre Dinamik Trafik Işığı Simülasyonu

Bu proje JavaFX kullanılarak geliştirilen bir trafik simülayon sistemidir.

Proje Yapısı

src/
├── main/
│ ├── java/
│ │ └── com/example/trafficgrok/traffic/
│ │ ├── controller/ → Kontrol sınıfları (ör. SimulationController)
│ │ ├── model/ → Model sınıfları (TrafficLight, Vehicle vb.)
│ │ ├── view/ → Arayüz destek sınıfları
│ │ └── Main.java → Uygulamanın giriş noktası
│ └── resources/
│ └── com/example/trafficsimulation/
│ └── fxml/ → FXML dosyaları (arayüz sahneleri)
└── README.md → Bu açıklama dosyası

Kurulum ve Derleme Talimatları
Gerekli Gereksinimler
Java SDK 17 veya üzeri
IntelliJ IDEA
Scene Builder (FXML ile GUI tasarımı)

JavaFX Kütüphanesini Projeye Ekleme
File > Project Structure > Libraries yolunu takip et.
'+' butonuna tıklayıp JavaFX SDK klasörünü seç.
'lib' klasörünü ekle.

Projeyi Derleme ve Çalıştırma
'Main.java' dosyasını aç.
Sağ tık Run 'Main.main' seçeneğine tıkla veya SHIFT F10'a bas.
Simülasyon arayüzü açılır ve çalışmaya başlar.

Özellikler
Gerçek zamanlı trafik ışığı simülasyonu
Yoğunluğa bağlı araç üretimi
MVC mimarisi ile yapılandırılmış
JavaFX ve Scene Builder kullanılarak geliştirilmiştir.
Arayüz Scene Builder ile .fxml dosyaları şeklinde tasarlanmıştır.
Görsel tasarım ile mantık kodları ayrıştırılarak temiz bir yapı kurulmuştur.

<img width="919" height="924" alt="image" src="https://github.com/user-attachments/assets/356b4ab7-c224-4392-83bc-f265b49a812e" />
